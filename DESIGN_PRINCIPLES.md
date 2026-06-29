# Design Principles: [NOME PROGETTO]

<!--
  Questo file contiene il DNA visivo ed editoriale del progetto.
  Va letto PRIMA di implementare qualsiasi nuova feature o componente.

  NON contiene valori tecnici (token, px, hex) — quelli stanno in TOKENS.md.
  Contiene le REGOLE e il RAGIONAMENTO che guidano le decisioni di design.

  📝 DA PERSONALIZZARE:
  - La sezione "Creative Direction" va compilata dal designer con il carattere visivo del progetto
  - Le regole numerate (1–10) sono universali — modificale solo se il design system del progetto
    ha esigenze specifiche che le contraddicono
-->

---

## Creative Direction

<!--
  📝 DA COMPILARE: Descrivi il DNA visivo del progetto in massimo 3 paragrafi.
  Rispondi a: Qual è il tono visivo? Cosa rende questo prodotto diverso da uno generico?
  Quali sono i 2-3 principi compositivi che guidano ogni schermata?

  Esempi di domande utili per compilare questa sezione:
  - L'utente deve sentirsi in un tool professionale, in un'app consumer, in un servizio di lusso?
  - Come si usa il bianco/spazio vuoto? È minimalista, denso, editoriale?
  - La tipografia è il protagonista o è in secondo piano rispetto alle immagini?
  - Il colore brand è sparso ovunque o usato con parsimonia come accento?
-->

**North Star:** [Es. "Un tool B2B che sembra un prodotto di design, non un gestionale"]

**Principio 1 — [Nome]:** [Descrizione in 2-3 frasi]

**Principio 2 — [Nome]:** [Descrizione in 2-3 frasi]

**Principio 3 — [Nome]:** [Descrizione in 2-3 frasi]

---

## Regola n°1: Separazione per Tonal Shift, Non per Bordi

**Vietato** usare bordi `1px solid` per separare sezioni, raggruppare contenuto o definire aree della pagina.

I confini si definiscono **esclusivamente** attraverso il cambio di colore di sfondo tra superfici adiacenti (tonal shift).

```
✅ CORRETTO
Sidebar su surface-container-low
contro pagina su surface
→ la separazione è percepita, non disegnata

❌ SBAGLIATO
<div className="border border-gray-200">
  sidebar
</div>
```

**Unica eccezione:** i bordi su input e form (obbligatori per WCAG 1.4.11 — vedi Regola n°9).

---

## Regola n°2: Surface Layering

Trattare la UI come una serie di strati fisici sovrapposti. Ogni layer ha il suo valore di superficie:

| Layer    | Token                           | Contesto                                      |
|----------|---------------------------------|-----------------------------------------------|
| 0        | `--color-surface`               | Sfondo pagina base                            |
| 1        | `--color-surface-container-low` | Sezioni, sidebar, aree di raggruppamento      |
| 2        | `--color-surface-container`     | Contenitori intermedi                         |
| elevated | `--color-surface-container-lowest` (bianco) | Card interattive, modali, primo piano |

Il movimento verso un layer più chiaro comunica **elevazione** e **interattività**. Una card su sfondo grigio chiaro è immediatamente percepita come cliccabile senza bisogno di bordi o ombre.

---

## Regola n°3: Uso Controllato del Colore Brand

Il colore brand primario è il "Precision Accent" del prodotto. Va usato **con parsimonia**.

Usi legittimi:
- CTA primaria (il bottone più importante della pagina)
- Stato errore critico (solo se il colore brand è un rosso / colore caldo)
- Accento su badge o stato chiave

Usi **vietati**:
- Sfondi decorativi
- Bordi decorativi
- Testo generico
- Hover state su elementi secondari

Se tutto è nel colore brand, niente lo è.

---

## Regola n°4: Ombre Soft, Mai Drop Shadow Tradizionale

Le ombre tradizionali (`box-shadow: 2px 2px 4px rgba(0,0,0,0.2)`) rendono la UI datata.

