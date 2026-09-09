# SOLUZIONI SUGGERITE - SCHEDA STUDENTE
## Ospedale San Leonardo - Analisi Requisiti

> **NOTA PER I DOCENTI:** Queste sono soluzioni di riferimento. Gli studenti possono avere risposte diverse ma ugualmente valide. Valutate la qualità del ragionamento, non solo la corrispondenza letterale.

---

## PARTE 1: REQUISITI IDENTIFICATI

### A) REQUISITI FUNZIONALI (esempi di risposte corrette)

| # | Requisito Funzionale | Priorità | Note |
|---|---------------------|----------|------|
| 1 | Cartella clinica elettronica accessibile da tutti i medici in tempo reale | Alta | Requisito critico |
| 2 | Sistema di gestione prenotazioni visite/esami | Alta | Mencionato più volte |
| 3 | Gestione triage Pronto Soccorso con codici colore | Alta | Specifico per PS |
| 4 | Integrazione con sistema FSE regionale | Media | Richiede accordi |
| 5 | Sistema di gestione farmacia interna | Media | Accennato |
| 6 | Sistema PACS per gestione immagini diagnostiche (RX, TAC, RMN) | Media | Necessario per radiologia |
| 7 | Gestione referti laboratorio analisi | Media | Implicito |
| 8 | Sistema di prenotazione in linea per pazienti (web/app mobile) | Bassa | Rimandabile dopo apertura |
| 9 | Notifiche automatiche agli specialisti dal PS | Media | Richiesta specifica |
| 10 | Integrazione con sistema 118 | Media | Per PS |
| 11 | Sistema di fatturazione e integrazione con sistema regionale | Alta | Obbligatorio normativo |
| 12 | Gestione pagamenti in linea | Bassa | Funzionalità aggiuntiva |
| 13 | Chat/consulto con IA per pazienti | Bassa | Menzionato ma irrealistico |
| 14 | Accesso remoto per medici (da casa) | Media | Richiesto per turni |

**Requisiti funzionali totali identificabili: ~15-20**

---

### B) REQUISITI NON FUNZIONALI (esempi)

| # | Tipo | Requisito Non Funzionale | Note |
|---|------|-------------------------|------|
| 1 | Usabilità | Interfaccia intuitiva (utilizzabile da utenti non esperti) | "Mia zia di 70 anni..." |
| 2 | Prestazioni | Aggiornamenti in tempo reale della cartella clinica | Critico per cure |
| 3 | Scalabilità | Sistema dimensionabile da 150 a 300 posti letto | Crescita prevista |
| 4 | Sicurezza | Conformità GDPR per dati sanitari | Obbligatorio legale |
| 5 | Sicurezza | Accesso remoto sicuro (VPN) | Per accessi da casa |
| 6 | Affidabilità | Sistema disponibile 24/7 (uptime >99%) | Ospedale sempre attivo |
| 7 | Compatibilità | Integrazione con sistemi esterni (regionali, bancari) | Più integrazioni richieste |
| 8 | Manutenibilità | Sistema modulare per aggiunte future | Implicito nella crescita |
| 9 | Portabilità | Accessibile da dispositivi diversi (PC, tablet, smartphone) | Per flessibilità medici |
| 10 | Prestazioni | Ottimizzazione automatica agenda (senza "buchi") | Richiesta vaga ma presente |

**Requisiti non funzionali totali: ~10-12**

---

### C) VINCOLI DEL PROGETTO

- **Budget:** 80.000 € (insufficiente per tutte le richieste)
- **Tempistica:** 6 mesi fino all'apertura (troppo stretta)
- **Altri vincoli:**
  - Integrazione obbligatoria con sistemi regionali (FSE, fatturazione)
  - Conformità normative sanitarie e GDPR
  - Certificazioni per software medicali (es. per IA diagnostica)
  - Necessità di formazione del personale
  - Assenza di responsabile sicurezza IT qualificato
  - Necessità di accordi con enti esterni (Regione, banche, 118)
  - Carenza di stakeholder chiave nell'intervista

---

## PARTE 2: CRITICITÀ RILEVATE

### 1. REQUISITI VAGHI O AMBIGUI (esempi)

**Esempio 1:**
- **Cosa ha detto:** "Sistema moderno, efficiente... che funzioni bene"
- **Perché è problematico:** Aggettivi generici, non misurabili, soggettivi
- **Domanda da fare:** "Cosa intende per 'efficiente'? Quali metriche dovremmo rispettare? (es: tempo di risposta, numero di operazioni/ora)"

