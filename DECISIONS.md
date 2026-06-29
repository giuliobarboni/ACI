# Architectural Decisions: [NOME PROGETTO]

<!--
  Questo file registra le decisioni architetturali rilevanti prese durante il progetto.
  Per ogni decisione: cosa è stato scelto, perché, quali alternative sono state scartate.
  È la memoria del progetto — evita di riaprire discussioni già chiuse.

  QUANDO AGGIORNARLO:
  - Ogni volta che si sceglie un framework, una libreria o un pattern non ovvio
  - Ogni volta che si scarta un approccio che sembrava valido ma non è stato scelto
  - Ogni volta che si cambia una decisione precedente (aggiorna lo stato a "Superseded")

  FORMATO ADR (Architecture Decision Record):
  ## [ADR-NNN] Titolo della decisione
  - **Data:** YYYY-MM-DD
  - **Stato:** Accepted | Superseded | Deprecated
  - **Contesto:** perché si è dovuto decidere
  - **Decisione:** cosa si è scelto
  - **Motivazione:** perché
  - **Alternative scartate:** cosa si è valutato e perché non è stato scelto
-->

---

## [ADR-001] Framework Frontend

- **Data:** [YYYY-MM-DD]
- **Stato:** Accepted

**Contesto:** [Es. Il progetto è un portale multi-pagina B2B con molte route. Necessita di data fetching strutturato, routing dichiarativo e buone performance di caricamento.]

**Decisione:** [Es. Next.js 15 con App Router]

**Motivazione:** [Es. Le pagine data-heavy beneficiano dei React Server Components per ridurre il JS inviato al client. L'App Router offre layout annidati nativi e route groups per separare area pubblica e privata.]

**Alternative scartate:**
- *[Alternativa 1]* — [Motivo per cui è stata scartata]
- *[Alternativa 2]* — [Motivo per cui è stata scartata]

---

## [ADR-002] Styling

- **Data:** [YYYY-MM-DD]
- **Stato:** Accepted

**Contesto:** [Es. Il design system usa CSS custom properties (token). Lo styling deve integrarsi con queste variabili senza forzare valori hardcoded.]

**Decisione:** [Es. Tailwind CSS v4]

**Motivazione:** [Es. Tailwind v4 usa una configurazione CSS-first: i token definiti in `app/globals.css` come CSS variables nel blocco `@theme inline` diventano disponibili come classi utility. Approccio coerente con la regola "mai valori hardcoded".]

**Alternative scartate:**
- *CSS Modules* — [Es. più verboso, meno produttivo per un design system token-based]
- *styled-components / Emotion* — [Es. CSS-in-JS aggiunge overhead di runtime, non ottimale con Server Components]

---

## [ADR-003] Gestione Stato Server (Data Fetching)

- **Data:** [YYYY-MM-DD]
- **Stato:** Accepted

**Contesto:** [Es. Il frontend consuma un'API REST. Molte schermate richiedono fetch con loading/error states, caching e invalidazione dei dati dopo mutazioni.]

**Decisione:** [Es. TanStack Query v5]

**Motivazione:** [Es. Gestisce automaticamente loading/error/success states, de-duplicazione delle richieste, cache con stale-while-revalidate e invalidazione granulare. Si integra bene con Next.js App Router con il pattern server prefetch + client hydration.]

**Alternative scartate:**
- *SWR* — [Es. simile ma TanStack Query ha API mutations più robusta e DevTools migliori]
- *Solo fetch in Server Components* — [Es. non gestisce le interazioni client dinamiche]

---

## [ADR-004] Gestione Stato Client

- **Data:** [YYYY-MM-DD]
- **Stato:** Accepted

**Contesto:** [Es. Alcuni stati UI devono persistere lato client tra navigazioni: carrello, preferenze UI, stato drawer/modal.]

**Decisione:** [Es. Zustand]

**Motivazione:** [Es. API minimale, nessun boilerplate, compatibile con Next.js App Router. Ideale per store semplici. Non va usato per dati remoti (quelli sono gestiti da TanStack Query).]

**Alternative scartate:**
- *Redux Toolkit* — [Es. overkill per questo caso d'uso]
- *Context API di React* — [Es. causa re-render non necessari per stati ad alta frequenza di aggiornamento]

---

## [ADR-005] Autenticazione

- **Data:** [YYYY-MM-DD]
- **Stato:** Accepted

**Contesto:** [Es. L'accesso al portale richiede autenticazione con credenziali aziendali. Necessaria gestione sessioni e protezione route dell'area autenticata.]

**Decisione:** [Es. Auth.js v5 (NextAuth) con Credentials Provider]

**Motivazione:** [Es. Integrazione nativa con Next.js App Router e middleware per protezione route. Il Credentials Provider permette di delegare la validazione delle credenziali all'API backend esistente.]

**Alternative scartate:**
- *Implementazione custom con JWT* — [Es. reinventare la ruota; Auth.js risolve già edge case come CSRF e rotazione token]
- *Clerk / Auth0* — [Es. servizi terzi a pagamento; dipendenza esterna non necessaria per questo progetto]

---

<!-- 📝 TEMPLATE PER NUOVA DECISIONE — copia e compila:

## [ADR-NNN] [Titolo della decisione]

- **Data:** [YYYY-MM-DD]
- **Stato:** Accepted

**Contesto:** [Perché si è dovuto decidere — quale problema stava cercando di risolvere]

**Decisione:** [Cosa si è scelto — nome della tecnologia/pattern/approccio]

**Motivazione:** [Perché questa scelta rispetto alle alternative — benefici specifici per questo progetto]

**Alternative scartate:**
- *[Alternativa 1]* — [Motivo per cui è stata scartata]
- *[Alternativa 2]* — [Motivo per cui è stata scartata]

-->
