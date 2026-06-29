# 04 · Benchmark — File Operativo

<!--
  Questo file registra i deliverable compilati del benchmark, passaggio per passaggio.
  Scopo: sopravvivere ai compact del contesto. Ogni volta che un passaggio è completato
  e validato dal designer, il risultato viene scritto qui. Claude legge questo file
  all'inizio di ogni sessione di benchmark per recuperare il contesto perso.
-->

---

## Passaggio 1 · Cluster definiti e validati

### Cluster 1 — Baseline di categoria
**Nome:** Baseline di categoria — cosa fa già il mercato su trasparenza, fiducia e B2B
**Razionale:** Il gap Trustpilot (ACI 1,9 vs AutoAssist 4,3) e la presenza di competitor europei più maturi (ADAC, RAC, AA) pongono una domanda concreta: su quali specifici problemi già risolti ACI Global è indietro? Il cluster non mappa "il mercato" in senso generico, ma legge i competitor diretti attraverso le lenti degli insight chiave — D1 (trasparenza tariffe/condizioni), S2 (certezza vs velocità), e il gap B2B (pagine aziende oggi copia delle pagine privati). Risponde alla domanda: qual è lo standard minimo di categoria che il redesign deve raggiungere o superare?
**Tipo di player:** Servizi di soccorso stradale e assistenza mobilità con reputazione online alta o con area business sviluppata — IT, EU, US/Canada.

### Cluster 2 — Gestione dell'emergenza & tracking real-time
**Razionale:** Risponde alla modalità emergenza (insight D3) e al pain "incertezza peggiore dell'attesa". Come si progetta un'azione urgente a friction zero, con CTA persistente, click-to-call, e soprattutto tracking "dov'è il mezzo / quanto manca".
**Tipo di player:** Prodotti best-in-class su azione urgente e tracking — ride-hailing, food/grocery delivery, app di emergenza/assistenza — oltre ai flussi di richiesta soccorso dei competitor europei.
**Alimentato da:** Cross-settore + competitor europei.

### Cluster 3 — Trasparenza su prezzi e condizioni
**Razionale:** Affronta l'insight #1 (D1, condizioni non dichiarate). Come si rendono costi variabili, limiti e "cosa è incluso/non incluso" leggibili prima dell'impegno, senza PDF.
**Tipo di player:** Servizi a tariffa variabile o condizioni complesse che le comunicano in chiaro — assicurazioni dirette, utility/telco, servizi con preventivo trasparente.
**Alimentato da:** Cross-settore + qualche competitor.

### Cluster 4 — Fiducia, prova sociale e certezza
**Razionale:** Sostiene il riposizionamento "sai cosa aspettarti" (S2) e la valorizzazione dei dati di affidabilità (88%, 300 operatori h24, 1.800 partner, 32 Paesi) + garanzia Sara. Come si riduce l'incertezza e si costruisce credibilità sistemica (non del singolo operatore).
**Tipo di player:** Prodotti che eccellono nel trust-building — recensioni aggregate, social proof, dati di performance, garanzie istituzionali.
**Alimentato da:** Cross-settore + competitor.

