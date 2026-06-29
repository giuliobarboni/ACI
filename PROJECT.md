# Project: Redesign Sito ACI Global Servizi

<!--
  📋 Questo file è il punto di partenza del progetto. Compilato a valle della ricerca desk
  (dati di mercato, dati utenti, insight preliminari). Letto da Claude all'inizio di ogni
  sessione per il contesto business. Le fonti di dettaglio sono nelle pagine HTML in /pages
  e nei file di fase in /docs.
-->

---

## Overview

Redesign del sito web di **ACI Global Servizi**, azienda di soccorso stradale e assistenza alla mobilità. L'obiettivo è trasformare un sito oggi strutturato secondo l'organigramma del gruppo in un prodotto digitale costruito attorno ai bisogni reali degli utenti, capace di supportare sia chi si sta informando prima del bisogno sia chi è in emergenza, e di valorizzare il riposizionamento avviato con l'acquisizione da parte di Sara Assicurazioni.

**Prodotto:** Sito web istituzionale e di servizio (soccorso stradale e assistenza alla mobilità)
**Cliente:** ACI Global Servizi (parte di Sara Assicurazioni da fine 2025 / inizio 2026)
**Dominio:** Soccorso stradale / Automotive / Mobilità e assistenza
**Tipo di prodotto:** Web app / Sito di servizio (responsive, mobile-first sui task di emergenza)

---

## Obiettivi di Business

- **Ridurre il carico sul numero verde 803.116** rendendo autonomamente risolvibili online le domande elementari (costi, condizioni, copertura, "cosa fare se…", stato pratica), oggi causa di chiamate evitabili.
- **Aumentare la fiducia percepita** colmando il divario tra brand forte e percezione del servizio (Trustpilot ACI 1,9/5 vs competitor AutoAssist 4,3/5), portando in evidenza i dati aggregati di affidabilità.
- **Spostare il posizionamento da "i più veloci" a "sai cosa aspettarti"**: promessa più solida e differenziante, meno esposta a smentite dalla singola esperienza negativa.
- **Rendere trasparenti costi e condizioni** (tariffe, km coperti, orari, limiti geografici, auto sostitutiva) prima del bisogno, eliminando le "condizioni non dichiarate" — il reclamo numero uno nelle recensioni.
- **Abilitare l'espansione "beyond automotive"** prevista dal gruppo Sara, con un'architettura modulare e scalabile.
- **Valorizzare la garanzia istituzionale di Sara Assicurazioni**, oggi nascosta come logo nel footer.

---

## Utenti Target

La ricerca non identifica personas discrete ma **tre fasi del journey con bisogni diversi**, e due modalità d'uso dominanti (informativa vs transazionale/emergenza).

### Profilo 1: Utente pre-evento (modalità informativa)
- **Contesto d'uso:** A freddo, prima del bisogno; valuta l'iscrizione o confronta coperture. Desktop o mobile, senza stress.
- **Familiarità digitale:** Media; abituato a cercare risposte su forum, articoli e recensioni di terzi.
- **Bisogno principale:** Capire "conviene la tessera? quanto costa se non sono socio? cosa è incluso? funziona all'estero?".
- **Frustrazione attuale:** Tariffe sepolte in PDF non ricercabili; FAQ sparse in navigazione profonda; risposte trovate solo su siti terzi (Motor1, Quora).

### Profilo 2: Utente in emergenza (modalità transazionale)
- **Contesto d'uso:** Auto in panne, alto stress emotivo, da mobile, a bordo strada. Friction zero richiesta.
- **Familiarità digitale:** Irrilevante in quel momento: vuole solo agire subito.
- **Bisogno principale:** "Chi chiamo? quanto aspetto? dov'è il carro attrezzi?".
- **Frustrazione attuale:** Il numero 803.116 non è l'endpoint esplicito di nessun percorso e non è persistente; l'incertezza sui tempi è peggiore dell'attesa stessa.

### Profilo 3: Utente post-intervento
- **Contesto d'uso:** Dopo il soccorso; gestisce officina, auto sostitutiva, rimborsi.
- **Bisogno principale:** "Quando arriva l'auto sostitutiva? dov'è la mia auto? devo pagare? qual è l'officina convenzionata?".
- **Frustrazione attuale:** Nessun tracking dello stato pratica, nessun contenuto sulla fase post: la fiducia si rompe proprio qui.

### Segmento B2B (fleet manager)
- Bisogni distinti (SLA, rendicontazione, referenze) oggi completamente assenti: le pagine Aziende sono una copia delle pagine Privati. Lo split B2B/B2C è una **open question** da chiarire con dati interni.

---

## Insights da Ricerca Utenti

> Fonti: 64 recensioni Trustpilot ACI Global + 300+ ACI Italia, forum (CamperOnLine, Triumph), Quora, articoli di settore. Dati a campione (bias di auto-selezione): segnali di pattern, non distribuzione statistica. 6 insight selezionati per il cliente su 11 analizzati.