**Esempio 2:**
- **Cosa ha detto:** "Ottimizzare gli appuntamenti"
- **Perché è problematico:** Non specifica cosa significa "ottimizzare" concretamente
- **Domanda da fare:** "Ottimizzare rispetto a cosa? Tempo di attesa paziente? Saturazione agenda? Riduzione spostamenti personale?"

**Esempio 3:**
- **Cosa ha detto:** "Interfaccia intuitiva, mia zia di 70 anni deve poterlo usare"
- **Perché è problematico:** "Intuitivo" è soggettivo; il riferimento all'età non è un criterio tecnico
- **Domanda da fare:** "Possiamo definire criteri di usabilità? (es: max 3 click per azione comune, test con utenti reali, formazione richiesta <4 ore)"

**Altri esempi validi:**
- "Tutti i reparti di un ospedale completo" → Quali esattamente?
- "App moderna con tutte le funzionalità" → Quali funzionalità specificamente?
- "Ridurre le liste d'attesa" → Di quanto? Qual è il target?

---

### 2. CONFLITTO TRA RICHIESTE E RISORSE

| Cosa vuole | Vincolo che lo rende difficile | Compromesso possibile |
|-----------|-------------------------------|---------------------|
| Sistema completo con IA, app, integrazioni | Budget di soli 80.000€ | Approccio per fasi: prima le funzioni critiche, poi espansione |
| Tutto pronto in 6 mesi | Normalmente progetti simili richiedono 12-18 mesi | MVP con funzionalità minime per apertura, resto dopo |
| "Sistema unico integrato" ma anche "ognuno usa i suoi programmi" | Contraddizione tecnica | Scegliere: o sistema unico o compatibilità limitata |
| "Innovativi con IA" e "Budget limitato" | IA diagnostica costa centinaia di migliaia € | Partire senza IA, valutare in futuro |
| "Sicuro, veloce, economico" | Triangolo impossibile: buono/veloce/economico - scegline due | Prioritizzare: es. sicuro e veloce, budget più alto |

---

### 3. ASPETTATIVE NON REALISTICHE

1. **"IA che suggerisce diagnosi come Google"**
   - **Perché irrealistico:** validazione clinica, certificazioni, responsabilità legale, costi elevatissimi

2. **"Sistema completo in 6 mesi"**
   - **Perché irrealistico:** Sviluppo, test, integrazioni, formazione richiedono 12-18 mesi per sistemi di questa portata

3. **"80.000€ per sistema completo"**
   - **Perché irrealistico:** Solo la cartella clinica certificata costa 50-60k€, poi servono PACS, integrazioni, formazione, manutenzione

4. **"Software libero e gratuito"
   - **Perché irrealistico:** "Gratuito" non significa senza costi: servono personalizzazione, hosting certificato, supporto, manutenzione

5. **"Il ragazzo del Wi-Fi come responsabile sicurezza"**
   - **Perché irrealistico:** Dati sanitari richiedono DPO e esperti certificati in cybersecurity sanitaria

6. **"Ottimizzazione automatica perfetta"**
   - **Perché irrealistico:** Scheduling perfetto è problema NP-completo; servono algoritmi euristici, non soluzioni magiche

---

### 4. PROBLEMI DI COMUNICAZIONE

| Termine tecnico | Il cliente ha capito? | Come spiegarlo meglio |
|----------------|---------------------|----------------------|
| API | NO | "Le interfacce che permettono a due programmi diversi di 'parlare' tra loro, come una presa elettrica standard" |
| FSE | Parzialmente (dopo) | Usare subito nome completo "Fascicolo Sanitario Elettronico" |
| PACS | NO | "Il sistema che archivia e mostra le immagini come radiografie e TAC" |
| Cloud vs in locale | NO | "Cloud = affittare computer su internet; In locale = comprare e gestire propri server" |
| VPN | Non menzionato | "Tunnel sicuro per accedere da casa come se fossi in ospedale" |
| GDPR | Implicito | "La legge europea sulla privacy dei dati personali" |

**Lezione:** Il consulente ha usato troppi termini tecnici senza verificare la comprensione.

---

### 5. ESPANSIONE DELLO SCOPE (requisiti che crescono)

Nuovi requisiti emersi durante la conversazione:

1. "Ah, dimenticavo! Il sistema deve permettere accesso remoto da casa"
2. "Deve integrarsi con il 118" (non menzionato inizialmente)
3. "Controllare FSE di altre strutture"
4. "Chiamare automaticamente specialisti dal PS"
5. Continui cambiamenti di priorità: "forse l'IA può aspettare", "l'app può aspettare"

**Come gestire:**
- Documento formale dei requisiti approvato da firmare
- Change request formale per ogni nuovo requisito
- Valutazione impatto (costi, tempi) per ogni modifica
- Riunioni di review periodiche
- Congelare requisiti prima dello sviluppo