### Cluster 5 — Ecosistemi multi-entità & multi-servizio scalabili
**Razionale:** Copre S1 (l'utente non distingue ACI / ACI Global / Sara) e S3 (espansione beyond automotive). Come un brand ombrello orchestra più entità/servizi senza confondere, gestisce gli handoff, e ospita un percorso B2B/fleet parallelo (SLA, rendicontazione, referenze) accanto al B2C.
**Tipo di player:** Gruppi assicurativi/mobilità, super-app di servizi, ecosistemi con offerta sia privati sia business.
**Alimentato da:** Cross-settore + competitor europei (per la parte B2B).

---

## Passaggio 2 · Domande di analisi per cluster

### Cluster 1 — Baseline di categoria
1. Come gestiscono la gerarchia "numero di emergenza vs contenuti informativi" in homepage?
2. Su quali temi puntano principalmente (empatia, efficienza, storia, social proof)?
3. Come gestiscono la navigazione per tipo di utente (privati vs aziende)?
4. Quali canali di contatto offrono oltre al numero verde e come li gerarchizzano?

### Cluster 2 — Gestione dell'emergenza & tracking
1. Come progettano l'azione urgente: friction, numero di step, accesso al contatto.
2. Come comunicano l'attesa e lo stato dell'intervento in tempo reale?
3. Come promuovono l'app come canale alternativo al telefono?
4. Come trattano la fase post-intervento?

### Cluster 3 — Trasparenza su prezzi e condizioni
1. Come rendono leggibili tariffe variabili o condizioni complesse senza rimandare a PDF?
2. Come strutturano la sezione "cosa è incluso / non incluso" con esempi concreti?
3. Come gestiscono la distinzione tra profili diversi (es. socio/non-socio, piano base/premium)?
4. Come presentano tariffe e condizioni nelle pagine servizio? HTML scansionabile o PDF nascosto?

### Cluster 4 — Fiducia, prova sociale e certezza
1. Quali dati di affidabilità sistemica usano (es. % soddisfazione, operatori, copertura) e dove li posizionano nel percorso utente?
2. Come usano recensioni aggregate, certificazioni o garanzie istituzionali senza che sembrino decorazione?
3. Come comunicano la certezza dell'outcome ("saprai cosa aspettarti") vs la promessa generica di qualità?
4. Cosa li fa preferire rispetto ad ACI nelle recensioni — qual è la leva di fiducia principale?
5. Come bilanciano l'identità del brand autonomo con la visibilità del brand proprietario o del gruppo di appartenenza — lo usano come garanzia istituzionale in evidenza, lo nascondono, o la relazione non emerge affatto?

### Cluster 5 — Ecosistemi multi-entità & multi-servizio scalabili
1. Come un brand ombrello gestisce più entità/servizi senza confondere l'utente — handoff chiari, non rimbalzi?
2. Come separano il percorso B2C da quello B2B senza duplicare le pagine?
3. Come comunicano la scalabilità dell'offerta (es. "oltre l'automotive") senza disorientare chi cerca il servizio core?
4. Come differenziano l'offerta B2C da quella B2B/fleet (SLA, rendicontazione, referenze)?

---

## Passaggio 3 · Player per cluster

### Cluster 1 — Baseline di categoria

| # | Player | URL | Stato analisi |
|---|--------|-----|---------------|
| 1 | AutoAssist (IT) | autoassist.it | ✅ Completato |
| 2 | AA – The Automobile Association (UK) | theaa.com | ✅ Completato |
| 3 | ADAC (DE) | adac.de | ✅ Completato |
| 4 | Europ Assistance (IT/multinazionale) | europassistance.it | ✅ Completato |
| 5 | AAA – American Automobile Association (US) | aaa.com | ✅ Completato |

**Descrizioni player:**
- **AutoAssist (IT):** Competitor diretto citato nella ricerca con Trustpilot 4,3/5 vs ACI 1,9/5. Termine di paragone immediato: stessa categoria, stesso mercato, punteggio fiducia opposto. Indispensabile per capire cosa fa diversamente sul piano della comunicazione.
- **AA – The Automobile Association (UK):** Leader britannico del soccorso stradale, uno dei siti di categoria più maturi digitalmente. Ottima reference per la gerarchia homepage emergenza/informazione e per come gestisce la navigazione privati/aziende su larga scala.
- **ADAC (DE):** Il più grande club automobilistico europeo. Reference strutturale per la comunicazione istituzionale, la gerarchia dei canali e il bilanciamento tra servizio d'emergenza e contenuto informativo. Scala e brand molto più forti di ACI Global.
- **Europ Assistance (IT/multinazionale):** Player internazionale con forte presenza italiana. Opera sia in B2C che in B2B (flotte aziendali, assicurazioni), con un parent brand (Generali) che deve bilanciare visibilità istituzionale e autonomia del sub-brand — rilevante per la domanda sul brand proprietario.
- **AAA – American Automobile Association (US):** Corrispettivo americano di ACI, scala enorme, sito molto evoluto. Utile per i pattern di navigazione per tipo di utente e per le leve di social proof nei mercati maturi.

> **Nota di metodo:** i 5 competitor base del Cluster 1 (**AutoAssist, AA, ADAC, Europ Assistance, AAA**) + RAC ricorrono attraverso i cluster, letti ogni volta con la lente specifica del cluster. È voluto: stesso player, analisi diversa. Affiancati da 1–2 player cross-settore per cluster.

### Cluster 2 — Gestione dell'emergenza & tracking real-time
_Lente: come gestiscono richiesta soccorso e "dov'è il mezzo / quanto manca"._

| # | Player | Tipo | Stato analisi | Perché qui |
|---|--------|------|---------------|-----------|
| 1 | **ADAC** | Competitor (ric.) | ✅ Completato | App Pannenhilfe con tracking del mezzo: il competitor europeo più avanzato sul nostro stesso flusso d'emergenza. |
| 2 | **AA (UK)** | Competitor (ric.) | ✅ Completato | Tracking disponibile sia via app che online; safety advice screen prima del reporting; "twice as fast as calling" come claim esplicito sull'app. |
| 3 | **RAC (UK)** | Competitor | ✅ Completato | Tracking in-app con GPS automatico e aggiornamenti push; app-only (no web tracking); OTP email login come barriera critica in emergenza. |
| 4 | **Uber** | Cross-settore | ✅ Completato | Gold standard del tracking real-time: mappa ETA in movimento, push per stati, comunicazione attesa progressiva. |
| 5 | **Glovo** | Cross-settore | ✅ Completato | Tracking su delivery urgente: stato in-app, notifiche push per ogni transizione, accesso diretto al corriere. |

### Cluster 3 — Trasparenza su prezzi e condizioni
_Lente: tariffe variabili e incluso/escluso senza PDF._

| # | Player | Tipo | Stato analisi | Perché qui |
|---|--------|------|---------------|-----------|
| 1 | **AutoAssist** | Competitor (ric.) | ✅ Completato | Zero prezzi sul sito; condizioni esclusivamente in PDF; nessun piano/profilo differenziato; trust delegato a Trustpilot, non alla trasparenza. |
| 2 | **Europ Assistance** | Competitor (ric.) | ✅ Completato | Architettura biforcata: SOD (99€ in hero, prezzo fisso visibile) vs Auto Noproblem (3 tier HTML ma nessun prezzo senza preventivo). FAQ come surrogate di condizioni leggibili. Unico player con pagamento mensile menzionato in hero. |
| 3 | **Iliad** | Cross-settore | ✅ Completato | Best practice assoluta del benchmark: prezzo in card + URL + titolo pagina, zero preventivo. Offerte storicamente stabili (Voce a 4,99€ dal 24/07/2018). HTML per tutto il contenuto commerciale; PDF solo per compliance AGCOM. "Senza vincoli e costi nascosti" come brand promise strutturale, non marketing. |
| 4 | **ConTe.it** | Cross-settore | ✅ Completato | Modello standard dell'assicurazione auto diretta italiana: zero prezzi pre-preventivo (strutturale al prodotto RCA, non scelta opaca), ma ogni garanzia accessoria ha pagina HTML con lista coperture. Franchigie/massimali/esclusioni rinviati a Set Informativo PDF o a post-contratto. Contratto Base IVASS unico punto con incluso/escluso esplicito in HTML. Profili differenziati solo nel preventivo, non nel sito pubblico. |
| 5 | **Lemonade** | Cross-settore | ✅ Completato | Assicurazione digitale-first: prezzi "from" visibili in homepage su tutti i prodotti, "what's covered / what's not covered" in HTML per ogni sezione, Policy 2.0 come primo documento di polizza open source interamente in HTML (non PDF). Non opera in Italia; cross-sector benchmark per pattern UX, non competitor diretto. |

### Cluster 4 — Fiducia, prova sociale e certezza
_Lente: trust sistemico, recensioni, dati di affidabilità, garanzia._

| # | Player | Tipo | Stato analisi | Perché qui |
|---|--------|------|---------------|-----------|
| 1 | **AutoAssist** | Competitor (ric.) | ✅ Completato | È la fonte del gap (Trustpilot 4,3 vs 1,9): qual è la leva di fiducia che lo fa preferire ad ACI. |
| 2 | **AAA (US)** | Competitor (ric.) | ✅ Completato | Social proof nei mercati maturi a scala enorme. Stesso player del Cl.1, lente fiducia. |
| 3 | **ADAC** | Competitor (ric.) | ✅ Completato | Trust istituzionale del club più grande d'Europa: dati e autorevolezza sistemica. |
| 4 | **Booking.com** | Cross-settore | ✅ Completato | Punteggi aggregati e review system scalabile: fiducia costruita nel sistema, non nel singolo hotel. |
| 5 | **Airbnb** | Cross-settore | ✅ Completato | Garanzia istituzionale AirCover: protezione sistemica comunicata come promessa di brand, non come polizza. |

### Cluster 5 — Ecosistemi multi-entità & multi-servizio scalabili
_Lente: brand ombrello + percorso B2B/fleet parallelo._

| # | Player | Tipo | Stato analisi | Perché qui |
|---|--------|------|---------------|-----------|
| 1 | **Europ Assistance** | Competitor (ric.) | ✅ Completato | Sub-brand con identità autonoma under Generali: come gestisce separazione visiva e handoff verso il parent. Stesso player del Cl.1/3, lente ecosistema. |
| 2 | **Generali** | Competitor (ric.) | ✅ Completato | Parent brand che orchestra sub-brand multipli: come rende visibile il gruppo senza cannibalizzare le entità figlie — diretto su S1 (ACI / ACI Global / Sara). |
| 3 | **AAA (US)** | Competitor (ric.) | ✅ Completato | Ecosistema multi-servizio (soccorso + assicurazioni + viaggi + banking) sotto un brand. Stesso player del Cl.1/4. |
| 4 | **ADAC** | Competitor (ric.) | ✅ Completato | Multi-servizio e area business/flotte accanto al B2C. Ricorre dal Cl.1/2/4. |
| 5 | **Amazon** | Cross-settore | ✅ Completato | B2C + Business (Amazon Business) paralleli sotto brand ombrello; upgrade path e percorsi separati senza duplicare. |
| 6 | **Revolut** | Cross-settore | ✅ Completato | Personal + Business (Revolut Business) con percorsi separati e upgrade path chiaro; multi-servizio sotto brand unico. |

---

## Passaggio 4 · Analisi dei player

### Cluster 1

#### AutoAssist (IT) — ✅ Completato
_Analisi completa prodotta in sessione. Screenshot caricati in Figma (Tema 1, 165:56)._

#### AA – The Automobile Association (UK) — ✅ Completato
_Screenshot caricati in Figma (Tema 1, 165:56): Homepage (175:2), Breakdown Cover 1/2 (185:2), Breakdown Cover 2/2 (184:2), Report Breakdown (177:2)._

**Risposte alle domande del Cluster 1**

**1. Come gestiscono la gerarchia "numero di emergenza vs contenuti informativi" in homepage?**
AA adotta un modello ibrido ma sbilanciato verso la conversione commerciale: il numero di emergenza (0800 887 766) è presente nell'header persistente, ma non è il fulcro visivo della homepage. L'hero è occupato dall'offerta di membership ("Join from £X/month") con CTA commerciale in evidenza. Il breakdown è raggiungibile via voce dal nav ("Breakdown"), ma in homepage viene trattato come servizio incluso nell'iscrizione, non come endpoint di urgenza autonomo. Chi è già membro trova il canale di emergenza rapidamente; chi non lo è incontra prima la proposta commerciale. *(Osservazione diretta.)*

**2. Su quali temi puntano principalmente (empatia, efficienza, storia, social proof)?**
AA punta su un mix di social proof istituzionale e efficienza dichiarata: "The UK's largest breakdown provider", numero di interventi gestiti, anni di presenza. Il tono è rassicurante e professionale, non empatico nel senso emotivo: affidabile nel senso di "siamo grandi, siamo qui da sempre, siamo ovunque". La storia del brand (oltre 100 anni) è evocata come garanzia, non come narrazione. L'empatia verso il momento di stress è assente: nessun copy che riconosca esplicitamente la condizione di chi è in panne. *(Osservazione diretta + inferenza.)*

**3. Come gestiscono la navigazione per tipo di utente (privati vs aziende)?**
La separazione è netta e strutturale: il nav principale ha una voce "Business" che porta a un'area dedicata con offerte, servizi e percorsi distinti da quelli privati. Le pagine business trattano SLA, flotte, gestione sinistri per aziende, rendicontazione — non sono una copia delle pagine privati. Il toggle è nella navigazione principale, visibile da ogni pagina. Modello diametralmente opposto all'attuale ACI Global. *(Osservazione diretta.)*

**4. Quali canali di contatto offrono oltre al numero verde e come li gerarchizzano?**
Oltre al numero telefonico (0800, nell'header), AA promuove l'AA App come canale alternativo equivalente: "Report a breakdown using the app" appare nelle pagine servizio accanto alla chiamata, non come opzione secondaria. Terzo canale: il portale web "My AA" per storico interventi, rinnovo membership, gestione post-intervento. Gerarchia implicita: app per chi è già membro → numero per chi preferisce parlare → portale per la gestione post. Nessun canale è nascosto. *(Osservazione diretta.)*

#### ADAC (DE) — ✅ Completato
_Screenshot caricati in Figma (Tema 1, 165:56): Homepage 1/2 (188:2), Homepage 2/2 (189:2), Pannenhilfe (190:2), Pannenhilfe Online (191:2)._

**1. Identità e posizionamento**
ADAC non è un servizio di soccorso stradale: è il più grande club automobilistico europeo, con un ecosistema che copre mobilità, viaggi, assicurazioni, salute e media editoriale. Il soccorso stradale ("Pannenhilfe") è un servizio incluso nella membership, non il posizionamento principale del sito. La homepage è un portale media/magazine, non una vetrina di servizio. Il brand "Gelbe Engel" (angeli gialli) è iconico in Germania: identifica i tecnici ADAC ed è il principale asset emozionale del club, usato però come garanzia istituzionale, non come leva empatica sull'urgenza.

**2. Stile visivo**
Giallo-nero istituzionale fortissimo — tra i brand più riconoscibili in Germania. Il rosso del pulsante "SOS Nothilfe" crea un contrasto cromatico deliberato e funzionale sul giallo istituzionale. Layout editoriale: griglia modulare, fotografie di qualità (auto, natura, viaggi, lifestyle), font sans-serif pulito. Nessuna immagine che rappresenti il momento di stress dell'emergenza. Il wizard "Pannenhilfe Online" rompe lo stile editoriale: è un'UI task-focused minimale, centrata, senza elementi decorativi.

**3. Schemi di layout**
Tre livelli di UI con logiche diverse: (1) homepage = magazine a griglia editoriale, con sezioni Produkte, Videos, Rund ums Fahrzeug, Gesundheit, Motorrad — non orientata al servizio; (2) pagina Pannenhilfe = hub informativo a blocchi verticali, organizzati per funzione (contatti → app → cosa fare → prestazioni → Gelbe Engel → statistiche); (3) Pannenhilfe Online = wizard centrato a 4 step con geolocalizzazione immediata, UI completamente separata dallo stile editoriale. La coerenza visiva è garantita dal branding, non dallo schema di layout.

**4. Approccio comunicativo**
Autorevolezza istituzionale su tutto. "Der ADAC" — terza persona, tono da istituzione che non ha bisogno di convincere. La fiducia è costruita con scala e storia: Pannenhilfebilanz (report annuale pubblico su ogni intervento eseguito), Pannenstatistik (quale auto si rompe di più, su 100+ marche). Nessun copy che riconosca la condizione emotiva di chi è in panne. Il messaggio implicito è: "siamo qui da sempre, siamo ovunque, i numeri parlano da soli."

**5. Elementi di design distintivi**
- **"SOS Nothilfe" rosso in header** — persistente su ogni pagina, contrasto cromatico intenzionale rispetto al giallo dominante: il segnale d'urgenza è separato dal brand
- **Wizard a 4 step con geolocalizzazione immediata** — primo input è "condividi posizione", non "inserisci targa": riduce la friction al minimo nella segnalazione panne
- **Ecosistema di 4 app distinte** (Pannenhilfe App, Medical App, Drive App, Trips App) — ogni caso d'uso ha la sua app, non una sola superapp
- **"Gelbe Engel"** come brand dei soccorritori — con propria sezione, storia, fuhrpark, dati; non un dettaglio operativo ma un'identità narrativa
- **Pannenhilfebilanz** — report annuale con tutti i dati di intervento, pubblicato come documento istituzionale: trasparenza sistemica, non marketing

**6. Punti di forza**
- Brand giallo-nero riconoscibilissimo, fortissimo equity in Germania
- Flusso digitale d'emergenza maturo: wizard a 4 step, geolocalizzazione immediata, UI task-first segregata dallo stile editoriale
- Trasparenza sistemica tramite dati pubblici e certificabili (Pannenhilfebilanz, Pannenstatistik)
- Ecosistema di app differenziate per caso d'uso, con Pannenhilfe App dedicata all'emergenza
- SOS sempre visibile con contrasto cromatico funzionale — si distingue visivamente da tutto il resto

**7. Punti di debolezza**
- Homepage interamente editoriale: chi è in panne trova solo il bottone "SOS Nothilfe" nell'header; nessun percorso d'urgenza nell'area hero o nei blocchi principali
- Assenza totale di area B2B/fleet nella navigazione — ADAC è strutturalmente un club consumer. La pagina "Geschäftspartner" riguarda i fornitori interni (procurement, compliance), non clienti aziendali
- Complessità estrema: 7 voci di navigazione primaria, 4 app, centinaia di sezioni — può disorientare chi cerca solo il soccorso stradale
- La membership individuale non ha un equivalente aziendale: il B2B non è una proposta commerciale del club

**Risposte alle domande del Cluster 1**

**1. Come gestiscono la gerarchia "numero di emergenza vs contenuti informativi" in homepage?**
Modello editoriale con emergenza separata nel header: il "SOS Nothilfe" è in header persistente (rosso su giallo, cromaticamente distinto), ma la homepage è interamente occupata da contenuto editoriale. Nessuna CTA d'emergenza nell'area hero o nei moduli principali. La logica è quella di un portale media: chi è in panne deve usare l'header o conoscere già il percorso. *(Osservazione diretta.)*

**2. Su quali temi puntano principalmente (empatia, efficienza, storia, social proof)?**
Autorevolezza istituzionale + dati di sistema. ADAC costruisce fiducia con scala e storia ("Gelbe Engel", club fondato nel 1903), con dati pubblici annuali (Pannenhilfebilanz, Pannenstatistik), e con la sola presenza come il più grande club d'Europa. Nessun copy empatico sull'emergenza o sulla condizione dell'utente in difficoltà. Il tono è quello di un'istituzione che non ha bisogno di convincere — "i numeri parlano da soli". *(Osservazione diretta.)*

**3. Come gestiscono la navigazione per tipo di utente (privati vs aziende)?**
Non la gestiscono: nessuna sezione B2B/fleet nella navigazione principale. La pagina "Infos für Geschäftspartner" (sepolta nel footer sotto "Der ADAC") è dedicata a fornitori e partner commerciali di ADAC (procurement, compliance, einkaufsportal), non a clienti aziendali con flotte. ADAC è strutturalmente un club consumer — la membership è individuale. Caso diametralmente opposto ad AA UK, che ha una voce "Business" nel nav principale. *(Osservazione diretta.)*

**4. Quali canali di contatto offrono oltre al numero verde e come li gerarchizzano?**
Nella pagina Pannenhilfe: due numeri differenziati (089 20 20 40 00 per Germania; +49 89 22 22 22 per estero) + ADAC Pannenhilfe App prominente con descrizione esplicita ("Sparen Sie Zeit und Nerven im Pannenfall") + wizard "Panne online melden" a 4 step. Nel header: "SOS Nothilfe" porta alla pagina di aiuto. Gerarchia implicita: app → wizard online → telefono. "Mein ADAC" è per gestione membership, non per emergenze. *(Osservazione diretta.)*

#### Europ Assistance (IT) — ✅ Completato
_Screenshot caricati in Figma (Tema 1, 195:137): Homepage (209:2), Mobilità (208:2), Auto Noproblem (210:2), Soccorso Stradale On Demand (211:2)._

**1. Identità e posizionamento**
Europ Assistance non è un servizio di soccorso stradale: è una compagnia assicurativa multi-prodotto (viaggi, casa, salute, mobilità) con parent group Generali. Il soccorso stradale è uno dei quattro comparti, non il core. Il brand è in transizione verso "Redion" (notice di rebrand presente su tutte le pagine). Il tagline "you live, we care" ambisce a un posizionamento empatico-umano, ma l'esecuzione è quella di una grande corporate assicurativa. Il soccorso stradale operativo è gestito da un'entità giuridica separata — Europ Assistance VAI S.p.A. — con numero verde distinto (803 803 vs 800.44.33.22) e presenza sul sito come nota a piè di pagina, non come proposta integrata.

**2. Stile visivo**
Blu istituzionale e rosso corallo come colori dominanti — coerente con l'identità Generali. Il layout è pulito e moderno, con fotografie stock lifestyle (viaggi, coppie, famiglie). Il sito consumer mette il viaggio visivamente al centro: l'hero è un configuratore viaggi con immagini di destinazioni. La mobilità ha un'estetica più funzionale (foto di auto, strade) ma non rompe lo stile del sito. Il "Soccorso Stradale On Demand" (sodauto.europassistance.it) ha una palette gialla/blu più energica, distinta dal sito principale.

**3. Schemi di layout**
Due livelli distinti: (1) sito consumer (europassistance.it) = portale assicurativo a griglia, con configuratore in hero e tab per categoria prodotto; (2) pagine prodotto mobilità = layout informativo verticale con numero verde in evidenza, tre livelli di copertura, FAQ, link al PDF condizioni; (3) sodauto.europassistance.it = landing page dedicata con flow a 3 step e social proof numerico. Non c'è coerenza strutturale tra le tre esperienze: l'utente che passa dall'homepage alla pagina prodotto al sito SOD incontra tre design system distinti.

**4. Approccio comunicativo**
Social proof numerico massiccio: Trustpilot 4.4/5 in homepage con carosello di recensioni live, "10+ MLN di clienti assistiti", "301 MLN di chiamate", "200 paesi coperti". La fiducia è costruita su scala e dati quantitativi. Sul piano empatico, il "you live, we care" rimane uno slogan — nessun copy che racconti il momento dell'emergenza o la condizione di chi è in panne. L'approccio è quello di una multinazionale assicurativa: solidità e numeri, non empatia situazionale.

**5. Elementi di design distintivi**
- **Configuratore viaggi in hero** con tab per categoria (Viaggi / Casa / Salute / Mobilità) — la mobilità è accessibile ma non primaria
- **Trustpilot widget live in homepage** con recensioni scorribili — il rating è integrato nel layout, non una badge in footer
- **"Soccorso Stradale On Demand" come prodotto separato** (sodauto.europassistance.it, 99€ una tantum) — primo operatore italiano a offrire soccorso pay-per-use senza abbonamento, con preventivo online e tracking via email
- **Tre livelli di polizza** (Base / Completa / Top) con distinzione chiara di coperture nella pagina prodotto
- **Due numeri verdi distinti**: 800.44.33.22 per le polizze (EA Italia), 803 803 per i servizi operativi (EA VAI) — frammentazione interna visibile anche all'utente
- **Rebrand in corso** a "Redion": notice in ogni pagina; il cambio di marca introduce incertezza durante la fase di transizione

**6. Punti di forza**
- Trustpilot 4.4/5 con recensioni live visibili in homepage: il trust è documentato e verificabile in real-time
- "Soccorso Stradale On Demand" a 99€: unico in Italia come offerta pay-per-use con preventivo e tracking digitale — abbassa la barriera d'ingresso per chi non vuole un abbonamento annuale
- Scala internazionale comunicata con dati concreti (200 paesi, rete certificata, ISO 9001)
- Tre livelli di copertura chiari nella pagina prodotto con descrizione delle prestazioni incluse

**7. Punti di debolezza**
- Nessun numero di emergenza in homepage: chi è in panne deve navigare fino alla sezione Mobilità per trovare il 800.44.33.22 — percorso d'urgenza assente nel flusso principale
- Frammentazione brand/operativa: due numeri verdi, due entità giuridiche (EA Italia + EA VAI), due siti distinti (europassistance.it + sodauto.europassistance.it) — l'utente non capisce con chi stia parlando
- Area B2B assente nel sito consumer: nessuna sezione flotte/aziende; il B2B è delegato a EA VAI con canali separati non linkati dal sito principale
- Condizioni del prodotto non consultabili online: le pagine prodotto linkano a un PDF ("Set informativo auto noproblem") invece di presentare incluso/escluso in HTML scansionabile
- Rebrand a "Redion" in corso: la coesistenza dei due brand sulle stesse pagine genera confusione identitaria

**Risposte alle domande del Cluster 1**

**1. Come gestiscono la gerarchia "numero di emergenza vs contenuti informativi" in homepage?**
Il numero di emergenza non è in homepage. L'hero è un configuratore polizze viaggi; la mobilità è il quarto dei quattro tab. Il 800.44.33.22 appare solo nelle pagine prodotto Mobilità — non nell'header persistente, non nella navigazione principale. Chi è in panne e atterra sull'homepage non trova alcun percorso diretto. Modello opposto ad AA UK e parzialmente a ADAC: qui l'emergenza è subordinata alla logica commerciale del portale assicurativo. *(Osservazione diretta.)*

**2. Su quali temi puntano principalmente (empatia, efficienza, storia, social proof)?**
Social proof numerico dominante: Trustpilot 4.4/5 con recensioni live, "10+ MLN clienti", "301 MLN chiamate", "200 paesi". Il posizionamento empatico esiste come slogan ("you live, we care") ma non si traduce in copy che riconosce la situazione di chi ha bisogno. La storia del brand (50+ anni) è citata come dato, non come narrazione. L'efficienza operativa è comunicata nel sito SOD (preventivo immediato, tempi medi 25-45 minuti), non nel sito principale. *(Osservazione diretta.)*

**3. Come gestiscono la navigazione per tipo di utente (privati vs aziende)?**
Non esiste una sezione B2B nel sito consumer. L'intera navigazione — Assicurazioni (Viaggi / Casa / Salute / Mobilità) e Servizi — è orientata ai privati. Il B2B opera sotto Europ Assistance VAI S.p.A., entità separata menzionata solo in footer e nelle note legali delle pagine Mobilità. Nessun link "Sei un'azienda?" o switch utente nel nav principale. Caso estremo di separazione: il cliente business deve sapere già dell'esistenza di EA VAI per accedere all'offerta fleet. *(Osservazione diretta.)*

**4. Quali canali di contatto offrono oltre al numero verde e come li gerarchizzano?**
Tre canali: (1) numero verde 800.44.33.22 — nelle pagine prodotto, dalle 09:00 alle 19:00 (non 24/7); (2) "Soccorso Stradale On Demand" (sodauto.europassistance.it) — canale digitale pay-per-use con preventivo, acquisto e tracking online, senza abbonamento; (3) form "VUOI ESSERE RICONTATTATO?" nelle pagine prodotto — callback request. Nessuna app mobile nominata nella navigazione principale. Il canale digitale SOD è la vera innovazione, ma è segregato su un sottodominio separato senza rimandi evidenti dall'homepage. *(Osservazione diretta.)*

#### AAA (US) — ✅ Completato

**Sito analizzato:** ace.aaa.com (AAA Northern New England — club regionale per Maine, New Hampshire, Vermont; zip 04016)
**Screenshot Figma:** non inseriti
**Data analisi:** 2026-06-29

---

**Identità e posizionamento**

AAA Northern New England (ACE) è un club regionale affiliato alla federazione AAA nazionale. Come per tutti i club AAA, il posizionamento non è di puro soccorso stradale ma di "membership brand" che integra roadside assistance, assicurazioni, viaggi e sconti consumer. Rispetto ad altri club AAA (es. ACG/Illinois), ACE ha compiuto una scelta progettuale netta: **nessun numero di telefono nella navigazione principale** — l'accesso all'emergenza è interamente digitale. Il sito copre Maine, New Hampshire e Vermont, con struttura visiva, navigation e contenuti identici al template AAA nazionale. *(Osservazione diretta + footer: "AAA Northern New England is a member club affiliated with the American Automobile Association (AAA) national federation".)*

---

**Stile visivo**

Navy/bianco con CTA primaria rossa — palette coerente con il brand AAA nazionale. Logo: tripla A bianca su sfondo navy, versione monocromatica invertita rispetto ad ACG. Header full-width navy che ospita in primo piano search, "Join AAA" (outline bianco), "Contact us" (outline bianco) e "Get Roadside Assistance" (bottone rosso pieno con icona carrozzeria) — la gerarchia cromatica è immediatamente leggibile: rosso = emergenza, bianco outline = azioni secondarie. Navigation secondaria su sfondo bianco con 6 dropdown. Immagini realistiche (tow truck, membro assistito). Membership page: tre card con badge testuali "Best value" (rosso) su Plus e "Most exclusive" (viola) su Premier — invece del color coding dei CTA usato da ACG. *(Osservazione diretta.)*

---

**Schemi di layout**

Header a doppio livello: (1) top bar navy con CTA operative; (2) nav bar bianca con dropdown per categorie. Questa separazione è la scelta più significativa del layout: le azioni urgenti (emergenza, contatto, iscrizione) vivono nello strato superiore a larghezza piena, mentre la navigazione informativa è nello strato inferiore. Homepage: hero con promo membership + card grid assicurazioni affiancata. Roadside page: card overlay su immagine full-width con due CTA ("Request Roadside Assistance" blu + "Become a member" outline). Floating button rosso in basso a destra su tutte le pagine — replica persistente del bottone header anche dopo lo scroll. Membership page: tre card affiancate con prezzi in grandi dimensioni ($25 / $56 / $85) e lista benefit per differenza tra tier. *(Osservazione diretta.)*

---

**Approccio comunicativo**

Framing da club, non da prodotto: "With our legendary 24-hour Roadside Assistance" — il termine "legendary" evoca heritage senza citare anni o dati. La roadside page introduce il beneficio principale con un claim operativo: "On average, requests take less than 4 minutes to make" — metrica concreta e rassicurante. Zero social proof numerico in homepage. Pricing esplicito e frontale sulla membership page: Classic $25 / Plus $56 / Premier $85 per anno (prezzi first-year). La struttura "Choose a plan" è complementata da un link "Compare benefit levels" — trasparenza comparativa. *(Osservazione diretta.)*

---

**Elementi di design distintivi**

1. **"Get Roadside Assistance" come CTA rossa in header** — non un numero di telefono, non un link testuale: un bottone rosso pieno con icona vettura, visibile su ogni pagina come punto di ingresso primario all'emergenza. Unicum nel benchmark: nessun altro player ha rimosso il telefono dall'header a favore di un bottone digitale.
2. **Virtual assistant 24/7 per roadside** — "Chat with AAA's virtual assistant 24/7 and get the roadside service you need without waiting on the phone. On average, requests take less than 4 minutes to make." — chatbot come canale operativo primario, non di supporto.
3. **CTA per-servizio sulla roadside page** — 6 bottoni separati (Request a tow / Request battery service / Request tire service / Request lockout service / Request fuel delivery / Request breakdown service) — riduzione drastica del carico cognitivo: l'utente non deve descrivere il problema, lo seleziona.
4. **Floating button rosso persistente** — replica del bottone emergenza sempre visibile in basso a destra dopo lo scroll — doppia presenza (header + float) come ridondanza intenzionale per l'accesso all'emergenza.
5. **"Group membership"** nella membership page — "Boost the value of your organization's benefits package" — accenno di B2B come benefit collettivo, non come area dedicata.

---

**Punti di forza (rilevanti per ACI)**

- **CTA emergenza sempre visibile** in due punti simultanei (header + floating button) senza numero telefonico
- **Chatbot operativo con SLA dichiarato** ("avg 4 min") — costruisce fiducia sul canale digitale con dato misurabile
- **CTA per-servizio** — modello che elimina la frizione "devo spiegare cosa mi è successo"
- **Prezzi espliciti e trasparenti** con differenziazione benefit per tier — modello scalabile per membership multi-livello
- **Separazione strutturale header** — azioni urgenti (top bar) vs navigazione informativa (nav bar) — architettura coerente

---

**Punti di debolezza (anti-pattern per ACI)**

- **Nessun numero di telefono visibile** — scelta radicale che funziona per un mercato digitalmente maturo come gli USA, ma potrebbe escludere fasce d'utenza meno digitali (anziani, utenti in stress che preferiscono la voce)
- **B2B assente come area strutturata**: "Group membership" è un accenno in fondo alla membership page, non un percorso separato con contenuti dedicati
- **Struttura federata opaca**: il sito è riconoscibilmente ACE/Northern New England solo nel footer — l'utente che arriva su un altro club AAA trova un sito quasi identico ma con prezzi e contenuti locali diversi
- **Homepage non ha urgency esplicita nel body**: il bottone rosso è in header ma il body hero è occupato dalla promo membership; chi scorre la pagina perde il riferimento emergenza fino al floating button

---

**Risposte alle domande del Cluster 1**

**1. Come viene gestita la gerarchia tra contenuto informativo e contenuto di emergenza nella homepage?**
ACE risolve il problema con architettura a due strati: top bar navy con "Get Roadside Assistance" (bottone rosso pieno) sempre visibile al caricamento, separato fisicamente dalla nav informativa sottostante. Il body della homepage non contiene contenuto di emergenza — è occupato da promo membership e card insurance. La gerarchia è quindi strutturale (layer), non contenutistica (hero). Soluzione elegante che non sacrifica la conversione commerciale all'urgenza, ma mantiene l'accesso all'emergenza permanentemente above the fold. *(Osservazione diretta.)*

**2. Quali leve comunicative usano per trasmettere affidabilità e competenza tecnica?**
Due leve principali: (1) **legacy implicita** — "legendary 24-hour Roadside Assistance" senza numeri, contando sul brand recognition nazionale di AAA; (2) **metrica operativa dichiarata** — "On average, requests take less than 4 minutes to make" — dato concreto che trasforma un canale digitale (potenzialmente percepito come lento) in una promessa di velocità superiore al telefono. Assenza totale di social proof esterno (Trustpilot, Google Reviews) — massima distanza dal modello AutoAssist/Europ Assistance. *(Osservazione diretta.)*

**3. Come differenziano il percorso per privati rispetto a quello per aziende/flotte?**
Non esiste percorso B2B dedicato. "Group membership" nella pagina membership è l'unico accenno a un uso collettivo del servizio — "Boost the value of your organization's benefits package" — senza pagina o sezione separata. Nel footer compare "Become a participating business" (per esercizi commerciali che vogliono aderire al programma sconti AAA come partner, non come clienti fleet). Stesso anti-pattern strutturale di Europ Assistance e ACG, ma con "Group membership" come piccolo passo verso il riconoscimento dell'utente business. *(Osservazione diretta.)*

**4. Quali canali di contatto offrono oltre al numero verde e come li gerarchizzano?**
ACE è il caso più estremo del benchmark: **nessun numero di telefono visibile nella navigazione principale**. I canali identificati sono: (1) "Get Roadside Assistance" (bottone header + floating) → virtual assistant chatbot 24/7, avg 4 min; (2) 6 CTA per-servizio sulla roadside page → flusso digitale guidato per tipo di problema; (3) AAA Mobile App — nominata con QR code e SMS shortcode (APP10 → 86792); (4) "Contact us" in header → pagina contatti generale; (5) chatbot "I'm here to help" (widget in basso a destra, distinto dal virtual assistant roadside). Gerarchia implicita: digitale (chatbot/app) prima, telefono non comunicato. Scelta coerente con mercato USA digitalmente maturo ma distante dal contesto ACI. *(Osservazione diretta.)*

---

### Cluster 2

#### Glovo (IT/cross-settore) — ✅ Completato

**Sito analizzato:** glovoapp.com/it/it (consumer web) + Play Store listing IT
**Screenshot Figma:** non inseriti
**Data analisi:** 2026-06-29

---

**1. Identità e posizionamento rispetto al Cluster 2**

Glovo è un'app di delivery on-demand (cibo, spesa, negozi, farmacia) attiva in 25 paesi con 80+ milioni di download e 240.000+ partner. Rating Play Store: 4,6/5 su 2,09 milioni di recensioni. Nel contesto del Cluster 2, Glovo è analizzato come **reference cross-settore per il design del tracking real-time**: non gestisce emergenze di mobilità, ma risolve il problema strutturalmente identico di comunicare "dov'è il tuo operatore / quanto manca / cosa sta succedendo" durante un intervento attivo. Il modello è app-first in modo radicale: il sito web è quasi interamente un vetrina per l'app, la maggior parte delle pagine informative è su sottodomini separati o restituisce 404. *(Osservazione diretta.)*

---

**2. Stile visivo**

Rosa Glovo (brand color) + bianco su sfondi chiari. Layout homepage a una colonna con campo indirizzo come unico focus above the fold: zero distrazioni, zero contenuto informativo, una sola azione possibile. Categorie orizzontali con icone monocromatiche su sfondo colorato pastello. La schermata di tracking nell'app (da note di aggiornamento Play Store: "abbiamo modernizzato la schermata dove puoi monitorare il tuo ordine e l'orario di arrivo previsto") è l'unica schermata progettata per trattenere l'attenzione durante l'attesa — tutto il resto è transazionale. *(Osservazione diretta web + Play Store.)*

---

**3. Flusso d'azione urgente — step e friction**

Web: indirizzo → categoria → ristorante/negozio → selezione prodotti → carrello → checkout → pagamento → conferma ordine. Circa 6-7 step ma senza frizioni bloccanti: ogni step è immediato, no form, no campi opzionali, pagamento salvato. App: ulteriormente ridotto a 3-4 tap con indirizzo e metodo di pagamento memorizzati. Nessuna CTA di supporto visibile nel flusso pre-ordine — la friction è progettata sul "non fermarti mai", non sul "hai bisogno di aiuto?". Il canale di supporto (chat) è accessibile solo dall'interno dell'ordine attivo, non dall'homepage. *(Osservazione diretta.)*

---

**4. Tracking real-time e comunicazione dell'attesa**

Il tracking post-ordine è il nucleo del prodotto Glovo. Schermata dedicata con: (1) **mappa live** con posizione del corriere in tempo reale (punto che si muove); (2) **ETA dinamica** in minuti, aggiornata in tempo reale man mano che il corriere si avvicina; (3) **stato progressivo** con 6 fasi — "Ordine confermato → In preparazione → Corriere assegnato → Corriere al ritiro → In consegna → Consegnato"; (4) **push notification** automatica per ogni transizione di stato. Ogni elemento è correlato: il punto sulla mappa + l'ETA + lo stato verbale raccontano la stessa informazione da tre angolazioni diverse, eliminando l'incertezza su "cosa sta succedendo". La nota di aggiornamento recente ("abbiamo modernizzato la schermata di monitoraggio") conferma che il tracking screen è considerato il componente più critico del prodotto. *(Play Store, versione aggiornata al 29/06/2026.)*

---

**5. App come canale primario — non alternativo**

Su Glovo l'app non è un'alternativa al telefono: è l'unico canale. Il sito dice esplicitamente "Ordina tutto ciò che vuoi e seguilo in tempo reale **sull'app Glovo**." Il tracking completo (mappa, ETA dinamica, chat corriere) non è disponibile sul web — è esclusivamente in-app. Nessun numero di telefono da nessuna parte. L'unico canale di supporto umano è la **chat in-app** accessibile dall'ordine attivo. Promozione app: link iOS/Android in hero, footer, e CTA "Scarica l'app" con adjust link tracciato. *(Osservazione diretta.)*

---

**6. Fase post-intervento**

Immediatamente dopo la consegna: **rating a 5 stelle** per cibo, corriere e packaging — prompt automatico, non può essere ignorato senza interazione. Segnalazione problemi in-app (merce mancante, articolo sbagliato) con flusso di rimborso integrato. Storico ordini accessibile in-app. Secondo le recensioni più recenti del Play Store, la fase post-intervento è il punto debole sistemico: il supporto non risolve sempre i problemi segnalati, i ticket vengono chiusi senza risposta. Il gap tra promessa (rimborso automatico) ed esperienza reale (evasività del supporto) è il principale driver di recensioni negative. *(Play Store recensioni, osservazione diretta.)*

---

**7. Punti di forza per il Cluster 2**

- Mappa live + ETA dinamica + stati progressivi + push: tutti e 4 i segnali dell'attesa attivi simultaneamente — nessuna incertezza residua
- App-only coerente: nessun canale degradato, nessun "chiama per avere informazioni" come fallback
- Friction pre-ordine minima: 1 input (indirizzo) per avviare, dati salvati per gli step successivi
- Rating immediato post-consegna: feedback loop chiuso nello stesso contesto dell'esperienza, non via email

---

**8. Punti di debolezza per il Cluster 2**

- Nessun canale vocale o umano immediato: se il sistema fa un errore (ordine sbagliato, corriere non trovabile), l'utente è bloccato nella chat — nessuna via d'uscita per i casi critici
- Web completamente degradato: chi non ha l'app non può seguire l'ordine in tempo reale
- Supporto post-intervento inaffidabile: il gap tra promessa di rimborso e risoluzione effettiva produce recensioni sistematicamente negative — la fiducia nel sistema si accumula ma può erodere rapidamente

---

**Risposte alle domande del Cluster 2**

**1. Come progettano l'azione urgente: friction, numero di step, accesso al contatto.**
Flusso pre-ordine in 6-7 step su web, 3-4 tap su app, con friction quasi nulla (indirizzo + pagamento salvati). Nessuna CTA di supporto visibile nel flusso pre-ordine: l'accesso al contatto (chat) è disponibile solo dall'ordine attivo, non dall'homepage. Il design sceglie velocità sull'autodeterminazione: l'utente non cerca aiuto, procede. *(Osservazione diretta.)*

**2. Come comunicano l'attesa e lo stato dell'intervento in tempo reale?**
Quattro segnali simultanei: mappa live (posizione corriere), ETA dinamica (minuti aggiornati), stato verbale progressivo (6 fasi), push notification per ogni transizione. La combinazione elimina il silenzio informativo: in ogni momento l'utente sa dove si trova l'operatore, cosa sta facendo, e quanto manca. È il modello di riferimento per la comunicazione dell'attesa — applicabile direttamente al contesto soccorso stradale. *(Play Store + osservazione diretta.)*

**3. Come promuovono l'app come canale alternativo al telefono?**
Non è alternativo: è esclusivo. L'app è l'unica modalità per il tracking completo, il supporto e la gestione dell'ordine. Il sito web dice esplicitamente "seguilo in tempo reale sull'app". La promozione app è presente in ogni touchpoint (homepage hero, footer, link adjust tracciati) ma non è necessaria una "promozione" — senza app non si ottiene il servizio completo. *(Osservazione diretta.)*

**4. Come trattano la fase post-intervento?**
Rating immediato post-consegna (non differibile), segnalazione problemi in-app con flusso rimborso integrato, storico ordini. Il modello è corretto nella struttura (feedback loop chiuso, rimborso in-app) ma l'esecuzione del supporto è il punto critico — le recensioni negative convergono sistematicamente sulla inaffidabilità della risoluzione dei problemi post-consegna. Il sistema funziona quando tutto va bene; non quando serve davvero. *(Play Store recensioni.)*

#### Uber (IT) — ✅ Completato

**Fonti:** uber.com/it/it/ · uber.com/it/it/ride/ · uber.com/it/it/safety/ · uber.com/us/en/ride/safety/ · Play Store (com.ubercab, IT)

**Sintesi:** Uber è il gold standard del tracking per un motivo preciso: ha integrato la safety dentro il layer del tracking. Non solo "dove sei" ma "stai bene?". Il sito italiano è un thin funnel quasi privo di contenuto; tutta l'esperienza vive nell'app, che non è un canale alternativo ma il prodotto.

**Dati chiave app:** 4,8/5 · 19M recensioni · 1B+ download · Ultimo aggiornamento: giugno 2026

**Pattern differenzianti:**
- **RideCheck** — il sistema (non l'utente) rileva proattivamente anomalie nel percorso o possibili incidenti tramite sensori + GPS e interviene; nessun competitor di categoria ha nulla di simile
- **Safety Toolkit** centralizza tutte le funzioni di sicurezza in un unico punto (scudo blu) raggiungibile in ogni momento della corsa
- **Share My Trip** — condivisione real-time con contatti fidati, inclusi dettagli veicolo e targa; funziona anche per chi riceve il link senza avere l'app
- **Emergency Button in-app** — la chiamata al 112/911 avviene dall'app che mostra automaticamente posizione + dati veicolo + targa, eliminando lo step critico di dover comunicare dove sei

**Punti critici:**
- Nessuna feature di tracking accessibile da web senza app; chi non ha l'app non ottiene il servizio completo
- Help center non accessibile via browser nella versione IT (redirect a 404)
- Le recensioni negative convergono su malfunzionamenti dell'app che bloccano la prenotazione con addebito immediato — il sistema funziona bene quando funziona; i fallimenti sono costosi

---

**Risposte alle domande del Cluster 2**

**1. Come progettano l'azione urgente: friction, numero di step, accesso al contatto.**
Flusso standard: 2 input (partenza + destinazione) → selezione tipo corsa → pagamento → conferma. Con account e dati salvati: 2-3 tap. Il punto critico è l'accesso di emergenza in-corsa: Safety Toolkit sempre visibile (icona scudo) → Emergency Button → chiamata con posizione + dati veicolo pre-compilati automaticamente. Lo step più costoso in un'emergenza (comunicare dove sei) è eliminato by design. Nessun numero di telefono comunicato sul sito. *(Osservazione diretta + pagina safety US.)*

**2. Come comunicano l'attesa e lo stato dell'intervento in tempo reale?**
Tre layer sovrapposti: (a) mappa live con posizione autista dall'accettazione alla destinazione + ETA aggiornata; (b) push notification per ogni cambio di stato (confermato → in avvicinamento → arrivato → corsa iniziata → terminata); (c) RideCheck — monitoraggio passivo e proattivo: se il percorso devia o i sensori rilevano un possibile incidente, il sistema notifica l'utente e offre risorse di aiuto senza che debba fare nulla. È il pattern più avanzato del benchmark: il sistema si preoccupa per l'utente, non aspetta che l'utente si preoccupi. *(Play Store + pagina safety US.)*

**3. Come promuovono l'app come canale alternativo al telefono?**
Non è alternativo: è esclusivo. Il sito IT è una brochure con due campi di input — tutto rimanda a m.uber.com/looking o all'app. QR code per download prominenti in homepage. Le safety feature (RideCheck, Emergency Button, Share My Trip) sono comunicate come ragioni esplicite per usare l'app, non come "bonus". L'app non compete con il telefono perché non esiste un canale telefonico Uber — la scelta è app o niente. *(Osservazione diretta.)*

**4. Come trattano la fase post-intervento?**
Rating immediato post-corsa (2-way: passeggero valuta autista e viceversa) + possibilità mancia in-app. On-Trip Reporting: segnalazione discreta durante la corsa, non solo a fine. 24/7 incident support specializzato. Emergency Contacts: se dopo un incidente Uber non riesce a contattare l'utente, contatta i suoi contatti di emergenza registrati. Audio Recording in-app per situazioni scomode. Il ciclo è chiuso: dalla corsa alla segnalazione alla risoluzione, tutto in-app. *(Play Store + pagina safety US.)*

#### ADAC (DE) — ✅ Completato

**Fonti:** adac.de/services/pannenhilfe/ · adac.de/services/pannenhilfe/pannenhilfe-online/ · adac.de/services/apps/pannenhilfe/ · adac.de/hilfe-vom-adac/ · Play Store (de.adac.mobile.pannenhilfe, IT)

**Sintesi:** ADAC è il riferimento di categoria più diretto per ACI Global — stessa tipologia di servizio, scala maggiore. Ha implementato un live tracking dell'operatore e un web form a 4 step che rendono la richiesta di soccorso fruibile anche senza telefonata. Il tracking si attiva "poco prima dell'arrivo", non dall'accettazione — gap rispetto a Uber ma comunque presente. Il sito posiziona esplicitamente l'app come alternativa al telefono.

**Dati app:** 4,7/5 · 76K recensioni · 1M+ download · Ultimo aggiornamento: ottobre 2025

**Pattern differenzianti:**
- **"Nothilfe" SOS rosso persistente** in ogni pagina del sito — bottone di accesso emergenza sempre visibile in header, indipendentemente dalla sezione
- **Web form a 4 step** come canale intermedio: non richiede l'app, non è solo un numero — Step 1 = mappa con geolocalizzazione automatica ("Share Location") o ricerca manuale con nota "se inserito manualmente va verificato prima"
- **Live tracking dell'operatore** — posizione in mappa "poco prima dell'arrivo"; non dall'assegnazione ma presente. Nota aggiornamento recente: "Live-Tracking weiter optimiert für eine noch präzisere und stabilere Anzeige"
- **Dati pre-sincronizzati:** soci con profilo "Mein ADAC" hanno veicolo, dati e membership già caricati — friction minima all'atto della segnalazione

**Punti critici:**
- Live tracking attivato solo nell'ultimo tratto ("poco prima dell'arrivo"), non dall'accettazione — finestra di incertezza più lunga rispetto a Uber
- Il servizio gratuito è riservato ai soci — per i non-soci è solo un canale di segnalazione
- Nessuna comunicazione visibile sul post-intervento (feedback, rating) nel flusso pubblico

---

**Risposte alle domande del Cluster 2**

**1. Come progettano l'azione urgente: friction, numero di step, accesso al contatto.**
Tre canali in parallelo: (a) app con GPS automatico + profilo pre-compilato → segnalazione in pochi tap; (b) web form 4 step con mappa e geolocalizzazione — accessibile da browser senza app; (c) numero telefonico (089 20 20 40 00) sempre visibile. Il sito posiziona esplicitamente l'app come "segnalazione senza telefonata". La "Nothilfe" con badge SOS rosso è persistente in ogni pagina — non scompare navigando nei contenuti informativi. Per i soci con profilo precompilato la friction è la più bassa di categoria. *(Osservazione diretta + pagina app + web form.)*

**2. Come comunicano l'attesa e lo stato dell'intervento in tempo reale?**
Due layer: (a) push notification con aggiornamenti di stato post-conferma; (b) ETA stimata mostrata nell'app dopo l'accettazione; (c) live tracking della posizione dell'operatore attivato "poco prima dell'arrivo". Il tracking non copre tutta la durata dell'attesa — si attiva nell'ultimo tratto, non dall'assegnazione. È un tracking parziale ma dichiarato e in miglioramento attivo. Nessuna mappa live dal momento zero come Uber. *(Play Store descrizione + note aggiornamento.)*

**3. Come promuovono l'app come canale alternativo al telefono?**
La promozione è esplicita e di prodotto: la pagina app usa "semplice segnalazione senza telefonata" come headline benefit, non come feature secondaria. La sezione "ADAC Apps" è presente nel footer di ogni pagina. Ma l'app non è l'unico canale digitale — il web form è un secondo canale alternativo al telefono, utile per chi non vuole installare l'app. Questa struttura multi-canale (telefono + web form + app) riduce la dipendenza dall'app e riduce anche il costo di adozione percepito. *(Osservazione diretta.)*

**4. Come trattano la fase post-intervento?**
Non è comunicata pubblicamente nel flusso di segnalazione. L'"Auftragsstorno" (cancellazione ordine) è disponibile in-app. La "Schadenmeldung" (denuncia danno) consente upload di fatture per rimborso. Il team risponde ai commenti negativi sul Play Store invitando a contattare QM@adac.de con numero socio e data — gestione reputazione strutturata. Nessun sistema di rating pubblico visibile per il servizio d'intervento. *(Play Store + pagina Nothilfe.)*

#### AA (UK) — ✅ Completato

**Fonti:** theaa.com/breakdown-cover/ · theaa.com/breakdown-cover/broken-down/safety-advice · theaa.com/apps · Play Store (com.theaa.android.theaa, GB)

**Sintesi:** AA (UK) è il competitor diretto con il flusso digitale più maturo della categoria: tracking disponibile sia in-app che online (unico nel benchmark), claim esplicito sulla velocità dell'app vs telefono, safety screen prima del report. Il canale telefonico rimane presente ma non è il percorso promosso. Il punto debole strutturale è la stabilità dell'app in condizioni di stress — esattamente il momento in cui il servizio deve funzionare.

**Dati app:** 4,7/5 · 4,6M download · Ultimo aggiornamento: giugno 2026 (v11.18.0) · Nota recente: "improvements to app stability and fixed an issue that could occasionally affect app loading"

**Pattern differenzianti:**
- **Safety advice screen prima del report** — step dedicato con 3 istruzioni di sicurezza (sposta il veicolo, luci di emergenza, esci dal veicolo) prima del form di segnalazione — unico nel benchmark; scelta che antepone la sicurezza dell'utente alla velocità di reporting
- **Tracking via app e online** — "you can track our progress in the app or online" — tracking non app-exclusive: abbassa la barriera vs Glovo/Uber dove la mappa live richiede l'app
- **Geolocalizzazione automatica** — "No need to give us directions – we'll come straight to your phone's location" — la posizione è condivisa dal telefono, nessun indirizzo da digitare in emergenza
- **"Twice as fast as calling"** — claim esplicito con ragione tecnica (GPS location sharing), non solo promessa generica

**Punti critici:**
- Tracking non disponibile dal momento zero: da recensione utente "Was told to start tracking after 15 minutes" — finestra di silenzio simile ad ADAC, opposta a Uber
- Instabilità app in aggiornamenti recenti: più recensioni convergono su crash, loop di login, splash screen infinito — rischio critico su un canale d'emergenza
- Push notification eccessive e non pertinenti: segnalate da 3+ recensioni, erode la fiducia nel canale notifiche — controproducente in un servizio che usa le push per comunicare lo stato dell'intervento
- Nessun sistema proattivo tipo RideCheck — solo tracking passivo su richiesta

---

**Risposte alle domande del Cluster 2**

**1.** Tre canali in parallelo: app (GPS automatico, tap per report), web online (stesso flusso senza app), telefono 24/7 (03330 046 046 — in header come "Broken down?"). Step intermedio esclusivo: safety advice screen con 3 istruzioni di sicurezza prima del bottone "Report breakdown". L'"Aim to get to you in around an hour" è l'unica promessa temporale comunicata sul sito. Il telefono è visibile nell'header ma "Broken down?" porta alla pagina safety, non direttamente a un numero — incentivo implicito al canale digitale. *(Osservazione diretta.)*

**2.** Tracking patrol disponibile in-app e online con ETA stimata. Attivazione ritardata: da recensioni reali il tracking si attiva ~15 minuti dopo la segnalazione, non al momento zero. Push notification per aggiornamenti di stato. Struttura simile ad ADAC — tracking parziale, non dall'accettazione. ETA media dichiarata: ~1 ora. Web tracking è il differenziatore rispetto ai competitor: chi è in un'area con scarsa batteria o senza l'app installata può comunque seguire l'intervento dal browser. *(Play Store recensioni + sito.)*

**3.** Approccio multi-canale con preferred channel esplicito: "It's twice as fast as calling, and we can pinpoint exactly where you are using your phone's location" — ragione tecnica per scegliere l'app, non solo marketing. Pagina /apps con 6 feature, prima è il breakdown reporting. Web tracking disponibile abbassa la barriera rispetto all'app-only. Telefono ancora presente e 24/7, ma non il percorso principale del sito. Il "Broken down?" in header apre la safety screen, non un numero — la gerarchia implicita è: digitale prima, telefono come fallback. *(Osservazione diretta.)*

**4.** Nessun prompt di rating post-intervento identificato (né su web né su Play Store). Smart Benefits in-app (sconti in 1000+ pub/ristoranti, auto, viaggi) — il valore della membership continua dopo l'emergenza, non termina con l'intervento. Principale critica post-intervento nelle recensioni: perdita accesso Smart Benefits in caso di rinnovo anticipato; problemi di login post-aggiornamento che impediscono accesso all'account. *(Play Store.)*

#### RAC (UK) — ✅ Completato

**Fonti:** rac.co.uk/breakdown-cover · rac.co.uk/download-and-drive · rac.co.uk/drive/features/ownership/the-myrac-app-route-planner-traffic-fuel-prices/ · Play Store (uk.co.rac.roadside, GB)

**Sintesi:** RAC è il secondo competitor UK diretto con un flusso digitale strutturalmente simile ad AA ma con due differenze operative critiche: il tracking è app-only (nessun web tracking come AA), e il sistema di autenticazione OTP-via-email è una barriera strutturale in emergenza — chi non riesce ad accedere all'app perde l'accesso al tracking nell'esatto momento in cui ne avrebbe bisogno. Il claim "Day or night – you don't need to call us – just tap the app" è la promessa giusta; l'esecuzione soffre del paradosso del canale critico: più l'app diventa indispensabile, più il suo punto di fallimento (autenticazione) diventa rischioso.

**Dati app:** ~2.5M download · uk.co.rac.roadside · Nota aggiornamento: "We update myRAC as often as possible to make it faster and more reliable for you"

**Pattern differenzianti:**
- **"You can track their arrival"** — tracking in-app dell'operatore con ETA e aggiornamenti in tempo reale: da recensione positiva (★5, luglio 2025) "the app was able to tell me an estimated time RAC would arrive & kept me updated with how far away they were"
- **GPS automatico zero-input** — "We'll be able to see exactly where you are": la posizione è condivisa automaticamente, nessun indirizzo da digitare in emergenza — identico ad AA
- **SMS di conferma come fallback** — "You'll get a confirmation text" in aggiunta alle push: chi perde la connettività internet riceve comunque una notifica offline, canale di backup non-app-dipendente
- **"Regular updates on your patrol's arrival time"** — push notification sequenziali durante l'attesa, non solo ETA iniziale
- **App-first senza canale telefonico promosso** — "Day or night – you don't need to call us – just tap the app": il numero (0333 2000 999) esiste ma il sito non lo promuove come percorso principale

**Punti critici:**
- **OTP email = barriera critica in emergenza** — Il login richiede un link one-time via email. In un'area con connettività limitata (rurale, autostradale) o a batteria scarsa, l'utente non riceve l'email e non può accedere all'app: Anthony Jackson (2★, aprile 2026) "This app is useless in areas of limited connectivity - the logging in process needs urgent revision - couldn't log in because the link wouldn't work"; D (1★, giugno 2026) "Will not let me in. Sends one time email link that just throws you back to the log in page"
- **Biometrico rimosso nell'ultimo aggiornamento** — metodo di accesso più rapido in emergenza (impronta digitale) eliminato; l'app ora richiede email + codice OTP ad ogni accesso
- **Tracking app-only: nessun web tracking** — a differenza di AA, chi non ha l'app installata o non riesce ad accedere non può seguire l'intervento dal browser — barriera aggiuntiva rispetto al competitor diretto
- **Status non motivato per attese lunghe** — Anthony Jackson (2★, aprile 2026): "I expect to be able to find out WHY, after a 6hr wait, my 8.30-11.30pm pickup is now 11-2am" — il tracking mostra ETA ma non spiega ritardi eccezionali; in caso di sovraccarico, lo strumento che dovrebbe rassicurare aumenta la frustrazione
- **App difficile da trovare in emergenza** — Mark Lawson (3★, gennaio 2026): "adding 'My' to the name makes it tricky to find in the list of Apps when you actually need it to report a breakdown — it's not under 'R' where you'd expect to find 'RAC'"; app usata raramente → rischio di non saperla usare quando serve

---

**Risposte alle domande del Cluster 2**

**1.** Due canali principali: app (GPS automatico, tap "Rescue" per segnalazione) e telefono 24/7 (0333 2000 999). Nessuna safety advice screen (differenza rispetto ad AA). Il web non è un canale di segnalazione autonomo. L'app è posizionata come percorso preferito: "Day or night – you don't need to call us". ETA: "most breakdowns in 60 mins or less". 4/5 breakdowns risolti sul posto. *(Osservazione diretta.)*

**2.** Tracking in-app con ETA e aggiornamenti push ("regular updates on your patrol's arrival time") + SMS di conferma. Tracking app-only: nessuna versione web disponibile come su AA. Da recensioni positive, il tracking funziona e riduce l'ansia ("takes the anxiousness out of how long your RAC will be"). Limite: per attese eccezionalmente lunghe il tracking non fornisce motivazioni per i ritardi. *(Play Store recensioni + sito.)*

**3.** "Day or night – you don't need to call us – just tap the app" — framing implicito: l'app è migliore, non solo alternativa. Nessun claim esplicito tipo "twice as fast as calling" come AA. GPS automatico è la ragione implicita ("We'll be able to see exactly where you are"). Web tracking non disponibile — barriera più alta rispetto ad AA per chi ha problemi con l'app. *(Osservazione diretta.)*

**4.** Nessun prompt di rating post-intervento identificato. App include RAC Rewards (fuel finder, sconti) e reminders (MOT, service, assicurazione) — valore di retention post-emergenza. Principale critica post-contratto nelle recensioni: auto-rinnovo non comunicato con aumenti di prezzo significativi; cancellazione difficile. *(Play Store recensioni + sito.)*

---

### Cluster 3

#### AutoAssist (IT) — ✅ Completato

**Fonti:** autoassist.it · autoassist.it/servizi · autoassist.it/wp-content/uploads/2024/03/Auto-Assist-Condizioni.pdf

**Sintesi:** AutoAssist è il caso più estremo del Cluster 3: il player con il Trustpilot più alto del benchmark (4,3/5 vs ACI 1,9/5) ha la **minore trasparenza tariffaria** dell'intero cluster. Nessun prezzo sul sito, nessuna pricing page, nessun piano. Le condizioni contrattuali esistono solo come PDF di 4 pagine nel footer — non HTML, non scansionabile, non raggiungibile dalla navigazione principale. Il modello è un funnel B2B2C (parte del Gruppo Facile.it) che genera lead telefonici: la conversione avviene per via, non online. Il trust non viene costruito attraverso la trasparenza, ma attraverso la reputazione Trustpilot e la qualità percepita del servizio. Questo separa il Cluster 3 (trasparenza prezzi) dal Cluster 4 (fiducia): AutoAssist è un anti-pattern per il 3 e un benchmark per il 4.

**Struttura del sito:** 3 pagine operative (Home, Servizi, Contatti). Architettura minimale di lead generation — nessun flusso self-service, nessun acquisto online. I link "Condizioni" in footer puntano al PDF; "Privacy Policy" all'unica altra pagina legale.

**Cosa contiene il PDF (4 pagine, marzo 2024):**
- **Art. 5 — Servizi inclusi:** depannage sul posto (max €150), traino fino a 50km (eccedenza a carico utente), recupero fuori strada (max €350 iva esclusa), auto sostitutiva max 7 giorni (se riparazione >8h). Max 3 interventi per durata contrattuale
- **Art. 6/8 — Esclusioni e inoperatività:** gare automobilistiche, guerre, calamità naturali, alcol/droghe, uso improprio del veicolo, mancata manutenzione, atti vandalici, veicolo ceduto o rivenduto
- **Art. 2 — Limite operativo:** servizio valido solo fuori dalla sede/residenza del beneficiario (non copre guasti sotto casa)
- **Art. 3 — Territorio:** Italia + 30+ paesi europei
- **Zero prezzi** — nessuna tariffa, nessun canone mensile/annuale nel PDF o nel sito

**Pattern differenzianti:**
- **Trustpilot come unica leva di trasparenza** — l'intero sito punta a Trustpilot: "Cosa ci distingue dagli altri? La qualità certificata TrustPilot." Il badge e il link sono presenti in homepage e nella pagina servizi; le recensioni fanno il lavoro che le condizioni non fanno
- **B2B2C come modello strutturale** — AutoAssist è il marchio operativo di NetAssistance s.r.l. (Gruppo Facile.it/Tangerine Holdco): il canale primario non è il cliente finale ma gli intermediari (assicuratori, concessionari, comparatori). I prezzi variano per canale — questo spiega la loro assenza sul sito pubblico
- **Sito come biglietto da visita** — non è un prodotto digitale: è un'interfaccia per generare la telefonata. Ogni CTA porta al numero verde

**Punti critici:**
- **Prezzo completamente assente** — non esiste alcuna indicazione di costo né sul sito né nel PDF delle condizioni. L'utente non può valutare il servizio senza chiamare
- **PDF nel footer = condizioni non leggibili** — il link "Condizioni" nel footer porta a un file PDF WordPress, non a una pagina HTML. Non è indicizzabile, non è accessibile da mobile senza app esterna, non è scansionabile rapidamente
- **Testo contraddittorio nel PDF** — Art. 5.2 afferma che "i costi di deposito del veicolo [...] sono compresi nel servizio" poi nella stessa frase "sono esclusi eventuali costi di deposito" — errore redazionale mai corretto, potenzialmente fonte di contestazioni
- **Nessun piano o profilo differenziato** — un solo livello di servizio, nessuna distinzione socio/non-socio, base/premium o per tipo di veicolo
- **Servizi su sito = 3 bullet generici** — "Traino e rimozione veicoli", "Assistenza h24, 7/7 giorni", "Assistenza stradale": nessun limite, massimale, km, ora di copertura visibile nella navigazione principale

**Risposte alle domande del Cluster 3**

**1. Come rendono leggibili tariffe variabili o condizioni complesse senza rimandare a PDF?**
Non lo fanno. Il sito non ha alcuna sezione prezzi, alcuna FAQ con limiti e coperture, alcuna tabella comparativa. Il rimando è diretto e unico: chiamare il numero verde. Le condizioni esistono solo in PDF. È il caso più estremo del benchmark su questo punto. *(Osservazione diretta + PDF estratto.)*

**2. Come strutturano la sezione "cosa è incluso / non incluso" con esempi concreti?**
Non esiste tale sezione sul sito. Il PDF agli Art. 5 (incluso) e Art. 6/8 (escluso) elenca le prestazioni con massimali numerici (€150, €350, 50km, 3 interventi, 7 giorni) ma con linguaggio legale-assicurativo, senza esempi concreti né scenari d'uso. L'utente che vuole capire "se mi si scarica la batteria cosa succede?" non trova risposta né sul sito né nel PDF. *(Osservazione diretta + PDF.)*

**3. Come gestiscono la distinzione tra profili diversi (es. socio/non-socio, piano base/premium)?**
Non gestiscono. Un solo livello di servizio, nessun piano alternativo. Il sito non distingue tra privati e aziende, tra veicoli diversi, tra coperture diverse. Il modello B2B2C suppone che la differenziazione avvenga nell'accordo con l'intermediario, non nella pagina pubblica. *(Osservazione diretta.)*

**4. Come presentano tariffe e condizioni nelle pagine servizio? HTML scansionabile o PDF nascosto?**
Pagina servizi: 3 bullet HTML generici senza un singolo numero, data o km. Footer: link a PDF (`/wp-content/uploads/2024/03/Auto-Assist-Condizioni.pdf`). Il PDF contiene i limiti quantitativi ma zero prezzi. Non esiste nessuna pagina HTML con condizioni strutturate. È il caso peggiore di trasparenza tariffaria nel benchmark. *(Osservazione diretta.)*

#### Europ Assistance (IT) — ✅ Completato

**Fonti:** europassistance.it/prodotti-per-te/mobilita/auto-noproblem · sodauto.europassistance.it · europassistance.it/set-informativi

**Sintesi:** Europ Assistance è il caso più complesso del Cluster 3: presenta due modelli di pricing radicalmente diversi nella stessa famiglia di prodotti. **SOD** (Soccorso on Demand, `sodauto.europassistance.it`) è il caso di massima trasparenza — **99€ fisso** nella hero, con -10% sconto immediato, nessun preventivo necessario, nessuna condizione variabile. **Auto Noproblem** (`europassistance.it/prodotti-per-te/mobilita/auto-noproblem`) è invece il caso di trasparenza parziale: 3 tier differenziati in HTML (Base/Completa/Top) con incluso/escluso leggibile, ma **nessun prezzo** senza passare per il preventivo online. La biforcazione è strutturale e rivela una tensione interna: EA conosce come si fa la trasparenza assoluta (SOD), ma non l'applica al prodotto principale.

**Architettura prodotto Mobilità:**
- **Auto Noproblem** — abbonamento annuale (o mensile). 3 livelli di copertura, preventivo obbligatorio per il prezzo. Sito principale.
- **SOD (Soccorso on Demand)** — pay-per-use. 99€ fisso per singolo intervento, prezzo visibile in homepage senza alcun input. Sottodominio separato (`sodauto.europassistance.it`).
- **Europ Assistance VAI S.p.A.** — entità giuridica operativa separata, menzionata solo in footer e note legali. Numero verde diverso (803 803 vs 800.44.33.22).

**Auto Noproblem — Struttura dei 3 tier (HTML):**
- **Base:** Soccorso stradale per guasto/incidente, officina mobile sul posto, recupero fuoristrada
- **Completa:** Base + furto parziale/tentato, foratura pneumatici, esaurimento batteria, **auto sostitutiva** in caso di fermo per riparazione, assistenza passeggeri
- **Top:** Completa + auto sostitutiva **sul luogo del fermo** (non più dopo la riparazione), consegna auto a destino o taxi. Massima mobilità garantita immediata.

**SOD — Struttura del servizio (HTML):**
- Prezzo: 99€ con -10% sconto (→ 89,10€) visibile in homepage senza alcun input
- Flow: inserisci posizione/targa → visualizza preventivo → aspetta soccorso (25–45 min)
- Coperture elencate in HTML: guasto, batteria, foratura, esaurimento carburante, sportelli bloccati, incidente
- Veicoli: auto, moto, caravan, veicoli commerciali

**Pattern differenzianti:**
- **SOD come anti-modello positivo** — l'unico caso nel benchmark di assistenza stradale con prezzo fisso visibile in homepage senza preventivo. Il 99€ non è nascosto: è il messaggio principale della hero. Pattern da food delivery / ride-hailing applicato all'assistenza stradale
- **FAQ come surrogate di condizioni** — Auto Noproblem ha 5 FAQ expandable con scenari concreti: "Sono coperto in tutta Europa?", "È prevista l'auto sostitutiva?", "Cos'è il servizio di Dépannage?", "In caso di furto dell'auto su che supporto posso contare?", "Ho perso le chiavi dell'auto: cosa posso fare?" — non sono condizioni complete ma è il tentativo più avanzato nel benchmark di rispondere alle domande pre-acquisto in HTML
- **Pagamento mensile in hero** — "Anche con pagamento mensile" è menzionato nella hero di Auto Noproblem. Unico player del benchmark di assistenza stradale che esplicita la flessibilità di pagamento prima del preventivo
- **Set informativi strutturati** — la pagina `/set-informativi` organizza i documenti legali in categorie (Viaggi / Mobilità / Casa / Salute) e distingue tra prodotti "individuali" e "collettivi" (B2B partner). Non è un PDF nel footer: è una sezione dedicata della navigazione

**Punti critici:**
- **Auto Noproblem senza prezzo** — nonostante 3 tier HTML ben descritti, il prezzo rimane invisible fino al preventivo. L'utente deve inserire numero di veicoli e data per vedere un costo. Pattern tipico assicurativo che crea attrito pre-acquisto
- **SOD in sottodominio separato** — il prodotto più trasparente del catalogo è su `sodauto.europassistance.it`, non integrato nel sito principale. Un utente che visita europassistance.it può non trovarlo facilmente
- **Set informativo = PDF** — il "Set informativo auto noproblem" linkato nella pagina prodotto è un PDF su Contentful CDN (`assets.ctfassets.net`). I documenti legali rimangono PDF, non HTML
- **Rebrand in corso** — il footer annuncia "Europ Assistance diventa Redion". Il cambio brand non è ancora riflesso nel sito ma introduce incertezza per l'utente: la fiducia costruita sul nome EA si trasferirà?
- **Biforcazione non comunicata** — il sito non spiega chiaramente la differenza tra abbonamento annuale (Auto Noproblem) e pay-per-use (SOD). Un utente che cerca soccorso stradale deve navigare tra due sottodomini per confrontare i due modelli

**Risposte alle domande del Cluster 3**

**1. Come rendono leggibili tariffe variabili o condizioni complesse senza rimandare a PDF?**
Due approcci coesistono. SOD: prezzo fisso 99€ in hero — zero variabilità, zero ambiguità. Auto Noproblem: 3 tier con incluso/escluso in HTML + 5 FAQ con scenari concreti, ma il prezzo richiede preventivo. Rispetto ad AutoAssist (zero HTML, solo PDF), EA è significativamente più avanzata sul contenuto operativo. Il PDF rimane solo per i documenti legali formali, non per la comprensione del servizio. *(Osservazione diretta.)*

**2. Come strutturano la sezione "cosa è incluso / non incluso" con esempi concreti?**
I 3 tier sono descritti in HTML con una progressione additiva chiara: ogni livello aggiunge coperture rispetto al precedente, rendendo visibile il salto di valore. Le FAQ trattano casi concreti (batteria, foratura, chiavi, furto, incidente) con spiegazioni in linguaggio naturale. Manca però la lista esplicita degli esclusi — non c'è un "cosa NON è incluso" equivalente. *(Osservazione diretta.)*

**3. Come gestiscono la distinzione tra profili diversi (es. socio/non-socio, piano base/premium)?**
Auto Noproblem offre 3 profili differenziati per livello di copertura (Base/Completa/Top) + SOD come profilo pay-per-use. "Anche con pagamento mensile" aggiunge una distinzione di impegno finanziario. È la gestione dei profili più sviluppata nel benchmark di categoria — ma non arriva alla distinzione privati/aziende (B2B assente sul sito consumer). *(Osservazione diretta.)*

**4. Come presentano tariffe e condizioni nelle pagine servizio? HTML scansionabile o PDF nascosto?**
Auto Noproblem: tier in HTML con descrizioni di copertura, FAQ expandable con scenari, preventivo online per il prezzo. "Set informativo" = PDF su CDN. SOD: prezzo in HTML nella hero, flow di acquisto 3-step, coperture in HTML dettagliato. Valutazione complessiva: **HTML per il contenuto operativo, PDF per i soli documenti legali formali** — un pattern sensato e corretto. È il migliore nel benchmark di categoria su questo punto. *(Osservazione diretta.)*

#### Iliad (IT) — ✅ Completato

**Fonti:** iliad.it · iliad.it/offerte-iliad-mobile.html · iliad.it/offerta-iliad-top250plus-999.html · iliad.it/trasparenza-tariffaria-mobile.html · iliad.it/brochure-prezzi-mobile.html

**Sintesi:** Iliad è il benchmark assoluto del Cluster 3 — e probabilmente dell'intero benchmark sulla trasparenza tariffaria. La filosofia "prezzo fisso per sempre" non è solo un claim: è implementata strutturalmente a ogni livello del sito. Il prezzo è visibile nella card offerta, codificato nell'URL della pagina (`/offerta-iliad-top250plus-999.html`), nel titolo della pagina (`TOP 250 PLUS: minuti, SMS, Internet – Offerta Mobile 9,99€`). Zero preventivo, zero modulo, zero chiamata. L'utente vede il prezzo finale prima ancora di aprire la pagina. La prova più concreta della promessa è storica: l'offerta Voce a 4,99€ è attiva dal **24/07/2018** — 8 anni senza modifica — e la data è pubblicata nella pagina Trasparenza Tariffaria.

**Offerte disponibili (tutte con prezzo visibile senza interazione):**
- **GIGA PRIME** — 12,99€/mese (Amazon Prime incluso 12 mesi, poi 4,99€/mese)
- **TOP 300 PLUS** — 11,99€/mese (300 GB, 5G, 25 GB EU)
- **TOP 250 PLUS** — 9,99€/mese (250 GB, 5G, 25 GB EU)
- **GIGA 180** — 8,99€/mese (180 GB)
- **GIGA 150** — 7,99€/mese (150 GB)
- **VOCE** — 4,99€/mese (solo chiamate e SMS, attiva dal 2018)
- **DATI 350** — 14,99€/mese (solo dati, 350 GB, 5G)
- **DOMOTICA** — 1,99€/mese (IoT, solo dati)

**Architettura documentale:**
- **HTML** (contenuto commerciale): pagina offerta per singolo piano, incluso/escluso strutturato, overage pricing in €/MB, trasparenza tariffaria, sintesi contrattuale, condizioni generali di contratto, schemi tariffari
- **PDF** (compliance AGCOM): brochure prezzi per offerta (`/docs/prezzi/prezzi-[offerta].pdf`), trasparenza tecnica per offerta, carta dei servizi, modulistica recesso
- Il PDF esiste perché richiesto da AGCOM come documento regolatorio — non è la fonte primaria per l'utente, ma l'allegato formale

**Pattern differenzianti:**
- **Prezzo nell'URL** — unico player del benchmark a codificare il prezzo nella struttura dell'URL stesso: `offerta-iliad-top250plus-999.html`
- **Stabilità temporale come feature** — "OFFERTE CHE NON CAMBIANO NEL TEMPO" in ogni pagina offerta + data attivazione pubblica nella pagina trasparenza (Voce: 24/07/2018, 8 anni)
- **Zero costi nascosti come brand promise strutturale** — "SENZA VINCOLI E COSTI NASCOSTI" non in footer, non in note, ma nella sezione hero di ogni pagina offerta
- **Overage pricing in HTML** — superata la soglia dati: "Superati i 25 GB dedicati in Europa, pagherai un sovrapprezzo di 0,001342 EUR/MB" + "0,90€/100MB" per il piano nazionale — nella pagina offerta stessa, non in PDF
- **Pagina Trasparenza Tariffaria HTML dedicata** — `trasparenza-tariffaria-mobile.html`: lista completa offerte con prezzi e date di validità, policy di attivazione (9,99€ una tantum), policy di recesso (gratuito, 30gg preavviso, 3 canali), diritto di ripensamento 14 giorni
- **Servizi inclusi elencati esplicitamente** — Mi richiami, Hotspot, Nessuno scatto alla risposta, Controllo credito residuo, Segreteria telefonica, Portabilità del numero, VoLTE — lista positiva completa
- **Attivazione separata e dichiarata** — 9,99€ una tantum per SIM, sempre visibile sopra la CTA

**Punti critici (pochi, quasi tutti giustificati):**
- Brochure Prezzi per offerta sono PDF — ma per compliance AGCOM, non per scelta UX
- "Condizioni di uso lecito e corretto" per minuti/SMS illimitati rimanda a link separato — la limitazione non è immediatamente leggibile in pagina
- Timer conto alla rovescia su TOP 250 PLUS e TOP 300 PLUS (offerte temporanee) — introduce urgenza che si discosta dalla promessa di stabilità
- Nessuna sezione esplicita "cosa NON è incluso" in negativo — solo lista positiva degli inclusi
- iliadclub (programma multi-SIM) richiede fibra iliad come prerequisito — non immediato per chi cerca solo mobile

**Risposte alle 4 domande Cluster 3:**
1. **Leggibilità tariffe senza PDF:** Eccellenza assoluta. Prezzo visibile in card, URL e titolo pagina. Unica azione richiesta: aprire la pagina offerte. Zero preventivo, zero form, zero chiamata. Overage pricing esplicito in HTML nella stessa pagina offerta.
2. **Incluso/escluso con esempi concreti:** Lista strutturata HTML degli inclusi (GB, minuti, SMS, roaming EU, hotspot, VoLTE, ecc.) con overage pricing dichiarato. Mancano esempi narrativi di scenari concreti (nessun "se stai navigando in Francia..."). Nessuna sezione "non incluso" in negativo.
3. **Distinzione profili diversi:** 8 offerte differenziate coprono ogni profilo: voce pura (4,99€), IoT (1,99€), mid-range (7,99-8,99€), premium (9,99-12,99€), solo dati (14,99€). Business separato su `business.iliad.it`. iliadclub per famiglie multi-SIM (richiede fibra). Nessuna distinzione per anzianità/fedeltà sul sito consumer.
4. **HTML vs PDF:** Il contenuto commerciale è interamente HTML — incluso le condizioni generali di contratto e la sintesi contrattuale. I PDF esistono solo per compliance AGCOM. **Miglior punteggio del benchmark su questo punto.**

#### ConTe.it — ✅ Completato

**Fonti:** conte.it · conte.it/assicurazione-auto/ · conte.it/garanzie-assicurazione-auto/ · conte.it/assicurazione-auto/protezione-kasko/ · conte.it/assicurazione-rc-auto/ · conte.it/documenti-polizza/ · conte.it/preventivass-e-contratto-base/

**Sintesi:** ConTe.it è il caso più simile strutturalmente ad ACI Global Servizi nell'intero Cluster 3: un prodotto a prezzo variabile per profilo (Classe di Merito, età conducente, tipo veicolo, zona geografica) dove il preventivo è la porta obbligata per qualsiasi cifra. Questo non è una scelta di design opaca — è la struttura legale dell'RCA italiana. L'IVASS impone prezzi personalizzati; non è possibile pubblicare "la polizza costa X€" come fa Iliad. La domanda di analisi diventa quindi: **cosa comunica ConTe prima che l'utente faccia il preventivo?** La risposta è: le garanzie accessorie in HTML, senza prezzi. Franchigie, massimali ed esclusioni reali sono rinviate al Set Informativo PDF (per legge IVASS) o al contratto post-stipula. L'unica eccezione positiva è il Contratto Base IVASS, che ha sezioni "Cosa include / Cosa esclude" esplicite in HTML — ma si tratta del prodotto regolatorio minimo, non dell'offerta commerciale.

**Architettura informativa pre-preventivo:**
- **Homepage:** Form preventivo (targa + data di nascita) come unico contenuto di conversione. Nessun prezzo, nessun range orientativo, nessun "da X€/anno".
- **Assicurazione Auto:** Hub con garanzie accessorie filtrabili ("Per la persona" / "Per l'auto"). 12 garanzie elencate come card, ognuna con headline descrittiva. Nessun prezzo per nessuna.
- **Pagine garanzia (es. Kasko):** Lista HTML di cosa copre la garanzia (lista positiva). Nessuna sezione "cosa non copre". Franchigie, scoperti e massimali rinviati esplicitamente al contratto di polizza. Rimando al Set Informativo PDF per i dettagli.
- **RCA Auto:** Pagina editoriale HTML estesa su come funziona la RCA, casi di rivalsa (quando non paga), sistema Bonus/Malus, sanzioni. Unico punto di descrizione parziale degli esclusi — ma in forma narrativa, non strutturata come incluso/escluso.
- **Documenti Polizza:** Spiega che Certificato, Contratto, Modulo CAI e Carta Verde vengono inviati via email post-stipula. Nessun link a condizioni pre-contratto consultabili sul sito pubblico.
- **Preventivass e Contratto Base:** Unica pagina con struttura "Cosa include / Cosa esclude" esplicita in HTML — ma si riferisce al prodotto IVASS regolatorio, non ai prodotti commerciali ConTe.

**Garanzie accessorie disponibili (tutte senza prezzo visibile):**
- Assistenza Stradale, Infortuni del Conducente, Tutela Legale (Per la persona)
- Incendio e Furto, Kasko, Mini Kasko, Cristalli, Eventi Naturali, Atti Vandalici, No Assicurati, Rinuncia alla Rivalsa, Bonus RCA (Per l'auto)
- Ciascuna con pagina dedicata: lista coperture, rimando a Set Informativo PDF, CTA preventivo.

**Profili e segmentazione:**
- Auto / Moto / Cane e Gatto — tre rami separati con garanzie proprie
- ConTe SAT (polizza con dispositivo satellitare) come variante prodotto con sconto RCA implicito
- Family & Friends: sconto fino al 25% per parenti e amici di clienti esistenti
- Legge Bersani: ereditabilità della Classe di Merito del familiare — citata nelle FAQ e nella pagina RCA
- Nessuna distinzione profilo giovane/senior/fleet nella navigazione pubblica — emerge solo nel form preventivo
- Nessuna area B2B/fleet separata nel menu principale

**Architettura documentale:**
- **HTML** (pre-vendita): pagine garanzie, RCA, sospensione polizza, FAQ, come-fare-per
- **PDF IVASS** (obbligatori per legge): Set Informativo per prodotto (con franchigie, massimali, esclusioni), Informativa Precontrattuale per versioni Preventivass
- **Email post-stipula**: Certificato di Assicurazione, Contratto completo, Modulo CAI, Carta Verde
- Le condizioni complete (incluso le esclusioni specifiche) non sono consultabili nel sito pubblico senza fare il preventivo o stipulare

**Punti critici:**
- Nessun prezzo o range orientativo visibile — neanche "da X€/anno" per profilo tipo
- Franchigie non visibili pre-preventivo: l'utente non sa quanto paga di tasca propria in caso di sinistro fino a post-acquisto
- Nessuna sezione "cosa non copre" nelle pagine garanzia — solo lista positiva delle coperture
- Set Informativo PDF è l'unica fonte di esclusioni complete — non accessibile come primo contenuto
- Nessun esempio narrativo concreto (es. "se la tua auto viene graffiata in un parcheggio, la Mini Kasko copre se...")

**Rilevanza per ACI:**
ConTe.it è lo specchio metodologico di ACI Global Servizi: stesso problema (prezzo variabile per profilo, preventivo obbligatorio), stessa soluzione (form come prima interazione). La differenza progettuale da investigare è: ConTe mostra almeno le garanzie accessorie in HTML come contenuto esplorabile prima del preventivo; ACI potrebbe fare altrettanto con le coperture per piano/tipo di intervento. L'altra leva, ancora non usata da ConTe, sarebbe mostrare range di prezzo tipici ("un neopatentato con auto nuova paga mediamente X–Y€/anno") — informazione che riduce l'incertezza senza sostituire il preventivo personalizzato.

**Risposte alle 4 domande Cluster 3:**
1. **Leggibilità tariffe senza PDF:** Assente pre-preventivo. Nessun prezzo, nessun range, nessun indicatore di costo. La struttura del prodotto RCA rende impossibile un prezzo fisso — ma un range orientativo o un esempio per profilo sarebbe possibile senza cambiare il modello. Punteggio più basso del cluster su questa domanda.
2. **Incluso/escluso con esempi concreti:** Ogni garanzia accessoria ha lista HTML di cosa copre (lista positiva). Nessuna sezione esclusi in pagina. Franchigie e massimali rinviati a PDF. Il Contratto Base IVASS è l'unica eccezione con sezione esclusioni esplicita in HTML. Nessun esempio narrativo concreto. Struttura confrontabile tra garanzie, ma solo per le coperture.
3. **Distinzione profili diversi:** Tre rami (auto/moto/animali) + filtro per la persona/per l'auto nelle garanzie. ConTe SAT e Family & Friends come varianti implicite. Nessun profilo giovane/fleet/business nel sito pubblico — la segmentazione vera avviene solo nel form preventivo.
4. **HTML vs PDF:** HTML per il contenuto commerciale delle garanzie (coperture); PDF per le condizioni complete (Set Informativo IVASS obbligatorio). Condizioni post-contratto inviate per email. Architettura ibrida: meglio di AutoAssist (che non ha nemmeno le pagine garanzia), peggio di Iliad (tutto in HTML). Il PDF è qui obbligatorio per legge, non una scelta di design.

#### Lemonade — ✅ Completato

**Fonti:** lemonade.com · lemonade.com/car · lemonade.com/policy-two · lemonade.com/car/explained/what-does-car-insurance-cover/ · lemonade.com/car/explained/how-much-does-car-insurance-cost/ · lemonade.com/lemonade-goes-global

**Sintesi:** Lemonade è il benchmark di eccellenza assoluto del Cluster 3 — e l'unico player che ha risolto il problema della trasparenza anche sul documento di polizza, non solo sul sito marketing. Non è un competitor diretto di ACI (opera solo in US per il Car; EU limita a France, Germany, Netherlands, UK per renters/home; nessuna presenza italiana). È un cross-sector benchmark per pattern UX. Il suo contributo principale al cluster non è l'assicurazione auto in sé, ma la dimostrazione che trasparenza pre-acquisto + leggibilità delle condizioni + HTML-first sono scelte progettuali realizzabili anche in un settore regolamentato.

**Architettura prodotto:**
- **Car** — disponibile in 9 stati US (AZ, CA, CO, IL, IN, OH, OR, TN, TX, WA). Pay-per-mile in AZ, CA, OR, WA (acquisizione Metromile). Pricing basato su telematics: guida, chilometraggio, tipo veicolo, zona, storia di guida.
- **Renters / Homeowners / Pet / Life** — disponibili negli US. Renters/Home anche in FR, DE, NL, UK.
- **Policy 2.0** — documento di polizza HTML open source, "currently only available in Europe."

**Prezzi pre-preventivo (homepage e pagina Car):**
- Renters: from $5/mo · Homeowners: from $25/mo · Car: as low as $30/mo · Pet: from $10/mo · Life: from $8/mo
- Visibili nella grid della homepage senza alcun input. Ripetuti nella pagina prodotto ("As low as $30/mo, based on your driving profile").
- I propri tassi specifici rimangono quote-gated (CTA "check our prices" → form). Il "from" è un floor indicativo, non il prezzo reale di un profilo specifico. La distinzione rispetto a Iliad: prezzi fissi per tutti vs. floor variabile per profilo. Ma rispetto a ConTe (nessun numero) o AutoAssist (nessun numero): presenza di un riferimento numerico è già un segnale di trasparenza.

**Educational hub (car/explained/):**
- Pagina dedicata "What Does Car Insurance Cover?" — 9 tipi di copertura descritti in HTML con scenari concreti, incluso sezione "What won't be covered" esplicita
- Pagina dedicata "How Much Does Car Insurance Cost?" — tabelle per stato, per età, per modello auto (tutti da fonte terza ValuePenguin), range $912–$2.496/anno per minimum vs full coverage, fattori di prezzo descritti in HTML
- Deductible range dichiarato: $250–$2.000, con spiegazione che alzare il deductible abbassa il premio
- Esempi numerici concreti: California 18 anni = $509/mo, California 30 anni = $221/mo; Nevada full coverage = $335/mo, Ohio = $148/mo; limite $30k vs sinistro $45k → $15k gap out-of-pocket
- Modello: nessun prezzo personale, ma contesto educativo sufficiente per farsi un'idea prima di qualsiasi form

**"What's covered / What's not covered" su pagina Car:**
- Sezione "What's covered" con 6 scenari narrativi: "If you're in a car crash", "If you're stalled on the highway", "If the unexpected happens" (fuoco, meteo, vandalismo), "If your glass is damaged", "If you're sued for liability", "If your car is stolen"
- Esclusione esplicita nell'FAQ: uso commerciale/rideshare (Uber/Lyft) non coperto senza endorsement specifico
- Esclusione custom parts: threshold $1.000 — oltre, non coperto automaticamente
- Deductible spiegato con esempio concreto nel Policy 2.0: "$7.000 sinistro − $500 deductible = $6.500 pagato"

**Policy 2.0 — il punto di eccellenza assoluta:**
- "World's first open source insurance policy" — documento di polizza completamente in HTML, non PDF
- "Copyleft, GNU Free Documentation License" — open source su GitHub, contribuzione aperta
- "Currently only available in Europe" (renters/home in FR/DE/NL/UK)
- Struttura: "The Squeezed Version" (riassunto colloquiale) + "And now, the full story…" (sezioni dettagliate)
- Ogni sezione segue il pattern: descrizione affermativa di cosa è coperto → sottosezione esplicita "What's not covered"
- Linguaggio colloquiale per le esclusioni: "I lost it", "my dog ate it", "my kid dropped it", "my power went out", "my computer died" — ognuno come esempio di cosa NON è coperto
- Definizioni inline dei termini tecnici: "A deductible (AKA your 'deductible') is the amount..."
- "Scan this with your phone, or click on it, to view your policy online, make changes, and file claims" — documento interattivo, non statico
- Il PDF non esiste: il contratto è il sito stesso

**Profili e segmentazione:**
- Profili per tipo di prodotto: Car / Renters / Homeowners / Pet / Life — pagine separate, non un unico form generico
- Car: low mileage discount, EV/hybrid discount, safe driver (telematics), Tesla FSD 50% discount su miglia guidate in autonomous mode
- Anti-theft discount: 5–15%; pay-as-you-drive savings: 10–40%
- Bundling cross-prodotto esplicito con sconto automatico
- Nessuna pagina profilo demografico (giovani, senior, fleet): la segmentazione avviene nel preventivo via app, non in pagine pre-preventivo dedicate
- No B2B/fleet area pubblica

**Architettura documentale:**
- **HTML** (tutto il contenuto commerciale): pagine prodotto, coverage explained, cost explained, Policy 2.0
- **PDF** (non trovati nel flusso pre-acquisto): nessun PDF obbligatorio per comprendere il prodotto
- **App / email post-stipula**: gestione polizza, claims, tracking guida

**Punti critici:**
- I propri prezzi specifici rimangono nel preventivo — il "from $30/mo" è un floor, non un prezzo reale per un profilo
- Disponibile solo in US per Car — il benchmark non è trasferibile 1:1 sul modello assicurativo italiano (nessun IVASS, nessuna Classe di Merito, nessun obbligo RCA personalizzato per legge)
- Profili demografici non separati pre-preventivo: un giovane al primo preventivo non vede esplicitamente "per un neopatentato, il costo tipico è..."
- Policy 2.0 è per renters/home (non car), ed è "available in Europe" — potenzialmente disponibile in futuro anche in IT ma ad oggi assente

**Rilevanza per ACI:**
Tre pattern trasferibili, adattati al contesto italiano:
1. **Floor price** — "a partire da X€/anno per piano Essenziale" o "un intervento tipico da X€ con SOD" — segnale numerico prima del preventivo, senza sostituirlo
2. **Educational hub** — pagine "cosa copre / cosa non copre" per ogni servizio, con scenari concreti narrativi, separati dalla pagina prodotto
3. **Logica Policy 2.0** — non necessariamente HTML aperto, ma il principio: condizioni in linguaggio naturale, struttura "incluso / non incluso" esplicita, deducibili spiegati con esempi numerici. Applicabile alle pagine servizio di ACI senza richiedere open source o GitHub

**Risposte alle 4 domande Cluster 3:**
1. **Leggibilità tariffe senza PDF:** Floor price visibile in homepage su tutti i prodotti ("as low as $30/mo"), educational content con medie nazionali/statali/per profilo su pagina dedicata. I propri tassi rimangono quote-gated. Punteggio alto nel cluster — non assoluto come Iliad (prezzo fisso per tutti) ma nettamente superiore a ConTe e AutoAssist.
2. **Incluso/escluso con esempi concreti:** Eccellenza assoluta. Car page con 6 scenari "cosa copre", Car Coverage con 9 tipi di copertura + sezione "what won't be covered", Policy 2.0 con pattern sistematico "covered / not covered" su ogni sezione, esempi colloquiali per le esclusioni, deductible con esempio numerico. Il più completo del benchmark.
3. **Profili diversi:** Separazione per tipo di prodotto (Car/Renters/Pet/Life), differenziazione di prezzo per telematics/mileage/EV, bundle discount cross-prodotto. No pagine per profilo demografico pre-preventivo. Punteggio intermedio.
4. **HTML vs PDF:** Eccellenza assoluta. Nessun PDF nel percorso pre-acquisto. Policy 2.0 come documento di polizza HTML. Educational hub interamente HTML. Il PDF non compare come touchpoint nel customer journey sul sito pubblico. Miglior punteggio del cluster su questo punto — pari a Iliad.

---

### Cluster 4

#### AutoAssist (IT) — ✅ Completato

**Fonti:** autoassist.it · autoassist.it/servizi · ricerche SERP Trustpilot IT (33 recensioni, accesso diretto bloccato da robots.txt)

**Sintesi:** AutoAssist è il paradosso del Cluster 4 — e la risposta alla domanda centrale del benchmark. Il player con il Trustpilot più alto della categoria (4,3/5) ha **zero trasparenza tariffaria** (C3 anti-pattern), **zero sistema digitale d'emergenza** (C2 anti-pattern), un sito di 3 pagine senza prezzi né condizioni. Eppure viene scelto e raccomandato. Il motivo non sta in quello che comunica _prima_ del servizio, ma in quello che fa _durante_: velocità di intervento reale + comunicazione proattiva nel momento dello stress. La fiducia è costruita post-esperienza, non pre-esperienza. Il Trustpilot non è il trust signal — è il tracciante del trust reale che si genera nell'operatività.

**Struttura trust sul sito:**
- **3 pilastri dichiarati:** Velocità ("saremo lì per te nel più breve tempo possibile"), Esperienza ("decisioni rapide e accurate"), Gentilezza ("empatia e rispetto, un ambiente rassicurante")
- **CTA trust:** "Cosa ci distingue dagli altri? La qualità certificata TrustPilot" — l'unico differenziatore comunicato esplicitamente rimanda all'esterno
- **Group affiliation:** "Autoassist.it fa parte del Gruppo Facile.it" — dichiarato in footer con descrizione di tutti i siti del gruppo (Facile.it, Prestiti.it, Mutui.it, Assicurazione.it, BolletteCasa.it, Miacar.it). Posizionato come segnale di legittimità, non come garanzia istituzionale primaria
- **Entità legale:** AutoAssist è un marchio di NetAssistance s.r.l., soggetta a Tangerine Holdco S.p.A. — struttura societaria visibile nel footer, non comunicata come valore

**Profilo Trustpilot:**
- **33 recensioni totali** (campione minimo per 4,3/5) — il punteggio è statisticamente fragile ma coerente nel tono
- **Temi ricorrenti nelle recensioni (da SERP snippet):**
  - Velocità reale: "arrivati in neanche mezz'ora"
  - Comunicazione proattiva: "mi hanno chiamato più volte assicurandosi che..." — il centralino richiama durante l'attesa senza che il cliente lo chieda
  - Tono umano: "gentilezza ed efficienza", "professionale e rapido"
  - Affiancamento: "assistenza clienti fantastica" — il servizio non è solo il tecnico, è tutto il contatto umano pre/durante/post

**La leva di fiducia principale:**
La comunicazione proattiva durante l'attesa. Non è la velocità in sé (anche altri sono veloci) — è che qualcuno richiama il cliente per aggiornarlo, senza essere sollecitato. Questo comportamento, in un momento di stress, trasforma un servizio ordinario in un'esperienza memorabile. Il copy "Gentilezza" sul sito traduce esattamente questo: non è un valore decorativo, è la descrizione di un comportamento operativo che si riflette poi sulle recensioni.

**Paradosso brand/trust:**
AutoAssist delega il trust a Trustpilot ("Collegati a TrustPilot", CTA diretta alla pagina reviews) — rinuncia a costruire fiducia sul proprio sito e la riprende come effetto del servizio erogato. Questo funziona perché il servizio è coerente con le promesse operative (velocità, gentilezza). Non funzionerebbe se il servizio fosse mediocre: 33 recensioni a 4,3 reggono solo finché la media resta alta.

**Risposte alle 5 domande Cluster 4:**

1. **Dati di affidabilità sistemica:** Nessun dato numerico sul sito (nessun "88% soddisfatti", nessun "300 interventi al giorno"). L'unico dato sistemico è il badge Trustpilot e il numero di stelle. Il Gruppo Facile.it in footer è l'unico proxy di scala. Non usa dati di performance — usa dati di soddisfazione delegati all'esterno.
2. **Recensioni aggregate come non-decorazione:** Il badge Trustpilot è l'unico contenuto della sezione trust — non è decorazione perché è l'intero messaggio. Il link "Collegati a TrustPilot" porta direttamente alle recensioni reali, non a una selezione curata. Efficace per chi clicca; invisibile per chi non cerca attivamente la prova.
3. **Certezza dell'outcome:** Non comunicata esplicitamente. La promessa più vicina è "saremo lì per te nel più breve tempo possibile" — vaga sulla metrica (nessun "entro 60 min"). La certezza reale emerge dalle recensioni ("mezz'ora"), non dal sito.
4. **Leva di fiducia principale vs ACI:** La comunicazione proattiva durante il servizio. Non la trasparenza pre-acquisto, non la tecnologia, non i dati: il centralino che richiama. ACI non comunica questa dimensione sul sito né sembra averla come comportamento operativo sistematico — o se ce l'ha, non la racconta.
5. **Brand autonomo vs brand proprietario:** Il Gruppo Facile.it è comunicato come legitimacy signal in footer (elenca tutti i brand noti del gruppo), non come garanzia istituzionale. AutoAssist non nasconde l'appartenenza al gruppo ma non la usa come promessa di qualità — usa il Trustpilot invece. La relazione emerge, non è nascosta né valorizzata strutturalmente.

---

#### AAA (US) — ✅ Completato

**Fonti:** analisi Cluster 1 (ace.aaa.com) riletta con lente Cluster 4

**Sintesi:** AAA costruisce il trust attraverso due meccanismi opposti a quelli di AutoAssist: heritage implicita ("legendary") senza dati, e metrica operativa concreta ("avg 4 min") su un canale specifico. Non usa recensioni aggregate né Trustpilot — si affida interamente alla brand recognition nazionale consolidata in decenni. Il rischio: funziona nel mercato USA dove AAA è un riferimento culturale; sarebbe fragile in un mercato dove il brand non è noto.

**Struttura trust sul sito:**

- **"Legendary 24-hour Roadside Assistance"** — il termine "legendary" evoca heritage senza citare anni o dati quantitativi. È l'unico claim di legacy dell'intero sito. Funziona perché AAA è fondata nel 1902 — ma quella storia non viene mai raccontata esplicitamente
- **"On average, requests take less than 4 minutes to make"** — metrica operativa dichiarata sul chatbot. È il trust signal più concreto del sito: trasforma un canale percepito come lento (chatbot) in una promessa misurabile. È certezza dell'outcome per il processo di segnalazione, non per i tempi di arrivo
- **Prezzi espliciti sul sito:** Classic $25 / Plus $56 / Premier $85/anno (first-year) — la trasparenza tariffaria contribuisce al trust pre-acquisto: l'utente sa esattamente cosa compra prima di impegnarsi
- **"Choose a plan" + "Compare benefit levels"** — il link comparativo riduce l'incertezza sulla scelta, costruisce fiducia nel processo decisionale
- **CTA emergenza sempre visibile:** bottone rosso "Get Roadside Assistance" in header + floating button — la doppia presenza ridondante comunica che il canale è sempre disponibile, creando un trust signal di accessibilità
- **Zero recensioni esterne:** nessun Trustpilot, nessun Google Reviews, nessun widget di social proof — scelta radicale che funziona solo con brand recognition forte

**Dati di affidabilità sistemica:** Assenti come numeri espliciti. "Legendary" e "24-hour" sono gli unici claim. Il trust è tutto di brand, niente di performance data. Contrasto netto con ADAC (Pannenhilfebilanz) e Europ Assistance (10+ MLN clienti, 200 paesi).

**Certezza dell'outcome:** Il chatbot "avg 4 min" è l'unico punto di certezza misurabile. Per i tempi di arrivo del soccorso: nessuna promessa esplicita. La membership differenziata per tier (Basic/Plus/Premier) implica che il Plus e il Premier offrano servizi più veloci — ma non viene dichiarato in termini di minuti.

**Brand proprietario:** AAA Northern New England (ACE) è un club regionale affiliato alla federazione AAA nazionale. La struttura federata non è comunicata esplicitamente — l'utente arriva su ACE ma il sito ha l'aspetto del brand nazionale AAA. Il logo nazionale dominante fa da garanzia istituzionale implicita senza che il rapporto regionale/nazionale venga spiegato.

**Risposte alle 5 domande Cluster 4:**

1. **Dati affidabilità sistemica:** Assenti come numeri. Solo "legendary" + "24h". Nessun dato di interventi, nessuna % soddisfazione. Fiducia di brand, non di performance.
2. **Recensioni aggregate:** Zero. Il trust è interamente di brand heritage. Non scalabile in mercati senza quella heritage.
3. **Certezza dell'outcome:** "Avg 4 min" per il processo digitale, nulla per i tempi fisici di intervento. Pricing trasparente costruisce certezza pre-acquisto.
4. **Leva principale vs ACI:** Brand recognition + pricing trasparente. Non replicabile direttamente da ACI (brand heritage diversa). Il pricing trasparente è invece un pattern trasferibile.
5. **Brand autonomo vs proprietario:** Brand federato gestito come unico — la struttura regionale è opaca. AAA nazionale fa da umbrella guarantee implicito.

---

#### ADAC (DE) — ✅ Completato

**Fonti:** analisi Cluster 1 + Cluster 2 (adac.de) riletta con lente Cluster 4

**Sintesi:** ADAC è il benchmark assoluto del Cluster 4 per i dati di affidabilità sistemica. Nessun altro player del benchmark pubblica dati operativi con la granularità del Pannenhilfebilanz (report annuale pubblico su ogni tipo di intervento) o della Pannenstatistik (quale auto si rompe di più su 100+ marche). Il trust non è costruito su testimonianze o rating — è costruito su trasparenza operativa certificabile. È il modello opposto ad AutoAssist: AutoAssist delega il trust ai clienti (Trustpilot), ADAC lo produce direttamente con i propri dati.

**Struttura trust sul sito:**

- **Pannenhilfebilanz** — report annuale con tutti i dati di intervento: numero di panne gestite, tipo di avaria, tempo medio di intervento, distribuzione geografica. Documento istituzionale pubblicato come contenuto pubblico, non come marketing. Chiunque può verificare i numeri. È trasparenza sistemica nel senso più letterale del termine
- **Pannenstatistik** — quale auto si rompe di più, su 100+ marche. Dati raccolti da tutti gli interventi ADAC in Germania. Non è un report su ADAC — è un servizio di informazione per gli automobilisti. Il trust si costruisce attraverso l'utilità editoriale dei dati, non attraverso la promozione del brand
- **Scala dichiarata:** "Il più grande club automobilistico d'Europa" — affermazione quantificabile e verificabile, non solo un claim emotivo
- **"Gelbe Engel" (angeli gialli)** come brand dei soccorritori: sezione dedicata con storia, flotta, dati. I tecnici non sono "operatori anonimi" — hanno un'identità di brand. Questo umanizza il servizio senza cedere alla logica individuale delle recensioni
- **SOS Nothilfe rosso in header persistente** — contrasto cromatico intenzionale sul giallo istituzionale. Il segnale d'urgenza è separato dal brand, riconoscibile a colpo d'occhio. Trust signal di accessibilità: "questo canale è sempre lì"
- **Zero rating esterni:** nessun Trustpilot, nessun Google Reviews — come AAA, il trust è interno. Ma a differenza di AAA, è documentato con dati propri, non con reputazione implicita

**Certezza dell'outcome:** Non comunicata come promessa ("entro X minuti") sul sito pubblico — ma il Pannenhilfebilanz include i tempi medi reali di intervento, che l'utente può verificare. È certezza documentata, non promessa.

**Brand proprietario:** ADAC è un'entità monolitica — non ha un parent brand separato. Il trust è tutto ADAC, nessuna dipendenza da un gruppo esterno. Questo è un vantaggio rispetto a EA (sotto Generali) o AutoAssist (sotto Facile.it): la fiducia non si divide tra brand operativo e brand proprietario.

**Risposte alle 5 domande Cluster 4:**

1. **Dati affidabilità sistemica:** Eccellenza assoluta. Pannenhilfebilanz + Pannenstatistik sono dati operativi pubblici e verificabili. Nessun altro player del benchmark pubblica qualcosa di comparabile.
2. **Recensioni aggregate:** Non usate. Il trust è costruito su dati operativi propri, non su rating di terze parti. Scelta coerente con il posizionamento istituzionale — un'istituzione non ha bisogno di conferme esterne.
3. **Certezza dell'outcome:** Documentata nel Pannenhilfebilanz (tempi medi reali), non promessa come claim marketing. Chi vuole la certezza la trova nei dati, non in uno slogan.
4. **Leva principale vs ACI:** Trasparenza operativa sistemica con dati propri. Pattern trasferibile per ACI: pubblicare dati reali sugli interventi (% risolti sul posto, tempo medio di arrivo, numero di partner rete, copertura geografica) — non come boast marketing ma come documentazione verificabile.
5. **Brand autonomo vs proprietario:** Monolitico. Nessun parent brand. Tutto il trust è concentrato nel brand ADAC — massima coerenza, massimo rischio di reputazione (un singolo scandalo colpisce l'intero sistema).

---

#### Airbnb (IT) — ✅ Completato

**Fonti:** airbnb.it · airbnb.it/aircover (redirect → help/article/3218) · listing campione Milano/Cervia

**Sintesi:** Airbnb costruisce il trust bottom-up: il guest si convince attraverso l'accumulo di segnali individuali (stelle, sottodimensioni, anni da host, tasso di risposta, recensioni narrative). La garanzia istituzionale (AirCover) è un safety net nascosto — non entra mai nel percorso di acquisto come elemento attivo. Il pattern più interessante per ACI non è AirCover ma la **scomposizione della fiducia in sottodimensioni**: invece di un unico punteggio aggregato, Airbnb mostra Pulizia / Precisione / Check-in / Comunicazione / Posizione / Qualità-prezzo separati — ogni dimensione misura un aspetto diverso dell'experience.

**Struttura trust sul sito:**

**AirCover — la garanzia nascosta:**
- Non compare in homepage (solo link testuale nel footer, secondo livello)
- Non compare nel listing nel flusso pre-acquisto
- Il redirect `/aircover` porta al Centro Assistenza (articolo help/3218) — è trattata come documentazione operativa, non come brand promise
- Tono procedurale: "documenta il problema, contatta l'host entro 72 ore, poi contattaci" — nessuna headline emozionale, nessuna metrica di affidabilità
- Escape clause: "in base alla disponibilità" — la promessa di riprenotazione introduce incertezza dove il guest si aspetta certezza istituzionale
- Nota legale: "AirCover per gli ospiti non costituisce una polizza assicurativa" — de-trust signal posizionato subito dopo le promesse
- **Conclusione:** AirCover è pensata come strumento post-problema, non come argomento pre-acquisto. La sua esistenza abbassa l'ansia solo per chi la cerca attivamente

**Sistema recensioni nel listing:**
- **Livello 1 — Punteggio sintetico:** "4,74 · 77 recensioni" immediatamente sotto il titolo, above the fold
- **Livello 2 — Distribuzione stelle:** 5★ 79% / 4★ 17% / 3★ 3% / 2★ 1% / 1★ 0% — granularità visibile ma sotto fold, in sezione separata
- **Livello 3 — Sottodimensioni:** Pulizia 4,7 / Precisione 4,8 / Check-in 5,0 / Comunicazione 5,0 / Posizione 4,7 / Qualità-prezzo 4,7 — permette di calibrare le aspettative per tipo di preoccupazione
- **Livello 4 — Tag semantici algoritmici:** "Ciclismo, Ospitalità, Spiaggia, Posizione, Muoversi in zona, Pulizia" — estratti automaticamente dal testo delle recensioni. Sintesi scannable senza richiedere lettura completa
- **Livello 5 — Recensioni narrative:** nome, anni da iscritto, stelle, testo — il trust diventa personale ("Giovanna è una host impeccabile")

**Trust signal sistemici vs individuali:**
- Badge "Amato dagli ospiti": visibile in 6/9 listing in homepage — ma privo di definizione esplicita della soglia. Rischio di ornamentalità
- "Host privato" vs "Host professionista": distinzione visibile come sottotitolo in ogni listing — tassonomia di tipo di relazione, non di verifica identità
- Tasso di risposta 100% + "risponde entro un'ora": metriche operative concrete — non promesse, dati comportamentali
- Durata iscrizione host ("7 anni da host"): segnale di longevità — nessun competitor rende questa metrica così visibile
- Nessun badge "identità verificata" esplicito nel corpo principale del listing

**Certezza dell'outcome:**
- Certezza data da metriche misurabili (Check-in 5,0 su 77 recensioni), non da promesse narrative
- "Cancellazione gratuita entro il giorno X" — specifica, datata, azionabile
- AirCover non garantisce certezza: "in base alla disponibilità" la rende condizionale

**Risposte alle 5 domande Cluster 4:**

1. **Dati affidabilità sistemica:** Stellari (aggregate) + sottodimensioni per listing individuale. Nessun dato di sistema aggregato tipo "X milioni di prenotazioni sicure" in homepage. Il trust sistemico è implicito (scala della piattaforma), non dichiarato.
2. **Recensioni non-decorazione:** Scomposizione in sottodimensioni + tag semantici + distribuzione stelle = strumento di calibrazione, non badge ornamentale. Ma il badge "Amato dagli ospiti" senza soglia dichiarata rischia di diventare rumore visivo per abitudine.
3. **Certezza vs promessa generica:** Metriche comportamentali concrete (tasso risposta, tempo risposta, sottodimensioni) > AirCover che è vaga e condizionale. La certezza reale viene dall'evidenza empirica, non dalla promessa istituzionale.
4. **Leva principale:** Scomposizione delle dimensioni del trust + segnali di longevità host. Non AirCover.
5. **Brand Airbnb vs host:** Il trust individuale dell'host (bio personale, anni di esperienza, recensioni per nome) è più presente e concreto del trust sistemico. I due piani non dialogano esplicitamente: manca un'interfaccia che dica "questo host ha passato X verifiche di sistema".

**Rilevanza per ACI:**
- **Sottodimensioni del trust:** ACI potrebbe scomporre la soddisfazione in dimensioni separate — Velocità di arrivo / Competenza tecnica / Cortesia operatore / Completezza risoluzione — invece di un unico Trustpilot aggregato. Ogni dimensione è misurabile e comunicabile
- **Tag semantici:** sintesi delle recensioni in etichette scannable, generabili algoritmicamente o manualmente su un campione
- **Longevità e metriche operative:** anni di attività, tasso di risoluzione first-time, tempo medio di risposta — resi visibili come dati, non come slogan

#### Booking.com — ✅ Completato

**Fonti:** booking.com (homepage IT) · booking.com/hotel/it/villa-madruzzo.it.html (listing campione: Hotel Villa Madruzzo, Trento — 4.538 recensioni, punteggio 9,3)

**Sintesi:** Booking.com è il benchmark assoluto del Cluster 4 per l'architettura sistemica della fiducia. Non costruisce il trust sul singolo hotel — lo costruisce sul sistema: 300 milioni di recensioni come dato concreto, 7 sottodimensioni per ogni listing, filtraggio per argomento e tipo di viaggiatore, "rimborso differenze di prezzo" come garanzia operativa. Il pattern chiave non è mostrare le recensioni — è trasformarle in **dati calibrabili**, non in opinioni generiche. Il guest non legge "ottimo hotel": legge Staff 9,7 / Pulizia 9,5 / WiFi 9,0 / Rapporto qualità-prezzo 9,1 — e decide in base alle dimensioni che contano per lui.

**Trust signals in homepage:**
- **"Oltre 300 milioni di recensioni dei viaggiatori"** — scala sistematica come dato concreto, non claim. Accompagnato da: "Approfitta di informazioni affidabili da ospiti come te" — frame peer-trust: la fonte è gli ospiti, non Booking
- **"Cancellazione GRATUITA per la maggior parte delle camere"** — risk reduction posizionata prima di qualsiasi prezzo — sequenza deliberata: prima elimina il rischio, poi mostra il costo
- **"Oltre 2 milioni di strutture"** — scale/choice signal
- **"Assistenza Clienti affidabile h24"** — disponibilità come promessa sistemica
- **"Rimborsiamo le differenze di prezzo"** — price guarantee riduce l'ansia post-acquisto

**Architettura trust nel listing (7 livelli):**

**Livello 1 — Punteggio sintetico con etichetta semantica:** "9,3 · Eccellente · 4.538 recensioni" — numero + label + count sempre insieme. Le label mappano range precisi: Punteggio medio → Buono → Ottimo → Favoloso → Eccellente → Eccezionale. L'etichetta rende il numero immediamente comparabile senza richiedere una scala di riferimento.

**Livello 2 — 7 sottodimensioni con decimali:**
- Staff 9,7 · Servizi 9,4 · Pulizia 9,5 · Comfort 9,5 · Rapporto qualità-prezzo 9,1 · Posizione 8,9 · WiFi gratuito 9,0
- Ogni dimensione è separatamente misurabile e confrontabile tra strutture. Il guest che prioritizza il WiFi guarda 9,0; il guest che prioritizza lo staff guarda 9,7. Il trust diventa contestuale al profilo.

**Livello 3 — Filtraggio recensioni per argomento:** "Seleziona gli argomenti: Colazione, Ristorante, Piscina, Posizione, Palestra" — le recensioni diventano un database interrogabile, non una lista da leggere linearmente. Riduce il costo cognitivo di raccogliere evidenza su una specifica preoccupazione.

**Livello 4 — Segmentazione per tipo di viaggiatore:** "Le coppie apprezzano molto la posizione: l'hanno valutata 8,9 per un viaggio a due" — i dati aggregati vengono re-segmentati per profilo. Un utente che viaggia da solo, in coppia o con famiglia vede il dato rilevante per sé.

**Livello 5 — "Clienti fedeli" come retention metric:** "Vanta più clienti abituali rispetto a molte altre strutture" — non solo soddisfazione (opinione), ma comportamento ripetuto (evidenza). Chi torna è un segnale più forte di chi è contento.

**Livello 6 — Review quotes above-fold:** 10 citazioni di recensioni reali mostrate prima dello scroll, con nome e paese d'origine — non una tab separata, non un link "vedi recensioni": sono nel body principale del listing, nella prima schermata.

**Livello 7 — FAQ generate da domande reali degli ospiti:** sezione "Domande dei viaggiatori" con 20+ domande effettivamente poste da altri ospiti — trasforma l'incertezza pre-acquisto in contenuto informativo strutturato.

**Trust sistemico vs trust individuale della struttura:**
Il sistema di rating è di Booking, applicato uniformemente a tutte le 2 milioni di strutture. L'ospite si fida del sistema Booking, non dell'hotel che si auto-descrive. La struttura non può alterare il punteggio — può solo rispondere alle recensioni. Questo è il modello opposto al sito hotel autonomo: la credibilità è dell'infrastruttura, non del singolo provider.

**Genius come trust amplifier:**
"Risparmia il 10% o più... Cerca l'etichetta blu di Genius" — il programma loyalty non è solo un incentivo economico: è un segnale di riconoscimento del profilo dell'utente ("so chi sei, ti tratto meglio"). Anche questo è trust: non l'affidabilità della struttura, ma la certezza che il sistema ti riconosce e ti dà valore aggiuntivo.

**Parent brand:**
"Booking.com è parte di Booking Holdings Inc." — dichiarato in footer. Non usato come trust argument in homepage: il trust di Booking non ha bisogno del parent perché è costruito direttamente sul volume dei dati propri. Un segnale di brand maturity: il parent non aggiunge credibilità, il prodotto parla da solo.

**Risposte alle 5 domande Cluster 4:**

1. **Dati affidabilità sistemica:** Eccellenza assoluta. "300 milioni di recensioni" in homepage come dato numerico preciso. 7 sottodimensioni per ogni listing. Scala e precisione combinate: il trust è documentato, non dichiarato.
2. **Recensioni non-decorazione:** Il filtraggio per argomento e la segmentazione per tipo di viaggiatore trasformano le recensioni da opinioni passive a strumento di ricerca attiva. Non si "leggono" le recensioni su Booking — le si usa.
3. **Certezza dell'outcome:** "Cancellazione gratuita" + "Rimborso differenza prezzo" + sottodimensioni a decimali = certezza operativa multi-livello. Non è una promessa generica: è un sistema di riduzione del rischio stratificato.
4. **Leva principale:** Il sistema di rating come infrastruttura di fiducia, non il singolo provider. 300M recensioni + 7 dimensioni + filtraggio = la fiducia è nel database, non nell'hotel.
5. **Brand Booking vs proprietario:** Il brand Booking è dominante — la struttura ospitata è secondaria. Il trust si trasferisce dalla piattaforma alla struttura, non il contrario. Booking Holdings non compare come argomento: il brand Booking è già abbastanza forte da soli.

**Rilevanza per ACI:**
- **Scala come dato:** comunicare "88% degli interventi risolti sul posto" o "tempo medio di arrivo X minuti" non come marketing ma come dato concreto con fonte verificabile
- **Sottodimensioni del trust:** scomporre il feedback clienti in assi separati (velocità, cortesia, completezza risoluzione, comunicazione durante l'attesa) invece di un unico rating aggregato
- **Certezza operativa stratificata:** non solo una promessa di qualità ma meccanismi specifici che riducono il rischio (garanzia rimborso, cancellazione, SLA dichiarati)
- **Recensioni come database, non vetrina:** filtraggio per tipo di problema (guasto batteria vs incidente vs foratura) invece di una lista cronologica

---

### Cluster 5

#### Europ Assistance (IT) — ✅ Completato

**Fonti:** analisi Cluster 1 + Cluster 3 (europassistance.it · sodauto.europassistance.it) riletta con lente Cluster 5

**Sintesi:** Europ Assistance è il caso di studio più diretto per ACI Global sul tema del brand ombrello: è un sub-brand con identità autonoma all'interno del Gruppo Generali, con un parent brand fortissimo che però non appare esplicitamente sul sito consumer. La coppia **Generali → Europ Assistance è l'analogo strutturale esatto di Sara → ACI Global Servizi** (assicuratore che possiede il brand operativo di assistenza) — con una differenza: nel caso ACI il nome del sub-brand appartiene a un ente terzo (Automobile Club d'Italia), mentre EA è interamente di Generali. Il finding principale per il Cluster 5 è la **frammentazione interna non comunicata**: due siti distinti (europassistance.it + sodauto.europassistance.it), due entità giuridiche (EA Italia + EA VAI), due numeri verdi diversi — tutto visibile all'utente come confusione non intenzionale, non come architettura deliberata.

**Gestione del brand ombrello:**
- **Generali come parent invisibile:** Il logo Generali non compare in homepage di europassistance.it. Il link "Il gruppo Generali" esiste solo nel footer in basso, non valorizzato come garanzia istituzionale. La scelta è di costruire il trust sul brand Europ Assistance, non sul parent — coerente con la logica di sub-brand autonomo, ma perde l'opportunità di usare la garanzia Generali come anchor di credibilità
- **Rebrand a "Redion"** in corso (notice su ogni pagina): il passaggio da Europ Assistance a Redion introduce un momento di instabilità identitaria — il brand costruito in decenni viene dismesso, la fiducia accumulata si azzera. Timing critico per chi sta analizzando il sito

**Separazione B2C / B2B:**
- **Assente nel sito consumer:** europassistance.it non ha una sezione flotte/aziende accessibile dalla navigazione principale. L'area B2B è delegata a Europ Assistance VAI S.p.A., entità separata menzionata solo in footer e note legali delle pagine Mobilità
- **Nessun switch audience in navigazione:** nessun toggle "Sei un'azienda?", nessun link "Soluzioni per le flotte", nessun percorso parallelo. Il cliente business che arriva sul sito consumer non trova nessun punto di ingresso

**Scalabilità dell'offerta (beyond mobility):**
- EA comunica la multi-verticalità attraverso la navigazione top-level: Assicurazioni (Viaggi / Casa / Salute / Mobilità). La mobilità è una delle quattro categorie, non il core. Ma l'hero è un configuratore viaggi — la prima cosa che vede il visitatore è Viaggi, non Mobilità. Chi cerca l'assistenza stradale deve cliccare sul quarto tab
- Il modello cross-selling (possiedi viaggi + casa + salute sotto un solo ombrello) è implicito nella navigazione ma non esplicitato come "ecosistema"

**Frammentazione interna come anti-pattern:**
Il caso EA è l'anti-pattern esatto del Cluster 5: due siti distinti non linkati dalla homepage principale, due entità giuridiche separate, due numeri verdi, un rebrand in corso che crea incertezza identitaria, un parent brand (Generali) che potrebbe essere una garanzia ma viene nascosto. Il cliente che interagisce con EA Italia per la polizza e EA VAI per il soccorso non sa di stare trattando con due entità diverse della stessa struttura.

**Risposte alle 4 domande Cluster 5:**
1. **Brand ombrello + entità multiple:** EA gestisce la molteplicità nascondendo la complessità al cliente (non c'è mappa dell'ecosistema) — ma questo genera confusione pratica (due numeri verdi, due siti). Modello opposto a Revolut che esplicita i percorsi nella navbar
2. **B2C vs B2B senza duplicare:** Non separati — il B2B non esiste nel sito consumer. Caso peggiore del benchmark su questo punto
3. **Scalabilità offerta:** Quattro tab di prodotto in navigazione ma nessuna narrative "siamo un ecosistema completo" — la breadth è presente, non comunicata
4. **Differenziazione B2B:** Assente. EA VAI non è mai presentata come valore per le aziende nel sito consumer

---

#### Generali (IT) — ✅ Completato

**Fonti:** generali.it (homepage + /business redirect test)

**Sintesi:** Generali Italia è il caso di studio del parent brand che ha scelto di **assorbire i sub-brand nella propria identità** invece di orchestrarli. Genertel, GenertelLife, Cronos Vita, Cattolica — tutte le entità che erano brand separati — sono ora "Prodotti a brand Cattolica", "Ex Cronos Assicurazioni Vita" nel footer. Il Gruppo Generali non compare in homepage come argomento di trust: la garanzia istituzionale è tutta di Generali Italia, il parent è un link nel footer. Europ Assistance non viene mai menzionata.

**Gestione del brand ombrello:**
- **Modello "assorbimento":** invece di orchestrare sub-brand autonomi (modello EA), Generali Italia ha unificato tutto sotto un brand nazionale. I 17+ avvisi legali di fusione/scissione visibili nella homepage sono la traccia pubblica di questo processo — ogni avviso è un confine societario che viene eliminato
- **"Il Gruppo Generali"** appare solo come link nel footer — non come argomento di homepage. La scelta è deliberata: il trust è tutto su Generali Italia, il gruppo internazionale non viene usato come amplificatore (sarebbe coerente invece con chi cerca la scala globale come garanzia)
- **Sub-brand residuali nel footer:** "Prodotti a brand Cattolica", "Prodotti ex partner GenertelLife", "Ex Cronos Assicurazioni Vita" — tracce del passato mantenute per la continuità contrattuale dei clienti, non come brand autonomi vivi. L'etichetta "ex" e "a brand" segnala che l'identità è in fase di transizione o conclusa

**Separazione B2C / B2B:**
- **"Business" come tab nel product browser, non come sezione separata:** la navigazione principale è "Assicurazioni / Assistenza e Sinistri / Iniziative e Vantaggi" — non contiene "Business". Il tab Business appare dentro il product browser ("Trova l'assicurazione su misura per te: Privati | Business | In evidenza | Auto e Mobilità..."). È una categoria di prodotto, non un percorso di audience separato
- **URL /business redirige all'homepage:** non esiste una pagina Business dedicata — il tab è un filtro del catalogo prodotti della homepage, non una landing page autonoma
- **Implicazione:** chi è un'azienda e cerca la sezione Business arriva sulla stessa homepage dei privati e deve individuare il tab — non c'è un percorso dedicato, non c'è una promessa separata

**Scalabilità dell'offerta:**
- L'hero è una hero di navigazione per tipo di prodotto (Auto e Mobilità / Casa, Salute e Famiglia / Previdenza) — copre quattro grandi aree di vita. La scalabilità è comunicata dalla breadth delle categorie, non da una narrative esplicita
- "11 milioni di clienti" + "800 mila strutture convenzionate" + "22 mila consulenti" — scala come dato numerico in homepage, posizionato sotto la hero
- Il multi-prodotto non ha una narrative "ecosistema" o "accompagniamo tutta la tua vita" — è un catalogo, non un viaggio

**Rilevanza diretta per ACI Global Servizi:**
La mappatura corretta dell'ecosistema post-acquisizione è: **Sara Assicurazioni = il parent assicurativo che ha acquisito il braccio operativo** (posizione di Generali), **ACI Global Servizi = il sub-brand operativo di assistenza** (posizione di Europ Assistance), **ACI / Automobile Club d'Italia = ente istituzionale terzo e separato** — non più proprietario dell'operativo: incassa il bollo, emette le tessere soci e di fatto concede il proprio nome storico al brand operativo. Generali offre quindi due lezioni a **Sara** (non ad ACI): (1) la scelta strategica assorbimento vs orchestrazione — Sara potrebbe fondere ACI Global in un brand "Sara Assistance/Mobilità" oppure mantenerlo come sub-brand autonomo con il nome ACI; (2) il costo dell'unificazione — anni di comunicazione legale esplicita (17+ avvisi di fusione in homepage) e gestione attiva della transizione. **Differenza chiave rispetto a Generali:** il nome "ACI" non è un sub-brand che Sara possiede e può assorbire, ma il marchio di un ente pubblico distinto — quindi per Sara l'**orchestrazione** (mantenere ACI Global come sub-brand riconoscibile) è il percorso vincolato, non l'assorbimento.

**Risposte alle 4 domande Cluster 5:**
1. **Brand ombrello + entità multiple:** Modello assorbimento — i sub-brand vengono progressivamente eliminati, non orchestrati. La complessità viene ridotta, non gestita
2. **B2C vs B2B:** Business come tab nel product browser — non separato. Strutturalmente simile ad ACI Global oggi (nessun percorso B2B dedicato)
3. **Scalabilità:** Hero per categoria prodotto + dati di scala numerici. Non c'è narrative "viaggio dell'utente" o "tutto sotto un tetto"
4. **Differenziazione B2B:** Assente come percorso separato — Business è un filtro del catalogo, non un'area autonoma

---

#### AAA (US) — ✅ Completato

**Fonti:** analisi Cluster 1 + Cluster 4 (ace.aaa.com) riletta con lente Cluster 5

**Sintesi:** AAA è il modello di ecosistema multi-servizio più sviluppato tra i competitor diretti: soccorso stradale + assicurazioni auto/casa/vita + viaggi + banking + sconti consumer, tutto sotto un brand. Il paradosso strutturale è che questo ecosistema vasto è gestito da una struttura federata di club regionali autonomi — e questa federazione è quasi completamente opaca per l'utente finale.

**Gestione del brand ombrello multi-servizio:**
- Il sito ACE (Northern New England) presenta tutti i servizi AAA come un pacchetto membership unificato — non come prodotti separati con brand separati. L'utente non sa che "AAA Insurance" è una divisione separata da "AAA Roadside" — vede solo "membership" che include tutto
- Il doppio header (top bar navy per azioni urgenti + nav bar bianca per categorie) è la soluzione architettonica: la struttura federata è invisibile, la navigazione è per tipo di servizio (Roadside / Insurance / Travel / Finance / Automotive)
- **Federazione nascosta:** il sito appare come un brand unitario AAA — ma il club regionale (ACE/Northern New England) è l'entità reale. Il national brand AAA è un umbrella che standardizza il look&feel ma ogni club è indipendente nei prezzi, nelle coperture, nella rete di partner. Un utente che si sposta da un club regionale all'altro trova lo stesso sito con prezzi diversi — senza essere avvertito

**Separazione B2C / B2B:**
- **Assente strutturalmente:** la membership AAA è individuale. "Group membership" compare come opzione nella pagina membership ("Boost the value of your organization's benefits package") ma è un accenno, non un percorso separato con SLA, fleet management, rendicontazione
- La voce "Become a participating business" nel footer riguarda esercizi commerciali che vogliono aderire al programma sconti AAA come partner — non aziende con flotte

**Scalabilità dell'offerta:**
- La navigazione mostra: Roadside / Insurance / Travel / Finance / Automotive — 5 macro-aree visibili
- Il posizionamento è quello della membership: "con la tua membership AAA hai accesso a tutto questo". La scalabilità è la proposta di valore principale, non una complicazione
- L'ecosistema è comunicato come "valore dell'iscrizione", non come "molti prodotti diversi" — questa è la differenza narrativa rispetto a Generali che usa un catalogo

**Risposte alle 4 domande Cluster 5:**
1. **Brand ombrello + entità:** Unificazione narrativa sotto "membership" — i servizi multipli diventano benefici di una sola iscrizione. La federazione regionale è nascosta. Modello efficace per il B2C; fragile per chi si sposta geograficamente
2. **B2C vs B2B:** B2B assente come percorso strutturato. Anti-pattern diretto per ACI che ha un'esigenza reale di fleet/aziende
3. **Scalabilità:** "Tutto incluso nella membership" — la breadth è la promessa di valore, non un rischio di confusione. Modello narrativo trasferibile
4. **Differenziazione B2B:** Assente. "Group membership" è un accenno che non scala

---

#### ADAC (DE) — ✅ Completato

**Fonti:** analisi Cluster 1 + Cluster 2 + Cluster 4 (adac.de) riletta con lente Cluster 5

**Sintesi:** ADAC è l'ecosistema multi-servizio più esteso del benchmark — mobilità, viaggi, assicurazioni, salute, media editoriale, 4 app distinte — gestito come un portale media con il soccorso stradale come beneficio incluso, non come prodotto principale. Come AAA, ha zero B2B fleet strutturato. La differenza rispetto ad AAA è che ADAC non nasconde la complessità: la espone come ecosistema editoriale e lascia all'utente il compito di orientarsi.

**Gestione del brand ombrello multi-servizio:**
- **Modello media/portale:** la homepage ADAC è una griglia editoriale con sezioni Produkte, Videos, Rund ums Fahrzeug, Gesundheit, Motorrad — non è organizzata per tipo di utente o di bisogno, ma per topic editoriale. È il modello del magazine, non dell'app
- La complessità è visibile e accettata: 7 voci di navigazione primaria, 4 app distinte (Pannenhilfe App, Medical App, Drive App, Trips App). L'ecosistema è esplicito, non nascosto
- L'unificazione avviene attraverso il brand visivo (giallo-nero istituzionale) e la membership come accesso unificato — stessa logica di AAA ma con una presentazione più frammentata

**Separazione B2C / B2B:**
- **Assente strutturalmente:** nessuna sezione flotte/aziende nel nav. La pagina "Infos für Geschäftspartner" nel footer è per fornitori di ADAC (procurement), non per clienti business
- ADAC è un club consumer per definizione — la membership è individuale. Non esiste un'offerta B2B fleet

**Scalabilità dell'offerta:**
- La navigazione top-level mostra tutto: Mobilität / Alltagsthemen / Reise & Freizeit / Motorsport / ADAC. Ogni sezione è una macro-area dell'ecosistema
- L'eccesso di scelta è il principale punto critico del sito: chi cerca solo il soccorso stradale deve orientarsi in un portale media vastissimo. La CTA "SOS Nothilfe" rossa nell'header è l'unica scorciatoia — senza di essa, chi è in panne dovrebbe navigare nel magazine

**Modello di scalabilità per ACI:**
Il modello ADAC mostra cosa succede quando l'ecosistema cresce senza un'architettura informativa che lo governa: il sito diventa un portale media che soddisfa molti bisogni ma non guida nessuno. Per ACI l'implicazione è che la scalabilità (beyond automotive) richiede un'architettura di navigazione deliberata che preservi l'accesso diretto al servizio core anche quando il catalogo si espande.

**Risposte alle 4 domande Cluster 5:**
1. **Brand ombrello + entità:** Modello portale — tutto sotto ADAC, nessun sub-brand visibile. La complessità è gestita dal brand, non dall'architettura. Funziona grazie all'enorme brand recognition tedesca
2. **B2C vs B2B:** B2B assente strutturalmente — non è la proposta di ADAC
3. **Scalabilità:** Presente ma non governata — 7 sezioni, 4 app, magazine editoriale. La SOS rossa è l'ancora di orientamento per l'urgenza
4. **Differenziazione B2B:** Assente

---

#### Revolut — ✅ Completato

**Fonti:** revolut.com/it-IT/ (homepage consumer) · revolut.com/it-IT/business/ (Revolut Business) — scraping diretto + analisi agente

**Sintesi:** Revolut è il benchmark del Cluster 5 per l'architettura di switch Personal/Business sotto brand unificato. La separazione è strutturale ma non percettiva: stesso dominio, stesso logo, stessa navbar — ma autenticazione separata, pricing separato, feature set separato, prove sociali separate. Il pattern chiave è la **navbar come punto unico di biforcazione**: "Personale | Business | Giovani | Società" è il primo elemento di navigazione, sempre visibile, che dichiara l'esistenza di più audience senza costringere nessuno a scegliere prima di entrare.

**Architettura Personal/Business:**
- **Stesso dominio, namespace separato:** /it-IT/ (consumer) + /it-IT/business/ (B2B) — nessun sub-dominio separato. La scelta preserva la brand authority del dominio principale e rende evidente che si tratta della stessa entità
- **Logo invariante:** "Revolut" punta sempre a /it-IT/ (consumer root) in entrambe le pagine. Nessun badge "Business", nessun cambio colore — il brand è uno solo. La separazione è di contenuto, non di identità visiva
- **Autenticazione separata** (l'unica biforcazione tecnica visibile): Consumer → app.revolut.com/start / Business → revolut-business.onelink.me (deeplink mobile). Due stack di prodotto distinti sotto un brand unico

**La navbar come architettura di orientamento:**
"Personale | Business | Giovani | Società" — 4 audience/profili separati in primo piano nella navbar, sempre visibili. Non è un dropdown, non è un footer link: è il primo livello di navigazione. Il visitatore non deve capire da sé a quale prodotto appartiene — la struttura glielo dice subito. Questo è il pattern trasferibile per ACI: una navbar che dichiara i percorsi ("Privati | Aziende | Soci ACI") prima di qualsiasi contenuto.

**Separazione B2C / B2B:**
- Consumer enfatizza: vita quotidiana (stipendio, risparmi, investimenti, crypto, carte), pricing da gratuito a €55/mese (5 piani)
- Business enfatizza: workflow operativi (pagamenti globali, multi-currency, carte aziendali, expense management, BillPay, API, integrazioni contabili), pricing da €10/mese a Enterprise personalizzato (4 piani)
- **Prove sociali differenziate:** Consumer: "4 milioni di persone in Italia", "app bancaria più scaricata" / Business: "centinaia di migliaia di aziende leader", "20.000 nuove aziende al mese", testimonial con nome + ruolo + azienda (Massimo Grossi CEO Kel12, Elena Giombelli CFO WeRoad)
- **SLA dichiarato solo sul B2B:** "servizio clienti italiano 24/7" compare nella pagina Business, non in quella consumer — la certezza operativa è un valore B2B, non consumer

**Complessità nascosta con progressive disclosure:**
Hero: 4 use case operativi semplici. Footer: navigazione estesa per settore verticale (Viaggi, E-commerce, Agenzie marketing, Tecnologia e IA), per funzione (API, Esercente, Tesoreria, Revolut People HR), per tipo prodotto. La profondità è accessibile ma non imposta.

**Gap: assenza di upgrade path:**
Non esiste un messaggio esplicito "Sei già cliente Revolut Personal? Aggiungi Business". Il cross-selling avviene via canale sales ("Parla con l'ufficio vendite" come secondo CTA nella hero Business) — implicito che la transizione sia assistita, non self-service. Questa è la lacuna principale del modello Revolut per l'ecosistema.

**Rilevanza per ACI:**
- **Navbar come biforcazione:** "Privati | Aziende" (o "B2C | B2B Fleet") come primo elemento di navigazione — non nel footer, non in un dropdown secondario
- **Prove sociali differenziate per audience:** ACI può usare dati consumer (soddisfazione privati, velocità intervento) separati dai dati B2B (SLA fleet, rendicontazione, volume contratti aziendali)
- **Prezzi trasparenti anche sul B2B:** Revolut mostra i piani Business con prezzi in homepage — non richiede "contatta il commerciale" per capire l'ordine di grandezza

**Risposte alle 4 domande Cluster 5:**
1. **Brand ombrello + entità:** Navbar come primo punto di biforcazione — 4 profili dichiarati. Brand unico, contenuto separato. Il modello più chiaro del benchmark per gestire audience multiple
2. **B2C vs B2B senza duplicare:** Stesso dominio, namespace distinti, autenticazione separata. Nessuna duplicazione di infrastruttura, separazione netta di percorso
3. **Scalabilità offerta:** Progressive disclosure — hero semplice + footer esteso. La complessità è accessibile ma non in primo piano
4. **Differenziazione B2B:** Pricing separato, feature set separato, prove sociali separate, SLA dichiarati solo per B2B. Il benchmark più completo del cluster su questo punto

#### Amazon (IT) — ✅ Completato

**Fonti:** amazon.it (homepage B2C) · amazon.it/business (landing B2B) · business.amazon.it (portale B2B autonomo)

**Sintesi:** Amazon è il caso più istruttivo per la tensione tra brand ombrello e percorsi separati: il B2B ("Amazon Business") ha un logo distinto, un dominio separato e una navigazione autonoma — ma dall'homepage B2C è accessibile **solo dal footer**, con zero prominenza nella navigazione principale. Il modello è l'opposto di Revolut: invece di dichiarare i percorsi nella navbar, Amazon sceglie di tenere il B2B quasi nascosto dal B2C, confidando che chi ha bisogno dell'account business lo cerchi attivamente.

**Architettura B2C / B2B:**
- **Tre livelli distinti:** amazon.it (B2C, navigazione per categorie merceologiche) → amazon.it/business (landing intermedia con segmentazione per dimensione: Libero professionista / PMI / Grande azienda) → business.amazon.it (portale B2B con dominio separato, nav autonoma, identità visiva distinta)
- **Logo differenziato:** B2C: freccia-sorriso arancione standard / Business: "amazon business" con icona valigetta arancione al posto della freccia. Il sottomarchio è riconoscibile come figlio di Amazon ma visivamente distinto
- **Nessun switch in navbar:** il percorso B2B appare sul sito consumer solo nel footer (voce "Amazon Business" in fondo alla pagina, sezione "Metodi di pagamento Amazon" e sezione "Guadagna con Amazon"). Un utente che non scorra fino in fondo non trova nessun rimando al B2B durante la navigazione normale

**Separazione B2C / B2B:**
- **Catalogo non duplicato:** Amazon Business usa lo stesso inventario di amazon.it con filtri aggiuntivi (prezzi IVA esclusa, sconti quantità). La separazione è di account, funzionalità e navigazione — non di prodotto
- **Account separato obbligatorio:** registrazione distinta con work email — non è un toggle sull'account consumer. Questo è sia un barrier to entry che un segnale di serietà per il B2B
- **Gerarchia asimmetrica:** dal B2C il B2B è in footer (bassa prominenza). Dal B2B nessun retro-link verso il consumer. I percorsi sono paralleli e non si incrociano attivamente

**Scalabilità dell'offerta — organizzazione per outcome vs categoria:**
- **B2C:** navigazione per categoria merceologica (30+ categorie nella nav bar, caroselli per categoria in homepage). La profondità del catalogo non viene comunicata — si naviga
- **B2B:** navigazione per outcome funzionale: Soluzioni (9 voci: approfondimenti spese, integrazioni sistemi, gestione conformità, acquisti all'ingrosso, opzioni pagamento...) + Settori (7 verticali: istruzione, ospitalità, sanità, non profit, finanziari, PA, manifattura) + Dimensione (PMI / Grandi imprese). La stessa ampiezza di catalogo è comunicata come "cosa ottengo" invece di "cosa compro"
- **300+ integrazioni sistemi** (Coupa, Concur, SAP Ariba): la scalabilità B2B è dimostrata dalla profondità delle integrazioni, non dal numero di prodotti

**Differenziazione B2B esplicita:**
- Prezzi al netto IVA (rilevante per contabilità aziendale italiana)
- **Fattura elettronica automatica** — verbatim: "Ricevi in automatico le fatture elettroniche per i tuoi ordini e archivia tutte le fatture direttamente nel tuo account" — posizionata come benefit primario per il mercato IT (obbligo legale B2B)
- Account multi-utente con flussi approvativi, soglie di spesa, conformità centralizzata
- Spedizione gratuita da €29 (stessa soglia B2C ma comunicata separatamente come vantaggio B2B)
- Nessun SLA esplicito differenziato per tier — la differenziazione è su funzionalità procurement, non su tempi di risposta o garanzie contrattuali

**Tone of voice:**
- B2C: "Non è uno scherzo: tutto sotto i 10€", "Rinnova la tua casa con meno di 20€", "Haul: grandi scoperte"
- B2B: "Il futuro smart degli acquisti aziendali", "Semplifica i tuoi acquisti con strumenti innovativi", "Amazon Business aiuta milioni di clienti in tutto il mondo a riadattare il modo di fare acquisti per l'azienda"
- Due toni radicalmente diversi sotto lo stesso brand

**Risposte alle 4 domande Cluster 5:**
1. **Brand ombrello + entità:** Sottomarchio "Amazon Business" con logo distinto e dominio separato — né completamente nascosto né completamente autonomo. La relazione con il brand parent è evidente nel nome, non nel sito
2. **B2C vs B2B senza duplicare:** Footer sul B2C → landing intermedia → portale autonomo. Il catalogo è condiviso, la navigazione è separata. Nessuna duplicazione di inventario
3. **Scalabilità:** B2C per categoria, B2B per outcome. Il modello "navigazione per outcome" è il pattern più trasferibile del cluster per ACI (pagine servizio organizzate per bisogno dell'azienda, non per nome del prodotto)
4. **Differenziazione B2B:** La più completa del cluster: pricing separato, fatturazione separata, account separato, integrazioni 300+ sistemi, segmentazione per verticale (7 settori) e dimensione (3 tier). Il limite: nessun SLA esplicito

**Rilevanza per ACI:**
- **Sottomarchio dedicato per il B2B** — non una pagina nella nav principale ma un brand separato riconoscibile come figlio del parent (come "ACI Fleet" o "ACI Business" potrebbe fare lo stesso lavoro di "Amazon Business")
- **Organizzazione per outcome funzionale** — "Gestione interventi fleet", "Rendicontazione", "SLA garantiti" invece di "Piano Aziende"
- **Segmentazione per dimensione** — Libero professionista / PMI / Grande azienda come punti di ingresso separati che portano a contenuti diversi (stessa struttura che potrebbe fare: Taxi/NCC, Flotta aziendale, Ente pubblico)

---

## Passaggio 5 · Sintesi dei pattern

> **Tesi in una frase:** il benchmark non chiede ad ACI Global di "fare un sito più bello", ma di rendere visibili sul sito tre cose che oggi accadono (o potrebbero accadere) altrove — la fiducia che si genera durante il servizio, la certezza dell'attesa, e la chiarezza tra le entità del gruppo — convertendole da fatti operativi nascosti in contenuto strutturale.

Le analisi dei 16 player attraverso i 5 cluster si sintetizzano nei tre livelli prescritti dal metodo (cfr. [04-benchmark.md](04-benchmark.md), Passaggio 5): **pattern trasversali** (cosa emerge da tutti o dalla maggioranza, in positivo e in negativo), **pattern applicabili al progetto** (cosa importare e perché, ancorato agli insight), **opportunità distintive** (cosa nessuno fa bene e che ACI può rendere differenziante). A valle: scelte strategiche aperte, matrice di riferimento, priorità per ROI.

---

### 5.1 · Pattern trasversali

_Cosa emerge dalla maggioranza dei player — i comportamenti condivisi dai più maturi e gli errori che si ripetono._

**Positivi ricorrenti (cosa fanno i player maturi):**
- **Trust con dati propri verificabili, non slogan** — i leader pubblicano numeri: ADAC (Pannenhilfebilanz, Pannenstatistik), Booking ("300 milioni di recensioni"), Europ Assistance ("10+ mln clienti, 200 paesi"). La fiducia è documentata, non dichiarata.
- **Emergenza separata strutturalmente** — layer e colore distinti dal resto: AAA (top-bar navy + CTA rossa + floating button), ADAC (SOS rossa persistente sul giallo del brand).
- **App come canale primario, non alternativo** — il tracking e il servizio completo vivono nell'app; il web è spesso una brochure (Uber, Glovo, RAC, AA, ADAC).
- **Trust scomposto in sottodimensioni** — il punteggio unico è superato: Booking (7 assi a decimali), Airbnb (6 sottodimensioni + longevità host).
- **HTML-first per il contenuto commerciale** — Iliad e Lemonade tengono incluso/escluso, prezzi e persino il documento di polizza in HTML; il PDF resta solo per la compliance.
- **Progressive disclosure su audience multiple** — hero semplice + profondità nel footer/navbar (Revolut, Amazon): la complessità è accessibile ma non imposta.

**Negativi ricorrenti (opportunità mancate da quasi tutti — seedbed delle opportunità distintive):**
- **Empatia situazionale assente** — quasi nessun player riconosce la condizione di chi è in panne/in stress. ADAC, EA, AA hanno tono istituzionale o efficiente, mai empatico nel momento. Ricorre in ogni analisi di categoria.
- **B2B/fleet assente nella categoria soccorso** — ADAC, AAA, EA, AutoAssist: o assente o un accenno ("Group membership"). Un percorso B2B reale esiste solo nei cross-settore (Revolut, Amazon).
- **Il tracking crolla sull'attesa eccezionale** — RAC mostra l'ETA ma non spiega i ritardi (→ frustrazione); AA e ADAC attivano il tracking "poco prima dell'arrivo". Lo strumento che dovrebbe rassicurare aumenta l'ansia proprio quando l'attesa si allunga.
- **Trust sistemico e individuale non dialogano** — Airbnb stesso lo nota: manca un'interfaccia che colleghi il dato di sistema all'identità/affidabilità del singolo operatore.
- **Parent brand nascosto invece che usato come garanzia** — EA nasconde Generali, AutoAssist non valorizza Facile.it. La garanzia istituzionale resta un link nel footer.
- **Post-intervento debole o assente** — feedback loop inaffidabile (Glovo: supporto evasivo) o nessun prompt di rating strutturato (AA, RAC, ADAC). La relazione si chiude con l'intervento.

---

### 5.2 · Pattern applicabili al progetto

_I sei pattern che ricorrono in più cluster e che conviene importare nel redesign — ognuno ancorato a un insight di progetto._

#### Pattern 1 — La fiducia si costruisce durante il servizio; il sito la documenta, non la promette
**Cosa dice il benchmark.** Il paradosso AutoAssist (Trustpilot 4,3 vs ACI 1,9 con un sito di 3 pagine, zero prezzi, zero sistema d'emergenza digitale) dimostra che il gap di fiducia di ACI **non nasce primariamente dal sito**: nasce nell'operatività. La leva reale di AutoAssist è la comunicazione proattiva durante l'attesa ("mi hanno chiamato più volte assicurandosi che…"). Sul versante opposto, ADAC e Booking mostrano l'altra metà: la fiducia *sistemica* si costruisce con dati propri verificabili (Pannenhilfebilanz; "300 milioni di recensioni"), non con slogan.
**Chi lo incarna.** AutoAssist (trust comportamentale, post-esperienza) · ADAC (trust documentale: dati operativi pubblici) · Booking (trust infrastrutturale: il sistema, non il singolo provider).
**Azione ACI.** Due mosse complementari: (1) **rendere il comportamento una promessa esplicita** — "ti richiamiamo noi durante l'attesa", non aspettare che il cliente solleciti; (2) **pubblicare i dati di affidabilità come documentazione**, non come marketing — 88% soddisfazione, 300 operatori h24, 1.800 partner, 32 Paesi, 10 mln di minuti gestiti, con fonte e data. ACI ha già i numeri di ADAC senza pubblicarli come ADAC.

#### Pattern 2 — Certezza, non velocità: l'attesa va raccontata con segnali ridondanti
**Cosa dice il benchmark.** Insight utente: si accettano attese lunghe se prevedibili; a frustrare è la *revisione ripetuta* delle stime (RAC: "after a 6hr wait… now 11-2am" → 2★). I best-in-class del tracking sovrappongono più segnali simultanei: Glovo (mappa live + ETA dinamica + 6 stati verbali + push), Uber (gli stessi + RideCheck proattivo). I competitor di categoria sono indietro ma in movimento: ADAC e AA attivano il tracking solo "poco prima dell'arrivo" (finestra di silenzio iniziale), AA dichiara "twice as fast as calling" con ragione tecnica (GPS).
**Chi lo incarna.** Uber/Glovo (gold standard cross-settore) · ADAC/AA (categoria, tracking parziale) · AutoAssist (la versione *umana* dello stesso principio: il richiamo proattivo).
**Azione ACI.** Posizionamento sulla **certezza** (S2): tracking dell'operatore dal momento dell'assegnazione (non dall'ultimo tratto), ETA + stato verbale + push, e — dove il tracking tecnico manca — il richiamo proattivo come fallback umano. Mai una promessa di minuti che il sistema possa smentire.

#### Pattern 3 — Trasparenza strutturale: HTML per il servizio, PDF solo per la legge
**Cosa dice il benchmark.** È il reclamo #1 di ACI (condizioni non dichiarate: sovrapprezzi, km, orari, limiti). Iliad e Lemonade sono lo standard: contenuto commerciale interamente in HTML (incluso/escluso, overage pricing, persino il documento di polizza in Lemonade Policy 2.0), PDF riservato alla sola compliance. ConTe è il **gemello strutturale di ACI** (prezzo variabile per profilo, preventivo obbligato per legge IVASS) e mostra il compromesso realistico: garanzie accessorie in HTML esplorabili *prima* del preventivo. Europ Assistance SOD dimostra che nell'assistenza stradale un **prezzo fisso visibile in hero** (99€) è possibile.
**Chi lo incarna.** Iliad/Lemonade (eccellenza assoluta) · ConTe (compromesso per prezzo variabile) · EA SOD (prezzo fisso in categoria) · AutoAssist (anti-pattern: solo PDF nel footer).
**Azione ACI.** Convertire i PDF tariffari (oggi per tipo di intervento e fascia oraria) in **HTML scansionabile** con "cosa è incluso / non incluso" per servizio, esempi concreti ("se si scarica la batteria…"), e — dove il prezzo è variabile — un **floor o range tipico** ("un intervento SOD da X€"; "piano Essenziale da X€/anno") che riduce l'incertezza senza sostituire il preventivo. Bonus B2B: l'HTML non blocca i processi di procurement aziendale.

#### Pattern 4 — L'emergenza è un layer persistente, non un contenuto dell'hero
**Cosa dice il benchmark.** I player di categoria più maturi separano *strutturalmente* l'azione urgente dal resto: AAA usa una top-bar navy con CTA rossa "Get Roadside Assistance" + floating button persistente, sopra una nav informativa distinta; ADAC tiene la "SOS Nothilfe" rossa in header su ogni pagina, cromaticamente staccata dal giallo del brand. ADAC offre inoltre **tre canali paralleli** (app + web form 4-step + telefono), riducendo la dipendenza da un singolo punto di fallimento — mentre RAC mostra il rischio opposto (tracking app-only + login OTP che fallisce proprio in emergenza).
**Chi lo incarna.** AAA (doppio layer + floating) · ADAC (SOS persistente + multi-canale) · AAA per-service CTA (6 bottoni: "seleziona il problema, non descriverlo") · RAC (anti-pattern: canale unico fragile).
**Azione ACI.** CTA d'emergenza **sempre visibile e cromaticamente distinta** in ogni schermata (numero verde persistente, da insight utente), affiancata dalla promozione dell'**app i803116 oggi sepolta in "Chi siamo"** (geolocalizzazione, click-to-call, tracking, memoria posizione auto già integrati). Separare i due modi d'uso — **informativa vs emergenza** — con IA per task, non per organigramma.

#### Pattern 5 — La fiducia si scompone in sottodimensioni (e i due piani, sistemico e individuale, devono dialogare)
**Cosa dice il benchmark.** Booking e Airbnb non mostrano un punteggio unico: lo **scompongono** in assi separati (Booking: Staff/Pulizia/Comfort/Posizione/Qualità-prezzo/WiFi/Servizi a decimali; Airbnb: Pulizia/Precisione/Check-in/Comunicazione/Posizione/Qualità-prezzo). Il rating diventa così *calibrabile* sul profilo di chi legge, e le recensioni diventano un **database interrogabile** (filtro per argomento, segmentazione per tipo di viaggiatore) invece di una lista da scorrere. Airbnb aggiunge i segnali di longevità (anni da host, tasso di risposta).
**Chi lo incarna.** Booking (architettura a 7 livelli, trust nel sistema) · Airbnb (trust bottom-up + sottodimensioni + longevità).
**Azione ACI.** Scomporre la soddisfazione cliente in assi misurabili e comunicabili — **Velocità di arrivo / Competenza tecnica / Cortesia operatore / Completezza risoluzione / Comunicazione durante l'attesa** — invece di un unico Trustpilot aggregato (oggi a sfavore). Recensioni filtrabili per tipo di intervento (batteria vs incidente vs foratura). Così il dato 1,9 smette di essere un verdetto monolitico.

#### Pattern 6 — L'architettura a più entità si dichiara in navigazione, non si subisce
**Cosa dice il benchmark.** È il cluster che risponde direttamente a S1 (l'utente non distingue ACI / ACI Global / Sara) e al gap B2B. Tre modelli:
- **Revolut** — biforcazione in navbar ("Personale | Business | Giovani | Società") sempre visibile, stesso brand e dominio, ma pricing/feature/prove sociali/SLA differenziati per audience. **Massima chiarezza, zero attrito.**
- **Amazon** — sottomarchio "Amazon Business" (logo valigetta, dominio dedicato), navigazione **per outcome** (non per categoria), segmentazione per dimensione, fattura elettronica come leva IT. Riconoscibile come figlio del parent ma con bassa prominenza sul B2C (solo footer).
- **Europ Assistance** — **l'anti-pattern**: due siti, due numeri verdi, due entità (EA Italia + EA VAI), parent Generali nascosto, rebrand "Redion" in corso → frammentazione vissuta dall'utente come confusione.

La mappatura corretta post-acquisizione (cfr. §Cluster 5): **Sara = parent assicurativo** (ruolo Generali) · **ACI Global Servizi = sub-brand operativo** (ruolo Europ Assistance) · **ACI = ente istituzionale terzo** (bollo, tessere) di cui ACI Global porta il nome in licenza. Poiché "ACI" appartiene a un terzo, per Sara la via è l'**orchestrazione**, non l'assorbimento alla Generali.
**Azione ACI.** (1) **Navbar che dichiara i percorsi** — "Privati | Aziende | Soci ACI" — risolvendo S1 prima di qualsiasi contenuto (modello Revolut). (2) **Percorso B2B/fleet reale** organizzato per outcome ("Gestione interventi flotta", "Rendicontazione", "SLA garantiti") con segmentazione per tipo di cliente (Taxi/NCC, Flotta aziendale, Ente pubblico) — modello Amazon Business, possibile sotto-marchio "ACI Fleet". (3) Esplicitare i confini con handoff chiari (chi fa cosa: ACI Global = soccorso; ACI Italia = tessere; Sara = polizze/garanzia) **senza costringere l'utente a capire la struttura societaria** — evitando il rimbalzo EA.

---

### 5.3 · Opportunità distintive

_Cosa nessun player del benchmark fa bene — e che ACI Global può trasformare in elemento differenziante. Nascono direttamente dai negativi ricorrenti di §5.1._

1. **"Non ti lasciamo solo nell'attesa" come promessa di prodotto.** Nessun player di categoria *dichiara* la comunicazione proattiva durante l'attesa: AutoAssist la fa (emerge solo nelle recensioni), Uber è proattivo ma sulla safety (RideCheck), tutti gli altri lasciano l'utente nel silenzio fino al tracking tardivo. ACI può possedere la combinazione **tracking dall'assegnazione + richiamo proattivo + spiegazione del ritardo motivato** — proprio il punto dove RAC fallisce. Attacca frontalmente l'insight S2 (la frustrazione non è l'attesa, è la revisione ripetuta delle stime).

2. **Il primo soccorso stradale con un B2B/fleet realmente strutturato.** Nessun competitor di categoria (ADAC, AAA, EA, AutoAssist) ha un percorso B2B vero — solo accenni. ACI ha invece domanda reale (taxi/NCC, flotte aziendali, enti pubblici) e il vincolo organizzativo che la rende strategica. Importando il modello Amazon/Revolut (navigazione per outcome, SLA, rendicontazione, segmentazione) ACI sarebbe **il primo della categoria** → vantaggio competitivo netto, non solo allineamento.

3. **Un'architettura a tre entità resa leggibile.** Nessun player gestisce una tripletta "ente istituzionale terzo + operativo + assicuratore garante": Revolut/Amazon orchestrano al più due audience, EA fallisce già con due entità. Se ACI rende esplicito **chi-fa-cosa senza rimbalzi** (bollo/tessere = ACI · soccorso = ACI Global · polizza/garanzia = Sara), trasforma S1 (la confusione tra entità) da problema a **segnale di serietà e trasparenza** — un pattern che letteralmente nessuno nel benchmark possiede.

4. **La trasparenza Iliad portata nel soccorso stradale.** Nella categoria, solo EA SOD ha un prezzo fisso visibile (e solo sul pay-per-use); tutti gli altri sono opachi o rinviano a PDF. Portare lo standard "prezzo e condizioni senza sorprese, in HTML" nel soccorso stradale è un differenziante diretto sul **reclamo #1** — e nessun concorrente lo presidia.

5. **Unire il dato di sistema all'identità dell'operatore.** Nessuno collega trust sistemico (l'88%, alla ADAC) + feedback scomposto per dimensione (alla Booking) + identità del soccorritore (alla "Gelbe Engel", ma agganciata al track record reale). ACI può rendere l'operatore **una persona con uno storico**, non un anonimo — chiudendo il gap che Airbnb stesso dichiara aperto.

6. **L'empatia come azione, non come copy.** Tutti i player o ignorano il momento di stress o lo riempiono di slogan ("you live, we care"). Ma l'insight di progetto dice: gli utenti vogliono **certezza, non rassicurazioni**. L'opportunità è quindi l'empatia *operativa* — il sistema che ti richiama, che ti dà istruzioni di sicurezza nell'attesa (alla AA), che non ti fa ripetere il problema (CTA per-servizio alla AAA). Empatia dimostrata dai fatti, l'unica che il benchmark mostra essere credibile.

---

### 5.4 · Le scelte strategiche aperte (decisioni del cliente)

Tre bivi che il benchmark illumina ma non chiude — vanno decisi con Sara/ACI Global:

1. **Quanto digital-first?** AAA ha rimosso il telefono dall'header (chatbot + app, "avg 4 min") — radicale, funziona in un mercato USA digitalmente maturo. ADAC tiene tre canali paralleli. Dato il profilo utente ACI (parco auto vecchio, utenti anche anziani, stress a bordo strada) la raccomandazione è il **modello multi-canale ADAC**: numero verde persistente *e* app *e* web form, non l'app-only.

2. **Orchestrazione: quanto rendere visibile Sara?** Europ Assistance nasconde Generali (perde la garanzia istituzionale); ADAC è monolitico (massima coerenza, massimo rischio reputazionale concentrato). Per ACI Global il vincolo (nome ACI = terzo) impone orchestrazione: la scelta aperta è **quanto valorizzare Sara come garante** (oggi logo nascosto nel footer) vs quanto lasciare ACI Global autonomo.

3. **Con cosa si guida il trust?** Dati sistemici (ADAC/Booking) o prova sociale (AutoAssist/Airbnb)? ACI parte da Trustpilot 1,9: guidare con la prova sociale aggregata è autolesionista. **Raccomandazione: guidare con i dati sistemici** (che ACI possiede e che non dipendono dalla media recensioni), affiancando le recensioni *scomposte per dimensione* (Pattern 5) per non esporre il numero unico.

---

### 5.5 · Matrice dei riferimenti best-in-class

| Pattern trasversale | Riferimento da imitare | Anti-pattern da evitare |
|---|---|---|
| 1 · Fiducia documentata | ADAC (dati pubblici) · AutoAssist (richiamo proattivo) | ACI oggi (dati nascosti in "Chi siamo") |
| 2 · Certezza dell'attesa | Uber/Glovo (tracking multi-segnale) | RAC (canale unico + OTP fragile) |
| 3 · Trasparenza HTML | Iliad/Lemonade · ConTe (per prezzo variabile) | AutoAssist (solo PDF nel footer) |
| 4 · Emergenza come layer | AAA (doppio layer) · ADAC (SOS + multi-canale) | EA (nessun numero in home) |
| 5 · Trust scomposto | Booking (7 dimensioni) · Airbnb (sottodimensioni) | Trustpilot aggregato unico |
| 6 · Multi-entità dichiarata | Revolut (navbar) · Amazon (sotto-marchio per outcome) | Europ Assistance (2 siti, 2 numeri, parent nascosto) |

---

### 5.6 · Priorità per il redesign (ordinate per ROI)

Ancorate ai **pain point ad alta risolvibilità via web** (PROJECT.md): opacità costi · condizioni scoperte durante il servizio · auto sostitutiva · rimbalzo tra entità.

1. **Tariffe e condizioni in HTML scansionabile** (Pattern 3) — attacca il reclamo #1, sblocca il procurement B2B. *Massimo ROI, basso costo tecnico.*
2. **Navbar che dichiara i percorsi "Privati | Aziende | Soci ACI"** (Pattern 6) — risolve S1 (rimbalzo) e apre il B2B oggi invisibile. *Alto ROI strutturale.*
3. **App i803116 promossa in home + numero verde persistente** (Pattern 4) — asset già esistente, oggi sepolto: si valorizza, non si costruisce. *Alto ROI, costo minimo.*
4. **Dati di affidabilità come trust signal nelle pagine servizio** (Pattern 1 + 5) — 88% / 300 operatori / 1.800 partner / 32 Paesi, scomposti per dimensione. *Medio-alto ROI.*
5. **Tracking dell'intervento + comunicazione proattiva dell'attesa** (Pattern 2) — il più impattante sull'esperienza ma dipendente dall'integrazione operativa (app + centrale). *Alto valore, costo/tempo maggiore.*
6. **Architettura modulare "beyond automotive" + percorso B2B per outcome** (Pattern 6) — abilita l'espansione Sara senza destabilizzare il core. *ROI a medio termine, fondativo per la scalabilità.*

---

_Benchmark completato: 5 cluster · 16 player · 5 passaggi. Output pronto per alimentare l'Information Architecture e il concept di redesign._
