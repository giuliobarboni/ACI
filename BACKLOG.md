# Backlog: [NOME PROGETTO]

<!--
  📋 ISTRUZIONI PER IL DESIGNER
  Questo file contiene l'elenco completo delle feature del prodotto, organizzate
  per area funzionale con priorità e stato di avanzamento.

  Claude lo usa per:
  1. Capire il contesto di una feature rispetto al prodotto complessivo
  2. Identificare dipendenze tra feature (es. "il checkout dipende dal carrello")
  3. Sapere cosa è già implementato e cosa non ancora

  AGGIORNAMENTO:
  - Quando una feature viene avviata → cambia stato in "In Progress"
  - Quando una feature viene completata → cambia stato in "Done" e aggiungi link alla spec
  - Quando emergono nuove feature → aggiungile con stato "Backlog"

  STATI: Backlog | Ready | In Progress | Done
  PRIORITÀ: P0 (critica) | P1 (alta) | P2 (media) | P3 (bassa / nice to have)
-->

---

## Overview Prodotto

<!--
  📝 DA COMPILARE: 2-3 frasi che descrivono il prodotto e il suo scopo.
  Identico a PROJECT.md — serve come contesto rapido senza dover aprire altri file.
-->

**Prodotto:** [Es. Portale B2B per la gestione ordini di prodotti alimentari]
**Cliente:** [Nome cliente]
**Versione corrente:** [Es. V1 — MVP]

---

## Stato Avanzamento

| Totale feature | Done | In Progress | Ready | Backlog |
|---------------|------|-------------|-------|---------|
| [N]           | [N]  | [N]         | [N]   | [N]     |

<!-- 📝 Aggiorna questo riepilogo manualmente o chiedi a Claude di aggiornarlo -->

---

## Area: Autenticazione

| Feature                  | Priorità | Stato        | Spec                                    | Note                                         |
|--------------------------|----------|--------------|-----------------------------------------|----------------------------------------------|
| [Es. Login email/pw]     | `P0`     | `Done`       | [docs/specs/login.md](docs/specs/login.md) | [Es. Credenziali fornite da admin]         |
| [Es. Reset password]     | `P0`     | `Ready`      | —                                       | [Es. Flow via email con link temporaneo]     |
| [Es. Primo accesso]      | `P0`     | `Backlog`    | —                                       | [Es. Cambio password obbligatorio al primo login] |

---

## Area: [Es. Catalogo Prodotti]

<!-- 📝 DA COMPILARE: Sostituisci con le aree funzionali reali del prodotto -->

| Feature                  | Priorità | Stato        | Spec                                    | Note                                         |
|--------------------------|----------|--------------|-----------------------------------------|----------------------------------------------|
| [Es. Lista prodotti]     | `P0`     | `Backlog`    | —                                       | [Es. Con ricerca full-text e filtri]         |
| [Es. Scheda prodotto]    | `P0`     | `Backlog`    | —                                       | [Es. Immagini, prezzi, quantità, add to cart]|
| [Es. Bundle prodotti]    | `P1`     | `Backlog`    | —                                       | [Es. Set di prodotti frequenti pre-compilati]|

---

## Area: [Es. Carrello e Checkout]

| Feature                  | Priorità | Stato        | Spec                                    | Note                                         |
|--------------------------|----------|--------------|-----------------------------------------|----------------------------------------------|
| [Es. Carrello]           | `P0`     | `Backlog`    | —                                       | [Es. Lista prodotti, modifica quantità, totale] |
| [Es. Checkout]           | `P0`     | `Backlog`    | —                                       | [Es. No pagamento — solo indirizzo e conferma] |
| [Es. Conferma ordine]    | `P0`     | `Backlog`    | —                                       | [Es. Modal post-checkout con numero ordine]  |

---

## Area: [Es. Storico Ordini]

| Feature                  | Priorità | Stato        | Spec                                    | Note                                         |
|--------------------------|----------|--------------|-----------------------------------------|----------------------------------------------|
| [Es. Lista ordini]       | `P1`     | `Backlog`    | —                                       | [Es. Con ricerca e filtro per data]          |
| [Es. Dettaglio ordine]   | `P1`     | `Backlog`    | —                                       | [Es. Prodotti, CTA riordina, documenti]      |
| [Es. Richiesta reso]     | `P2`     | `Backlog`    | —                                       | [Es. Form → email, no automazione]           |

---

## Area: [Es. Account Utente]

| Feature                  | Priorità | Stato        | Spec                                    | Note                                         |
|--------------------------|----------|--------------|-----------------------------------------|----------------------------------------------|
| [Es. Dati aziendali]     | `P1`     | `Backlog`    | —                                       | [Es. Solo visualizzazione, non editabile]    |
| [Es. Indirizzi]          | `P1`     | `Backlog`    | —                                       | [Es. Lista + aggiungi nuovo via modal]       |
| [Es. Documenti legali]   | `P2`     | `Backlog`    | —                                       | [Es. T&C e Privacy Policy in PDF]            |

---

## Aree da Definire

<!-- 📝 DA COMPILARE: Feature identificate ma non ancora assegnate a un'area o abbastanza definite. -->

- [Es. Notifiche — da capire se email, in-app o entrambe]
- [Es. Dashboard analytics — solo per admin Padovana, fuori scope V1]

---

## Fuori Scope V1

<!-- 📝 DA COMPILARE: Feature esplicitamente escluse dalla versione corrente.
     Importante per evitare che vengano implementate per errore. -->

- [Es. Pagamento online]
- [Es. Self-registration utenti]
- [Es. App mobile nativa]
- [Es. Integrazione real-time con ERP]

---

## Dipendenze tra Feature

<!-- 📝 DA COMPILARE: Mappa le dipendenze logiche.
     Aiuta Claude a non implementare feature che dipendono da base non ancora costruita. -->

| Feature                | Dipende da                          |
|------------------------|-------------------------------------|
| [Es. Checkout]         | [Es. Carrello, Indirizzi spedizione]|
| [Es. Dettaglio ordine] | [Es. Lista ordini, Autenticazione]  |
| [Es. Bundle prodotti]  | [Es. Catalogo prodotti, Carrello]   |

---

## Testing e Qualità

| Task                                    | Priorità | Stato     |
|-----------------------------------------|----------|-----------|
| [Es. E2E: login e navigazione catalogo] | `P0`     | `Backlog` |
| [Es. E2E: add to cart e checkout]       | `P0`     | `Backlog` |
| [Es. Unit test: validazione form login] | `P1`     | `Backlog` |

---

## Sicurezza e Compliance

| Task                                         | Priorità | Stato     |
|----------------------------------------------|----------|-----------|
| [Es. Validazione input con Zod su tutte le API] | `P0`  | `Backlog` |
| [Es. Rate limiting su autenticazione]        | `P0`     | `Backlog` |
| [Es. Audit OWASP Top 10]                     | `P1`     | `Backlog` |