---

## PARTE 3: ANALISI E RIFLESSIONE

### Cosa ha fatto BENE il consulente

- È rimasto paziente e professionale anche di fronte a richieste irrealistiche
- Ha fatto domande chiarificatrici (quanti posti letto, quali reparti...)
- Ha cercato di dimensionare aspettative (tempi, costi reali)
- Ha menzionato vincoli normativi (GDPR, certificazioni)
- Ha proposto approccio per fasi quando ha visto la complessità
- Ha identificato la necessità di coinvolgere altri stakeholder
- Non ha promesso l'impossibile

### Cosa avresti fatto DIVERSAMENTE

- Avrei portato un questionario preparatorio da far compilare prima
- Avrei insistito di più per coinvolgere altri stakeholder fin da subito
- Avrei usato schemi/diagrammi per visualizzare il sistema
- Avrei definito meglio scope minimo vs desiderata
- Avrei fermato prima il cliente quando aggiungeva requisiti continuamente
- Avrei evitato più termini tecnici o li avrei sempre spiegati
- Avrei mostrato esempi di progetti simili con tempi/costi reali

### Domande importanti NON fatte

- Quanti utenti simultanei? (medici, pazienti, amministrativi)
- Quali processi usate oggi? (per capire il flusso di lavoro)
- Avete già hardware/infrastruttura? Server, rete?
- Chi si occuperà di manutenzione ordinaria?
- Quali sono i formati dati che dovete gestire?
- Ci sono vincoli tecnologici specifici? (Es: compatibilità con dispositivi esistenti)
- Chi saranno gli utenti finali da intervistare?
- Quali sono i veri "deal breaker" (requisiti veramente irrinunciabili)?
- Avete fatto analisi di mercato su soluzioni esistenti?

---

### Il cliente

**Atteggiamento:** Impreparato ma collaborativo

**Perché:**
- Non ha studiato bene il problema prima dell'intervista
- Non ha coinvolto le persone giuste
- Ha aspettative irrealistiche ma in buona fede
- È disposto ad ascoltare e modificare opinioni
- Confonde entusiasmo con pianificazione
- Tipico cliente "non tecnico" in situazione reale

**NON è un cliente "difficile" nel senso negativo:** è normale che i clienti non siano esperti tecnici!

### Cosa avrebbe dovuto preparare PRIMA

- Analisi dei processi attuali e flussi di lavoro
- Mappatura degli stakeholder e loro esigenze
- Budget realistico approvato dalla direzione
- Studio di fattibilità preliminare
- Analisi comparativa (visitare altri ospedali simili)
- Lista prioritizzata di esigenze (must have vs nice to have)
- Informazioni su infrastruttura esistente
- Roadmap temporale flessibile

---

## PARTE 4: PROPOSTA DI SOLUZIONE

### APPROCCIO CONSIGLIATO

**Sviluppo per fasi (sviluppo incrementale)** o **Agile con rilasci frequenti**

**Motivazione:**
- Budget e tempi limitati richiedono prioritizzazione
- Meglio aprire con sistema basilare funzionante che aspettare sistema completo
- Permette di correggere problemi dopo feedback reale
- Riduce rischio di investire tutto in soluzione sbagliata
- Consente di iniziare a generare valore subito

 Non "tutto insieme": troppo rischioso, costoso, lento

---

### FASE 1 - PMV (Prodotto Minimo Vitale) per apertura (6 mesi) (o MVP o  primo prototipo funzionante)

**Funzionalità critiche:**

1. **Cartella Clinica Elettronica basilare**
   - Anagrafica pazienti
   - Anamnesi e visite
   - Prescrizioni
   - Accesso multi-reparto

2. **Gestione Prenotazioni interna**
   - Calendario visite/esami
   - Gestione disponibilità medici
   - Booking da front office (no app pazienti ancora)

3. **Triage Pronto Soccorso**
   - Codici colore
   - Gestione accettazione
   - Dashboard pazienti in attesa

4. **Sistema di fatturazione base**
   - Integrazione con sistema regionale
   - Emissione ricevute/fatture

**Budget stimato:** 60.000-70.000€
**Tempo necessario:** 5-6 mesi (con team adeguato)

---

### FASI SUCCESSIVE (dopo apertura)

**FASE 2 (mesi 7-12):**
- App mobile per pazienti (prenotazioni, referti)
- Integrazione FSE regionale avanzata
- Accesso remoto per medici
- Sistema di gestione farmacia integrato

**FASE 3 (anno 2):**
- PACS per gestione immagini complete
- Sistema avanzato di reportistica e analytics
- Ottimizzazione algoritmica agende
- Integrazione con 118

