# Information Architecture: [NOME PROGETTO]

<!--
  📋 ISTRUZIONI PER IL DESIGNER
  Questo file mappa la struttura completa del prodotto: schermate, navigazione,
  gerarchie e relazioni tra sezioni. È il documento che risponde alla domanda
  "dove si trova questa feature nel prodotto?".

  Claude lo legge per contestualizzare ogni feature prima di generare codice:
  sa così quali route usare, come si inserisce nella navigazione, da dove si arriva
  e dove si va dopo.

  Va aggiornato ogni volta che si aggiunge una nuova schermata o sezione.
-->

---

## Modello di Navigazione

<!-- 📝 DA COMPILARE: Descrivi il modello di navigazione principale.
     Es. sidebar fissa / top navigation / bottom navigation / menu a hamburger / combinazione -->

**Tipo:** [Es. Header fisso con navigazione laterale su desktop, bottom navigation su mobile]
**Autenticazione:** [Es. Le sezioni X e Y sono pubbliche, tutto il resto richiede login]

---

## Mappa delle Schermate

<!-- 📝 DA COMPILARE: Struttura ad albero di tutte le schermate del prodotto.
     Usa l'indentazione per indicare la gerarchia. Indica la route per ogni schermata.
     Aggiungi una breve descrizione dello scopo di ogni schermata. -->

```
/ (root)
├── /login                        → Accesso con email e password
├── /reset-password               → Reset password (flusso email)
│
└── [AREA AUTENTICATA]
    ├── /home                     → [Es. Catalogo prodotti — home del portale]
    │   └── /home?category=[id]   → [Es. Catalogo filtrato per categoria]
    │
    ├── /products
    │   └── /products/[id]        → [Es. Scheda prodotto di dettaglio]
    │
    ├── /cart                     → [Es. Carrello con lista prodotti e CTA checkout]
    │
    ├── /checkout                 → [Es. Checkout: indirizzo, note, conferma ordine]
    │   └── /checkout/success     → [Es. Conferma ordine completato]
    │
    ├── /orders                   → [Es. Storico ordini con ricerca e filtri]
    │   └── /orders/[id]          → [Es. Dettaglio ordine con documenti e CTA]
    │
    └── /account                  → [Es. Dati aziendali e impostazioni profilo]
        ├── /account/addresses    → [Es. Gestione indirizzi di spedizione]
        └── /account/documents    → [Es. Documenti: T&C, Privacy Policy]
```

<!-- Aggiungi, rimuovi o modifica le voci sopra in base al prodotto reale -->

---

## Flussi Principali

<!-- 📝 DA COMPILARE: Descrivi i 3-5 flussi utente più importanti come sequenze di schermate.
     Non serve un diagramma elaborato — anche una lista ordinata va benissimo.
     L'obiettivo è che Claude capisca le transizioni tra stati e schermate. -->

### Flusso 1: [Es. Primo accesso e reset password]
1. `/login` → utente inserisce credenziali temporanee
2. → redirect a `/reset-password` (obbligatorio al primo accesso)
3. → dopo reset, redirect a `/home`

### Flusso 2: [Es. Ordine rapido]
1. `/home` → utente seleziona bundle o cerca prodotto
2. → `/products/[id]` → aggiunge al carrello
3. → `/cart` → rivede lista e procede
4. → `/checkout` → seleziona indirizzo e conferma
5. → `/checkout/success` → conferma con numero ordine

### Flusso 3: [Es. Recupero documento da ordine precedente]
1. `/orders` → utente cerca ordine per data o numero
2. → `/orders/[id]` → apre dettaglio
3. → pannello documenti (overlay/drawer) → scarica PDF

<!-- Aggiungi altri flussi rilevanti -->

---

## Navigazione: Voci di Menu

<!-- 📝 DA COMPILARE: Lista delle voci di navigazione principale con la route corrispondente.
     Indica se una voce è visibile solo in certi contesti (es. solo da mobile, solo da admin). -->

| Voce          | Route         | Icona (riferimento)     | Visibilità         |
|---------------|---------------|-------------------------|--------------------|
| [Es. Catalogo]| `/home`       | [Es. grid / home]       | Sempre visibile    |
| [Es. Ordini]  | `/orders`     | [Es. receipt / list]    | Solo autenticato   |
| [Es. Carrello]| `/cart`       | [Es. shopping-cart]     | Con badge contatore|
| [Es. Account] | `/account`    | [Es. user / avatar]     | Solo autenticato   |

---

## Modali e Overlay

<!-- 📝 DA COMPILARE: Elenco dei contenuti che appaiono come modali, drawer o overlay
     piuttosto che come schermate separate. Importante per evitare che Claude
     crei pagine dove dovrebbero esserci modali e viceversa. -->

| Nome                        | Trigger                          | Tipo       | Contenuto                          |
|-----------------------------|----------------------------------|------------|------------------------------------|
| [Es. Aggiungi indirizzo]    | [Es. CTA in /account/addresses]  | Modal      | [Es. Form nuovo indirizzo]         |
| [Es. Conferma ordine]       | [Es. Submit in /checkout]        | Modal      | [Es. Riepilogo e CTA conferma]     |
| [Es. Documenti ordine]      | [Es. CTA "Documenti" in /orders/[id]] | Drawer | [Es. Lista PDF scaricabili]       |

---

## Empty States Globali

<!-- 📝 DA COMPILARE: Lista delle schermate che possono avere uno stato vuoto
     e come deve comportarsi la UI in quel caso. -->

| Schermata         | Condizione                        | Comportamento UI                              |
|-------------------|-----------------------------------|-----------------------------------------------|
| [Es. /orders]     | [Es. Nessun ordine ancora]        | [Es. Illustrazione + testo + CTA al catalogo] |
| [Es. /cart]       | [Es. Carrello vuoto]              | [Es. Messaggio + CTA al catalogo]             |
| [Es. /home]       | [Es. Nessun prodotto trovato]     | [Es. Messaggio di ricerca vuota + reset]      |