Per gli elementi flottanti (dropdown, modal, tooltip) usare solo ombre diffuse e leggere:

```css
/* ✅ Ombra cloud — morbida e moderna */
box-shadow: var(--shadow-float);   /* Es. 0 20px 40px rgba(0,0,0,0.06) */

/* ❌ Drop shadow classica — da evitare */
box-shadow: 2px 4px 8px rgba(0,0,0,0.2);
```

Per la maggior parte delle separazioni, non serve alcuna ombra — il tonal shift è sufficiente.

---

## Regola n°5: Glassmorphism per Elementi Floating (Opzionale)

<!--
  📝 DA PERSONALIZZARE: Includi questa regola solo se il design system del progetto
  prevede effetti glass (es. header sticky, modal overlay su contenuto).
  Altrimenti sostituisci con le regole di overlay specifiche del tuo progetto.
-->

La navigazione principale (header su scroll) e i pannelli floating possono usare l'effetto glass:

```css
background: var(--glass-bg);           /* rgba con opacity ~0.80 */
backdrop-filter: var(--glass-blur);    /* blur(16-20px) */
border-bottom: 1px solid var(--glass-border); /* ghost border opacity ~10% */
```

Questo crea profondità visiva tra il contenuto che scrolla sotto e il layer di navigazione sopra.

---

## Regola n°6: Gerarchia Tipografica Coerente

La scala tipografica va usata con coerenza:

- I **titoli display** hanno sempre `letter-spacing` negativo per l'effetto editoriale
- Le **label** sono **sempre ALL-CAPS** con `letter-spacing` positivo — usarle per metadata, SKU, overline
- Il **body** ha `line-height: 1.5-1.6` per garantire leggibilità
- Mai usare `#000000` per il testo — sempre il token `--color-on-surface`
- Il contrasto tra titolo e body è **incoraggiato** per creare gerarchia visiva chiara

---

## Regola n°7: Button Style Coerente

- Il bottone **primary** è l'azione più importante della pagina — uno solo per schermata
- Il bottone **secondary** ha un aspetto neutro e non compete con il primary
- Il bottone **ghost** usa solo testo con underline su hover — per azioni terziarie
- **Vietato** usare `border-radius: 9999px` (pill) per bottoni B2B — usa `--radius-md` per look professionale
- Il primary deve avere contrasto testo ≥ 4.5:1 (WCAG)

---

## Regola n°8: Liste Senza Divider

Le liste (ordini, prodotti, documenti, ricerche) non usano linee separatrici tra le righe.

La separazione si ottiene con **white space verticale** e con hover state tonale sull'item. Il risultato è una lista ariosa e moderna, opposta alla griglia da spreadsheet.

---

## Regola n°9: Accessibilità WCAG 2.1 AA (Vincolo Permanente)

**Ogni componente e ogni feature deve rispettare WCAG 2.1 AA.** Non è negoziabile.

### Contrasti minimi obbligatori

| Elemento | Requisito | Riferimento WCAG |
|---|---|---|
| Testo normale (< 18px) | ≥ 4.5:1 contro sfondo | 1.4.3 |
| Testo grande (≥ 18px / bold ≥ 14px) | ≥ 3:1 contro sfondo | 1.4.3 |
| Bordi e contorni di componenti UI (input, button) | ≥ 3:1 contro colori adiacenti | 1.4.11 |
| Indicatori di stato (icone, badge senza testo) | ≥ 3:1 contro sfondo | 1.4.11 |
| Placeholder text | ≥ 4.5:1 contro sfondo input | 1.4.3 |

### Regole per i form (Input, Select, Textarea)