**FASE 4 (anno 3+):**
- Espansione per scalare a 250-300 posti letto
- Sistemi di Intelligenza aziendale
- Valutazione di IA per supporto (non diagnosi automatica)
- Telemedicina e consulti a distanza

---

## PARTE 5: DOMANDE DI COMPRENSIONE

### 1. Differenza funzionale/non funzionale

**Risposta:**
- **Requisito funzionale:** descrive COSA il sistema deve fare, una funzionalità specifica
  - *Esempio dall'intervista:* "Il sistema deve gestire le prenotazioni delle visite"
  
- **Requisito non funzionale:** descrive COME il sistema deve funzionare, caratteristiche di qualità
  - *Esempio dall'intervista:* "Il sistema deve aggiornare la cartella in tempo reale" (prestazioni) oppure "L'interfaccia deve essere intuitiva" (usabilità)

---

### 2. Gestire aspettative del cliente

**Risposta:**
Perché se il cliente ha aspettative irrealistiche (troppo ottimistiche su tempi, costi, funzionalità):
- Il progetto fallirà o deluderà comunque
- Si creeranno conflitti quando emergono i problemi
- Il budget non sarà sufficiente
- Le decisioni saranno prese su basi sbagliate
- Il rapporto di fiducia si deteriorerà

Meglio essere onesti fin dall'inizio su cosa è realisticamente fattibile.

---

### 3. Espansione dello scope

**Risposta:**
- **Definizione:** L'espansione continua e incontrollata dei requisiti durante il progetto, oltre a quanto originariamente concordato.

- **Perché è pericoloso:**
  - Fa esplodere tempi e costi
  - Il progetto non finisce mai
  - Risorse (persone, budget) si esauriscono
  - La qualità cala per fare troppe cose
  - Si perde focus sugli obiettivi originali
  - Il team si demotiva

---

### 4. Coinvolgere altri stakeholder

**Risposta:**
Perché ogni categoria di utente ha esigenze diverse:
- **Primari di reparto:** requisiti clinici specifici
- **Infermieri:** flusso di lavoro operativo quotidiano
- **Radiologi:** esigenze PACS e gestione immagini
- **Farmacisti:** gestione magazzino e prescrizioni
- **Amministrativi:** fatturazione e aspetti burocratici
- **Pazienti:** usabilità app e servizi
- **IT:** vincoli tecnici e sicurezza

Solo il direttore ha visione parziale e di alto livello, mancano i dettagli operativi.

---

### 5. Competenze oltre le tecniche

Un bravo analista di requisiti deve avere:
- **Comunicazione:** saper ascoltare e spiegare in modo chiaro
- **Mediazione:** gestire conflitti tra stakeholder con esigenze diverse
- **Empatia:** capire le esigenze reali anche quando non espresse bene
- **Negoziazione:** trovare compromessi tra desideri e vincoli
- **Problem solving:** proporre soluzioni creative
- **Organizzazione:** gestire documentazione complessa
- **Pazienza:** lavorare con clienti confusi o esigenti
- **Capacità analitica:** identificare contraddizioni e problemi
- **Conoscenza di dominio:** capire il contesto (es. sanitario)

"La competenza tecnica è necessaria ma non sufficiente!"

---

## PARTE 7: SOLUZIONI DFD 
NOTA. GLi schemi si vedono meglio su Github desktop

---

### A) DFD - SISTEMA PRENOTAZIONE VISITE

#### ENTITÀ ESTERNE identificate:
1. **Paziente** (chi richiede/modifica prenotazioni)
2. **Personale CUP** (Centro Unico Prenotazioni - operatore amministrativo)
3. **Medico** (fornisce disponibilità, riceve agenda)

#### PROCESSI identificati:

| Codice | Nome processo | Cosa fa |
|--------|--------------|---------|
| **P1** | **Gestisci Prenotazione** | Riceve richiesta di prenotazione, verifica disponibilità medico e slot liberi, crea prenotazione, invia conferma |
| **P2** | **Modifica/Cancella Prenotazione** | Riceve richiesta di modifica/cancellazione, verifica validità, aggiorna o elimina prenotazione, libera slot |
| **P6** | **Verifica Disponibilità** | (Opzionale) Controlla in tempo reale slot disponibili per una data specialità |

#### ARCHIVI DATI identificati:

| Codice | Nome archivio | Cosa contiene |
|--------|--------------|---------------|
| **D1** | **Archivio Prenotazioni** | ID prenotazione, data/ora, ID paziente, ID medico, stato (confermata/in corso/conclusa/cancellata), note |
| **D2** | **Archivio Medici** | ID medico, nome, specialità, orari disponibilità, calendario |
| **D3** | **Archivio Pazienti** | ID paziente, CF, nome, cognome, data nascita, contatti, tessera sanitaria |