- **Trasparenza su costi e condizioni** → le condizioni non dichiarate (sovrapprezzi, km, orari, limiti) sono il reclamo #1. Le tariffe devono essere consultabili in HTML dentro le pagine servizio, non in PDF, con sezione "cosa è incluso / non incluso" ed esempi concreti.
- **L'app i803116 è funzionalmente superiore ma nascosta** → integra già geolocalizzazione, click-to-call, tracking e memoria posizione auto, ma è relegata in "Chi siamo". Va promossa in homepage e nelle pagine soccorso come canale alternativo al telefono.
- **Due modalità d'uso non riconosciute dall'IA attuale** → informativa vs emergenza vanno separate. IA per task utente (non per organigramma); numero verde persistente in ogni schermata; sezione informativa autonoma e linkabile.
- **L'utente non distingue tra ACI / ACI Global / Sara** → viene rimbalzato tra entità del gruppo. Il sito deve chiarire esplicitamente cosa fa ACI Global Servizi e gestire gli handoff senza costringere l'utente a capire la struttura societaria.
- **Posizionamento sulla certezza, non sulla velocità** → gli utenti accettano attese lunghe se prevedibili; a frustrare è la revisione ripetuta delle stime. Comunicare tempi medi, tracking e dati di affidabilità aggregati.
- **Il timing dell'acquisizione Sara abilita il riposizionamento** → ACI Global è il "fulcro" dei servizi di assistenza integrata Sara, in espansione oltre l'automotive. IA modulare e scalabile; Sara esplicita come garante istituzionale.

**Dati di fiducia da valorizzare:** 88% soddisfazione · 300 operatori h24 · 1.800 partner multiservizio · 32 Paesi (rete ARC Europe) · 10 milioni di minuti gestiti.

**Pain point ad alta risolvibilità via web (massimo ROI):** opacità sui costi · condizioni scoperte solo durante il servizio · auto sostitutiva (quando/come/a quali condizioni) · rimbalzo tra entità del gruppo.

---

## Benchmark e Decisioni di Stile

- **Posizionamento sulla certezza (modello AutoAssist, 4,3/5)** adottato al posto della promessa di velocità: comunicare aspettative realistiche + aggiornamenti in tempo reale è più solido e meno smentibile.
- **Carousel editoriale above-the-fold scartato:** CTR medio <1% sulla prima slide, quasi zero sulle successive; non comunica la value proposition né offre un endpoint di task.
- **Tariffe in HTML scansionabile** (non PDF da scaricare) preferite per ridurre il carico cognitivo in un momento già stressante e per non bloccare i processi di procurement B2B.
- **App come canale primario** in linea con la crescita del mercato delle app assicurative (CAGR 12%, da $9,5B 2023 a $26,7B 2032).
- **Dati aggregati di affidabilità come trust signal** nelle pagine servizio, non sepolti in "Chi siamo".

---

## Vincoli e Note Tecniche

- **Riposizionamento post-acquisizione:** l'architettura deve essere modulare per accogliere l'espansione "beyond automotive" senza destabilizzare l'offerta core.
- **Vincolo organizzativo di gruppo:** ACI Global Servizi non vende tessere (lo fa ACI Italia) né polizze (Sara Assicurazioni); il sito deve gestire i confini e gli handoff tra entità.
- **Tariffe oggi in PDF** generati dal cliente, suddivisi per tipo di intervento e fascia oraria — da convertire in contenuto consultabile.
- **App esistente (i803116)** già disponibile su iOS/Android: asset da integrare, non da costruire.
- **Domanda strutturale solida per 15+ anni** (parco auto vecchio: 42% Euro 4 o inferiore, età media 13 anni) → il modello di business tradizionale resta valido.
- **Accessibilità e mobile-first** critici nei task di emergenza (utente sotto stress, a bordo strada).

### Open questions per la fase successiva (richiedono dati primari / analytics)
1. Distribuzione del traffico per intento (informativo vs emergenza vs post-evento).
2. Funnel di conversione attuale e punti di abbandono.
3. Target effettivo: solo soci? non soci? entrambi?
4. Split di fatturato B2B vs B2C (percorsi potenzialmente separati).

---

## Stack Tecnico

<!-- Stack non ancora concordato con il team di sviluppo — TBD prima della prototipazione. -->

- **Framework:** TBD
- **Styling:** TBD
- **Language:** TBD
- **Font:** TBD
- **Database:** TBD
- **Autenticazione:** TBD
- **Deploy:** TBD

### Figma

- **UI File:** [SA — Sito AGSE](https://www.figma.com/design/C9yCwPmqVTXSB1XX4u2kFn/SA---Sito-AGSE?node-id=11-141&t=3jyBVd17vpO4LABJ-1)
- **Design System:** `[TBD]`
- **Schermate chiave in Figma:** `[TBD]`

---

## File Correlati

- [`docs/00-Contesto.md`](./docs/00-Contesto.md) — Contesto di progetto e vincoli fissi
- [`docs/01-analisi-as-is.md`](./docs/01-analisi-as-is.md) — Analisi as-is del sito attuale
- [`docs/02-ricerca-desk-senza-dati-primari.md`](./docs/02-ricerca-desk-senza-dati-primari.md) — Ricerca desk
- [`docs/03-user-personas-senza-dati-primari.md`](./docs/03-user-personas-senza-dati-primari.md) — User personas
- [`docs/04-benchmark.md`](./docs/04-benchmark.md) — Benchmark competitivo
- [`docs/05-pilastri-e-direzioni-strategiche.md`](./docs/05-pilastri-e-direzioni-strategiche.md) — Pilastri e direzioni strategiche
- [`docs/06-architettura-informazione.md`](./docs/06-architettura-informazione.md) — Architettura dell'informazione
- [`docs/07-wireframes.md`](./docs/07-wireframes.md) — Wireframes
- [`docs/09-presentazione.md`](./docs/09-presentazione.md) — Presentazione cliente
- [`pages/`](./pages/) — Report HTML: Insight, Dati mercato, Dati utenti, Aree critiche (index)
- [`IA.md`](./IA.md) — Architettura delle informazioni
- [`DESIGN_PRINCIPLES.md`](./DESIGN_PRINCIPLES.md) · [`DECISIONS.md`](./DECISIONS.md) · [`BACKLOG.md`](./BACKLOG.md)