- **Sfondo**: sempre `--color-input-bg` (grigio visibile, non bianco — permette al bordo di essere visibile)
- **Bordo**: `--color-input-border` con contrasto ≥3:1 — bordo pieno tutto intorno, mai solo bottom border
- **Placeholder**: `--color-placeholder` con contrasto ≥4.5:1 su sfondo input
- **Focus**: `focus-visible:ring-2` con `--color-primary` + cambio colore bordo
- **Errore**: bordo diventa `--color-error`, `aria-invalid="true"` sull'elemento
- **Collegamento errore**: `aria-describedby` tra input e testo di errore — obbligatorio

### Regole per i bottoni (Button)

- **Focus**: `focus-visible:outline-2` con `--color-on-surface` — visibile su qualsiasi sfondo
- **Loading**: `aria-busy="true"` durante lo stato di caricamento
- **Disabled**: elementi disabilitati sono esenti da requisiti di contrasto (eccezione WCAG 1.4.3)

### Regole per la navigazione e le interazioni

- Ogni elemento interattivo deve avere un indicatore di focus visibile (`focus-visible`)
- Le azioni destructive o irreversibili devono avere un passo di conferma
- I messaggi di errore dinamici devono usare `role="alert"` o `aria-live`
- Le icone decorative devono avere `aria-hidden="true"`
- Le icone funzionali devono avere `aria-label` o testo visibile associato

### Strumenti di verifica consigliati

- [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) per verificare ratio
- Axe DevTools browser extension per audit automatici
- Navigazione solo da tastiera (Tab / Shift+Tab / Enter / Space) come test manuale

---

## Regola n°10: Same Pattern, Same Component

**Se due elementi UI hanno lo stesso aspetto visivo, devono condividere lo stesso componente atom.**

Non è sufficiente che abbiano lo "stesso stile" — se le classi CSS sono identiche o quasi, è un pattern che deve vivere in un unico posto.

```
✅ CORRETTO
Header "Home / Prodotti / Ordini"   →  <NavTab>
CategoryNav "Tutti / Cat A / Cat B" →  <NavTab>
→ un solo atom, zero deriva di stile

❌ SBAGLIATO
Header:      <Link className="px-3 py-2 text-label-sm uppercase font-black..." />
CategoryNav: <Link className="px-4 py-2 text-body-md font-semibold bg-surface..." />
→ stesso pattern, due implementazioni diverse → deriva inevitabile
```

**Segnali d'allarme** — se ti trovi in una di queste situazioni, fermati ed estrai un atom:

1. Stai per copiare un blocco di classi CSS da un altro componente
2. Stai scrivendo classi identiche a quelle di un componente già esistente in un nuovo file
3. Due componenti hanno lo stesso comportamento visivo (hover, active, focus) ma nomi diversi
4. Stai implementando una "variante" di un elemento già esistente aggiungendo classi in un nuovo posto

**Regola pratica:** cerca le classi che stai per scrivere in `Grep` prima di scriverle. Se le trovi già in un altro componente, valuta se estrarre un atom condiviso.

---

## Do's and Don'ts — Riferimento Rapido

### ✅ Fare

- Usare white space generoso — se sembra abbastanza, valuta di aggiungerne ancora
- Separare le sezioni solo con tonal shift di superficie
- Usare `label` ALL-CAPS per SKU, codici e metadata tecnici
- Verificare sempre i contrasti con i token WCAG prima di usare un colore non standard
- Usare icone stroke sottili per l'estetica moderna e leggera

### ❌ Non Fare

- Non usare `#000000` per il testo — sempre il token `--color-on-surface`
- Non usare drop shadow tradizionali — solo cloud shadow o tonal shift
- Non usare il colore brand come elemento decorativo
- Non usare linee divisorie tra list item — usare spacing
- **Non usare valori hardcoded di nessun tipo** — né hex (`#ffffff`), né numerici (`14px`, `p-4`), né classi Tailwind built-in (`text-sm`, `font-semibold`, `rounded-md`, `w-4`) — tutto deve venire dai token in `TOKENS.md` / `app/globals.css`
- Se il token non esiste: aggiungilo a `TOKENS.md` e `app/globals.css` prima di usarlo nel componente