#### DIAGRAMMA DFD COMPLETO - Prenotazioni:

```
┌─────────────┐
│   PAZIENTE  │─────(Richiesta prenotazione: CF, tipo visita, data)─────┐
└─────────────┘                                                          │
                                                                         ▼
                                                              ┌──────────────────────┐
                                                              │  P1: Gestisci        │
                                                              │      Prenotazione    │
                                                              └──────────────────────┘
                                                                    │   │   │
                                                    ┌───────────────┘   │   └──────────────┐
                                                    │ legge             │                  │ scrive
                                                    ▼                   ▼                  ▼
                                            ╔═══════════════╗   ╔═══════════════╗  ╔═══════════════╗
                                            ║ D3: Archivio  ║   ║ D2: Archivio  ║  ║ D1: Archivio  ║
                                            ║    Pazienti   ║   ║    Medici     ║  ║  Prenotazioni ║
                                            ╚═══════════════╝   ╚═══════════════╝  ╚═══════════════╝
                                                                                            │
                                                                                            │ legge/aggiorna
┌─────────────┐                                                                             │
│   PAZIENTE  │─(Richiesta modifica/cancellazione: ID prenotazione)──┐                     │
└─────────────┘                                                       │                     │
                                                                      ▼                     │
                                                           ┌──────────────────────┐         │
                                                           │  P2: Modifica/       │◄────────┘
                                                           │   Cancella Prenot.   │
                                                           └──────────────────────┘
                                                                      │
                                                                      │ (Conferma)
                                                                      ▼
                                                              ┌─────────────┐
                                                              │   PAZIENTE  │
                                                              └─────────────┘

┌─────────────┐
│ OPERATORE   │────(inserisce prenotazione per conto del paziente)───┐
│    CUP      │                                                       │
└─────────────┘                                        stesso flusso  │
                                                       verso P1 ──────┘
```

#### FLUSSI DI DATI principali:

1. **Da Paziente a P1**: Richiesta prenotazione (CF, tipo visita/specialità, data/ora preferita)
2. **Da P1 a D3**: Lettura dati anagrafici paziente (verifica esistenza)
3. **Da P1 a D2**: Lettura disponibilità medici per specialità richiesta
4. **Da P1 a D1**: Scrittura nuova prenotazione + lettura slot occupati
5. **Da P1 a Paziente**: Conferma prenotazione (data, ora, nome medico, luogo)
6. **Da Paziente a P2**: Richiesta modifica/cancellazione (ID prenotazione)
7. **Da P2 a D1**: Aggiornamento/eliminazione record prenotazione
8. **Da Operatore CUP a P1**: Stesso flusso del paziente (prenotazione telefonica/sportello)

---

### B) DFD - CARTELLA CLINICA ELETTRONICA

#### ENTITÀ ESTERNE identificate:
1. **Medico** (consulta e aggiorna cartelle)
2. **Infermiere** (inserisce parametri vitali, terapie somministrate)
3. **Laboratorio/Radiologia** (inserisce referti esami)

#### PROCESSI identificati:

| Codice | Nome processo | Cosa fa |
|--------|--------------|---------|
| **P3** | **Consulta Cartella** | Riceve richiesta di visualizzazione, verifica autorizzazioni, recupera dati clinici, mostra cartella |
| **P4** | **Aggiorna Cartella** | Riceve nuovi dati (visita, diagnosi, prescrizione, esame), valida, salva nella cartella, conferma |
| **P5** | **Autentica/Autorizza Utente** | Verifica credenziali utente, controlla permessi (cosa può vedere/modificare), genera token sessione |

#### ARCHIVI DATI identificati:

| Codice | Nome archivio | Cosa contiene |
|--------|--------------|---------------|
| **D4** | **Archivio Cartelle Cliniche** | ID cartella, ID paziente, anamnesi, allergie, patologie pregresse, visite (data, medico, diagnosi, terapia), esami (tipo, data, referto), prescrizioni, ricoveri |
| **D5** | **Archivio Utenti/Permessi** | ID utente, username, password hash, ruolo (medico/infermiere/amministrativo), permessi (read/write su quali sezioni) |
| **D3** | **Archivio Pazienti** | (già esistente - link per collegare cartella a paziente) |

#### DIAGRAMMA DFD COMPLETO - Cartella Clinica:

```
┌─────────────┐
│   MEDICO    │────(Credenziali: username, password)─────┐
└─────────────┘                                           │
                                                          ▼
┌─────────────┐                                ┌──────────────────────┐
│ INFERMIERE  │────(Credenziali)──────────────►│  P5: Autentica/      │
└─────────────┘                                │      Autorizza       │
                                               └──────────────────────┘
                                                          │
                                            verifica     │
                                                          ▼
                                                  ╔═══════════════╗
                                                  ║ D5: Archivio  ║
                                                  ║ Utenti/       ║
                                                  ║ Permessi      ║
                                                  ╚═══════════════╝
                                                          │
                                            (Token autorizzato + permessi)
                                                          │
                    ┌─────────────────────────────────────┴────────────────────────┐
                    │                                                              │
                    ▼                                                              ▼
         ┌──────────────────────┐                                      ┌──────────────────────┐
         │  P3: Consulta        │                                      │  P4: Aggiorna        │
         │      Cartella        │                                      │      Cartella        │
         └──────────────────────┘                                      └──────────────────────┘
                    │ legge                                                       │ scrive
                    │                                                             │
                    └──────────────────┬────────────────────────────────────────┘
                                       ▼
                               ╔═══════════════╗
                               ║ D4: Archivio  ║
                               ║   Cartelle    ║◄────(link via ID paziente)────╔═══════════════╗
                               ║   Cliniche    ║                               ║ D3: Archivio  ║
                               ╚═══════════════╝                               ║   Pazienti    ║
                                       │                                       ╚═══════════════╝
                    ┌──────────────────┴───────────────────┐
                    │ (Dati clinici visualizzati)          │ (Conferma salvataggio)
                    ▼                                      ▼
            ┌─────────────┐                        ┌─────────────┐
            │   MEDICO    │                        │   MEDICO    │
            └─────────────┘                        └─────────────┘
```

#### FLUSSI DI DATI principali:

1. **Da Medico a P5**: Credenziali (username, password)
2. **Da P5 a D5**: Verifica credenziali e recupero permessi
3. **Da P5 a P3/P4**: Token autorizzato + matrice permessi
4. **Da Medico a P3**: Richiesta consultazione (ID paziente)
5. **Da P3 a D4**: Lettura dati cartella clinica (filtrati per permessi)
6. **Da P3 a D3**: Lettura dati anagrafici paziente
7. **Da P3 a Medico**: Visualizzazione cartella completa
8. **Da Medico a P4**: Nuovi dati clinici (diagnosi, prescrizione, note visita)
9. **Da P4 a D4**: Scrittura/aggiornamento record nella cartella
10. **Da P4 a Medico**: Conferma salvataggio + timestamp

---

### C) INTEGRAZIONE TRA I DUE SISTEMI

#### Momento di integrazione #1: **ACCETTAZIONE DEL PAZIENTE**

- **Processo coinvolto:** **P6: Gestisci Accettazione**
- **Archivi coinvolti:** D1 (Prenotazioni), D3 (Pazienti), D4 (Cartelle Cliniche)
- **Dati scambiati:**
  - INPUT: Codice paziente o tessera sanitaria
  - AZIONI:
    1. Legge D1 → verifica prenotazione attiva per oggi
    2. Legge D3 → recupera anagrafica paziente
    3. Legge/Crea D4 → apre cartella esistente o ne crea una nuova
    4. Aggiorna D1 → stato prenotazione da "confermata" a "in corso"
  - OUTPUT: Paziente accettato, cartella pronta per il medico

#### Momento di integrazione #2: **ACCESSO CARTELLA DURANTE VISITA**

- **Processo coinvolto:** **P3: Consulta Cartella** (collegato alla prenotazione)
- **Archivi coinvolti:** D1 (Prenotazioni), D4 (Cartelle), D3 (Pazienti)
- **Dati scambiati:**
  - Il medico accede al suo agenda (da D1) e vede i pazienti prenotati
  - Seleziona un paziente → il sistema recupera automaticamente ID paziente da D1
  - Usa quell'ID per aprire la cartella corretta da D4
  - Collegamento: D1.id_paziente = D4.id_paziente = D3.id_paziente

#### DIAGRAMMA INTEGRAZIONE:

```
┌─────────────────┐
│ OPERATORE       │───(Tessera sanitaria / CF paziente)─────┐
│ ACCETTAZIONE    │                                          │
└─────────────────┘                                          ▼
                                                  ┌──────────────────────┐
                                                  │  P6: Gestisci        │
                                                  │     Accettazione     │
                                                  └──────────────────────┘
                                                       │   │   │
                                     ┌─────────────────┘   │   └─────────────────┐
                                     │ legge/aggiorna      │ legge               │ legge/crea
                                     ▼                     ▼                     ▼
                              ╔═══════════════╗    ╔═══════════════╗    ╔═══════════════╗
                              ║ D1: Archivio  ║    ║ D3: Archivio  ║    ║ D4: Archivio  ║
                              ║  Prenotazioni ║    ║   Pazienti    ║    ║   Cartelle    ║
                              ╚═══════════════╝    ╚═══════════════╝    ╚═══════════════╝
                              (stato: "in corso")  (info paziente)      (apre/crea)
```

**Chiavi di collegamento:**
- `D1.id_paziente` → `D3.id_paziente` (FK)
- `D4.id_paziente` → `D3.id_paziente` (FK)
- `D1.id_medico` → `D2.id_medico` (FK)

---

### D) SOLUZIONI ALLE PROBLEMATICHE

#### 1. Gestione della concorrenza

**Cosa succede:** Due medici aprono contemporaneamente la stessa cartella, entrambi aggiungono note, salvano. Chi vince?

**Soluzione proposta:**
- **Lock ottimistico con versioning:**
  - Ogni record della cartella ha un campo `versione` o `timestamp_ultimo_aggiornamento`
  - Quando P4 salva, controlla se la versione è ancora quella che aveva letto
  - Se nel frattempo è cambiata → avviso "Cartella modificata da altro utente, ricaricare"
  - Opzionale: mostrare le differenze e permettere merge manuale

**Alternativa:**
- **Lock pessimistico:** Chi apre la cartella in modifica la "blocca" per altri (ma può causare problemi se il medico si dimentica di chiudere)

#### 2. Aggiornamento in tempo reale

**Come garantire dati sempre aggiornati:**

**Soluzione tecnica:**
- **WebSockets o Server-Sent Events (SSE):**
  - Quando P4 scrive su D4, il server invia una notifica push a tutti i client che stanno visualizzando quella cartella
  - I client ricevono un messaggio "La cartella è stata aggiornata" e ricaricano automaticamente
  
**Alternativa più semplice:**
- **Polling periodico:** Ogni 30-60 secondi, P3 ricontrolla se `timestamp_ultimo_aggiornamento` è cambiato
- Se sì, mostra banner "Nuovi dati disponibili - clicca per ricaricare"

**Indicatore visivo:**
- Mostrare sempre in alto "Ultimo aggiornamento: 10:35:22" per dare awareness al medico

#### 3. Sicurezza e accessi

**Chi può vedere/modificare cosa:**

| Ruolo | Consulta | Modifica | Cancella | Note |
|-------|----------|----------|----------|------|
| **Medico curante** |  Tutta la storia |  Proprie visite |  Mai | Può aggiungere diagnosi, prescrizioni |
| **Medico specialista** | Parti pertinenti |  Proprie visite |  Mai | Es: cardiologo vede esami cardiologici |
| **Medico PS** |  Info emergenza |  Intervento PS | Mai | Accesso rapido senza barriere burocratiche |
| **Infermiere** |  Terapie correnti |  Parametri vitali, somministrazioni |  Mai | Non può prescrivere farmaci |
| **Amministrativo**   Solo anagrafica |  Mai |  Mai | Solo per prenotazioni/accettazione |
| **Laboratorio** |  No (solo ID) |  Inserisce referti |  Mai | Carica file PDF/immagini nel fascicolo |

**Controlli necessari nel processo P5:**
- Matrice permessi memorizzata in D5
- Ogni azione verifica: `if (utente.ruolo.permessi.includes('write_cartella'))`
- Log di audit: chi ha fatto cosa e quando (per GDPR)

#### 4. Prenotazione in linea vs sportello

**Il flusso cambia?**
 **Cambia solo l'interfaccia, non la logica del processo**

**Differenze:**

| Aspetto | Prenotazione sportello | Prenotazione in linea (app) |
|---------|----------------------|---------------------------|
| **Entità esterna** | Operatore CUP | Paziente direttamente |
| **Processo** | Stesso P1 | Stesso P1 |
| **Input** | Operatore inserisce dati | Paziente compila form |
| **Validazioni** | Minime (operatore sa cosa fare) | Più stringenti (CAPTCHA, conferma email, limiti tentativi) |
| **Autenticazione** | Non necessaria (operatore già autenticato) | Paziente deve loggarsi o registrarsi |
| **Conferma** | Immediata a voce + cartacea | Email/SMS automatica |

**Nel DFD:**
- Possiamo rappresentare DUE frecce verso P1: una da "Operatore CUP", una da "Paziente (app)"
- Oppure considerare "CUP" come interfaccia che può essere sia umana che digitale
- Il processo P1 resta identico, cambia solo il "front-end"

---

### E) RISPOSTE DOMANDE DI COMPRENSIONE

#### 1. Quanti processi principali?

**Risposta:** **6 processi principali** identificati:
- P1: Gestisci Prenotazione
- P2: Modifica/Cancella Prenotazione
- P3: Consulta Cartella
- P4: Aggiorna Cartella
- P5: Autentica/Autorizza Utente
- P6: Gestisci Accettazione (integrazione)

(Potrebbero essere anche 5 se non si conta P6, o più se si dettagliano sotto-processi)

---

#### 2. Differenza entità esterna vs archivio dati

**Risposta:**

| Caratteristica | Entità Esterna | Archivio Dati |
|---------------|---------------|---------------|
| **Cosa è** | Un attore FUORI dal sistema | Un contenitore DENTRO il sistema |
| **Ruolo** | Usa il sistema (input/output) | Memorizza dati in modo persistente |
| **Esempi** | Paziente, Medico, CUP | Database pazienti, tabelle prenotazioni |
| **Nel DFD** | Rettangolo semplice | Rettangolo doppio (o linee parallele) |
| **Interazione** | Invia/riceve dati dai processi | Viene letto/scritto dai processi |

**Chiave:** Le entità sono PERSONE o SISTEMI ESTERNI; gli archivi sono DATI MEMORIZZATI.

---

#### 3. Perché separare "Archivio Pazienti" da "Archivio Cartelle Cliniche"?

**Risposta:**

**Motivi di separazione:**

1. **Scopo diverso:**
   - D3 (Pazienti) = dati anagrafici, amministrativi (nome, CF, indirizzo, contatti)
   - D4 (Cartelle) = dati clinici, sanitari (diagnosi, terapie, esami)

2. **Sicurezza e privacy:**
   - Accesso amministrativo può vedere D3 ma NON D4
   - Dati clinici hanno protezione maggiore (segreto professionale)

3. **Ciclo di vita:**
   - Anagrafica paziente cambia raramente
   - Cartella clinica viene aggiornata continuamente

4. **Scalabilità:**
   - D3 è relazionale (database SQL)
   - D4 potrebbe essere documento (NoSQL) o file system per referti

5. **Integrazione:**
   - D3 può essere condiviso con sistema prenotazioni, fatturazione
   - D4 solo per uso clinico

**Collegamento:** Sono diversi ma RELAZIONATI tramite `id_paziente` (chiave esterna).

---

#### 4. Quali archivi consultare prima di confermare prenotazione?

**Risposta:**  TUTTI E TRE:

-  **D1: Archivio Prenotazioni** → Verificare che lo slot non sia già occupato
-  **D2: Archivio Medici** → Verificare disponibilità del medico in quel giorno/ora e che abbia la specialità richiesta
-  **D3: Archivio Pazienti** → Verificare che il paziente esista (o crearlo se prima visita), recuperare i suoi dati

(D4 non serve in questa fase, serve dopo durante l'accettazione)

---

#### 5. Il DFD mostra l'ordine temporale?

**Risposta:  NO**

**Spiegazione:**
- Il DFD mostra COSA fluisce (quali dati), non QUANDO
- Mostra le DIPENDENZE LOGICHE (se A legge da B, serve che B esista)
- Ma NON mostra la sequenza temporale delle operazioni

**Per l'ordine temporale servono altri diagrammi:**
- **Diagrammi di sequenza** (UML) → mostrano messaggi nel tempo
- **Diagrammi di flusso** → mostrano decisioni e branching
- **Diagrammi di attività** (UML) → mostrano il flusso di lavoro

**Esempio:**
- Nel DFD vedo che P1 legge da D2 e D3, ma non so se legge prima D2 o D3
- Il DFD dice solo che P1 HA BISONO di entrambi prima di scrivere su D1

---

## CRITERI DI VALUTAZIONE DETTAGLIATI

### Ottimo (8/8 punti):
- Ha identificato tutte le entità, processi e archivi principali
- Il diagramma è disegnato correttamente con simboli standard
- Ha compreso l'integrazione tra i due sistemi
- Ha proposto soluzioni tecniche alle problematiche
- Il tutto è leggibile e ben organizzato

### Buono (6-7/8 punti):
- Ha identificato la maggior parte degli elementi
- Qualche imprecisione nei simboli o nei flussi
- Ha capito il concetto di integrazione anche se non perfettamente
- Risposte alle problematiche presenti ma incomplete

### Sufficiente (5/8 punti):
- Ha identificato gli elementi base (entità principali, 2-3 processi, qualche archivio)
- Diagramma disegnato in modo semplificato ma comprensibile
- Integrazione accennata
- Qualche risposta alle problematiche

### Insufficiente (<5/8 punti):
- Mancano elementi fondamentali
- Confusione tra entità e archivi
- Diagramma illeggibile o con simboli inventati
- Non ha compreso le problematiche

---
