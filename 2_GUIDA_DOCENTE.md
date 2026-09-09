# GUIDA PER I DOCENTI
## Intervista Ospedale San Leonardo - Analisi dei Requisiti

---

## OBIETTIVI DIDATTICI

L'attività mira a far comprendere agli studenti:
1. Le difficoltà reali nell'estrazione dei requisiti
2. La differenza tra requisiti funzionali e non funzionali
3. L'importanza della comunicazione tra cliente e tecnico
4. Le criticità tipiche dei progetti IT
5. La necessità di gestire aspettative e vincoli

---

## CRITICITÀ EMERSE NELL'INTERVISTA

### 1. **REQUISITI VAGHI E AMBIGUI**

**Dove emerge:**
- "Sistema moderno, efficiente... che funzioni bene"
- "Ottimizzare gli appuntamenti"
- "Interfaccia intuitiva" (mia zia di 70 anni...)
- "App moderna con tutte le funzionalità"

**Cosa far notare:**
- Aggettivi generici non sono requisiti
- Serve specificare COSA significa "ottimizzare" o "efficiente"
- "Intuitivo" è soggettivo: servono criteri misurabili
- "Tutte le funzionalità" è impossibile da definire

**Domande per gli studenti:**
- Come trasformereste "efficiente" in un requisito misurabile?
- Quali domande avrebbe dovuto fare il consulente per chiarire "ottimizzare"?

---

### 2. **CONFLITTO BUDGET/FUNZIONALITÀ**

**Dove emerge:**
- 80.000€ per sistema completo con IA, app mobile, integrazioni
- Aspettativa di costi bassi ("la tecnologia costa poco")
- Richiesta di software gratuiti vs. esigenze enterprise

**Cosa far notare:**
- Il cliente spesso sottostima i costi reali
- Esiste gap tra aspettative e realtà economica
- Software "gratuito" non significa "senza costi"
- Serve prioritizzare in base al budget

**Domande per gli studenti:**
- Quali funzionalità escludereste con quel budget?
- Come spieghereste al cliente che il budget è insufficiente?

---

### 3. **ASPETTATIVE IRREALISTICHE**

**Dove emerge:**
- "IA che suggerisce diagnosi" (come Google)
- Sistema completo in 6 mesi
- Integrazione automatica con tutti i sistemi esterni
- "Mio nipote gestisce il Wi-Fi" come responsabile sicurezza

**Cosa far notare:**
- IA medica richiede certificazioni e anni di sviluppo
- I tempi tecnici spesso non coincidono con quelli di business
- Le integrazioni richiedono accordi e documentazione
- Sicurezza sanitaria richiede competenze specifiche

**Domande per gli studenti:**
- Perché l'IA diagnostica non è "semplice" come pensa il cliente?
- Quali rischi comporta avere tempi troppo stretti?

---

### 4. **REQUISITI CONTRASTANTI**

**Dove emerge:**
- "Sistema unico integrato" vs "ognuno usa i suoi programmi"
- "Essere innovativi" vs "budget limitato"
- "Tutto pronto subito" vs "possiamo posticipare alcune cose"
- "Sicuro, veloce, economico" (triangolo impossibile)

**Cosa far notare:**
- I clienti spesso chiedono cose incompatibili
- Serve mediazione e compromessi
- Il consulente deve far emergere le contraddizioni
- Prioritizzazione è fondamentale

**Domande per gli studenti:**
- Quali compromessi proporreste al cliente?
- Come ordinereste le priorità?

---

### 5. **PROBLEMA DI COMUNICAZIONE TECNICO/NON-TECNICO**

**Dove emerge:**
- "Interfaccia? Che cosa sono?"
- "FSE? Ah, il Fascicolo..."
- "PACS?"
- "Cloud o in locale? Quale costa meno?"

**Cosa far notare:**
- Gergo tecnico crea barriere comunicative
- Il consulente deve tradurre in linguaggio comprensibile
- Il cliente deve ammettere quando non capisce
- Serve pazienza ed empatia da entrambe le parti

**Domande per gli studenti:**
- Come spieghereste un'"interfaccia di programmazione" a qualcuno non tecnico?
- Quando è appropriato usare termini tecnici?

---

### 6. **REQUISITI CHE CAMBIANO (ESPANSIONE DELLO SCOPE)**

**Dove emerge:**
- "Ah, dimenticavo!" (accesso remoto)
- Continui aggiunte durante l'intervista
- "Anche se... forse l'IA può aspettare"
- Modifiche alle priorità in corso d'opera

**Cosa far notare:**
- I requisiti emergono gradualmente
- Il cliente scopre nuove esigenze parlando
- Servono meccanismi per gestire i cambiamenti
- Documentazione è fondamentale

**Domande per gli studenti:**
- Come evitereste che i requisiti continuino a crescere?
- Quale processo usereste per gestire nuove richieste?

---

## ALTRI PROBLEMI EVIDENZIATI

### 7. **MANCANZA DI STAKEHOLDER CHIAVE**
- Solo il direttore sanitario presente
- Mancano: primari, IT, amministrazione, utilizzatori finali
- Visione parziale e incompleta

### 8. **ASSENZA DI ANALISI PRE-MEETING**
- Nessuna documentazione preparata
- Nessun studio di fattibilità preliminare
- Nessuna analisi dei processi esistenti

### 9. **VINCOLI NASCOSTI**
- Tempistiche imposte (6 mesi)
- Integrazioni obbligatorie non menzionate subito
- Requisiti normativi (GDPR, certificazioni)

### 10. **DELEGA ECCESSIVA**
- "Lei è l'esperto, saprà come fare"
- "Scelga lei la soluzione migliore"
- Mancanza di ownership del cliente

---

## SUGGERIMENTI PER LA DISCUSSIONE IN CLASSE

### FASE 1: Raccolta (10 minuti)
Fate completare agli studenti la scheda individualmente

### FASE 2: Confronto (15 minuti)
- Dividete in gruppi di 3-4
- Ogni gruppo condivide i requisiti identificati
- Consolidate una lista comune per gruppo

### FASE 3: Discussione plenaria (20-25 minuti)

**Domande guida:**
1. Quali requisiti sono chiari? Quali ambigui?
2. Quali problemi avete notato?
3. Se foste il consulente, cosa avreste fatto diversamente?
4. Il cliente è "difficile" o è normale?
5. Come si poteva condurre meglio l'intervista?

### FASE 4: Teoria (15 minuti)
- Definizione formale di requisito
- Funzionali vs non funzionali
- Tecniche di elicitazione
- Gestione delle aspettative
- Documentazione dei requisiti

### FASE 5: Esercizio pratico (opzionale, 20 minuti)
Far riscrivere agli studenti 3-5 requisiti dell'intervista in forma corretta:
- Chiara, specifica, misurabile
- Distinguere funzionali/non funzionali
- Indicare priorità
- Segnalare dipendenze e vincoli

---

## SOLUZIONI POSSIBILI AI PROBLEMI

Discutete con gli studenti queste possibili soluzioni:

### Per requisiti vaghi:
- Usare la tecnica delle 5W + H (Who, What, When, Where, Why, How)
- Chiedere esempi concreti
- Usare prototipi e mockup
- Definire criteri di accettazione misurabili

### Per conflitti budget/funzionalità:
- Approccio MoSCoW (Must have, Should have, Could have, Won't have)
- Sviluppo incrementale/agile
- PMV (Prodotto Minimo Vitale)
- Presentare diverse opzioni con trade-off chiari

### Per aspettative irrealistiche:
- Educazione del cliente
- Casi studio e analisi comparative
- Coinvolgimento di esperti di dominio
- Documentazione di rischi e conseguenze

### Per comunicazione:
- Glossario condiviso
- Diagrammi e visualizzazioni
- Evitare gergo quando possibile
- Verificare sempre la comprensione

### Per espansione dello scope:
- Gestione dei cambiamenti formale
- Documentazione requisiti approvata
- Gestione priorità
- Contratti chiari su cosa è incluso

---

## COLLEGAMENTI CON IL PROGRAMMA

Questa attività può introdurre o consolidare:
- **Ingegneria del software:** ciclo di vita, requisiti
- **Gestione progetti:** vincoli (tempo, costo, scopo)
- **Database:** analisi dei dati necessari
- **Sistemi informativi:** ERP, integrazione sistemi
- **Sicurezza:** GDPR, cybersecurity sanitaria
- **Competenze trasversali:** comunicazione, problem solving

---

## VALUTAZIONE DELL'ATTIVITÀ

Valutate gli studenti su:
- **Completezza:** hanno identificato i requisiti principali?
- **Criticità:** hanno riconosciuto i problemi?
- **Analisi:** hanno distinto funzionali da non funzionali?
- **Proposte:** hanno suggerito soluzioni sensate?
- **Partecipazione:** hanno contribuito alla discussione?

---

## ESTENSIONI POSSIBILI

1. **Homework:** far scrivere il documento di analisi requisiti formale
2. **Role-play:** studenti provano a fare consulenti/clienti in altre interviste
3. **Progetto:** seguire tutto il ciclo dall'analisi all'implementazione
4. **Invito esperti:** portare un vero analista/project manager
5. **Casi studio:** analizzare progetti reali falliti per requisiti mal definiti

---

## RISORSE AGGIUNTIVE

### Link utili:
- Standard IEEE 830 per Specifiche Requisiti Software
- Tecniche di elicitazione requisiti
- Template documento analisi requisiti
- Casi studio progetti IT falliti

### Bibliografia consigliata:
- "Software Requirements" di Karl Wiegers
- "Mastering the Requirements Process" di Robertson & Robertson
- Agile User Stories

---

## NOTE FINALI

**IMPORTANTE:** Sottolineate che:
- Questi problemi sono REALI e comuni
- Un bravo analista sa far emergere e gestire queste criticità
- La comunicazione è importante quanto la competenza tecnica
- L'analisi requisiti è una delle fasi più critiche (e sottovalutate)
- Errori in questa fase costano 10-100 volte di più se scoperti dopo

**MESSAGGIO CHIAVE:** Un progetto IT ha successo non solo per la tecnologia, ma per quanto bene si comprendono e gestiscono i bisogni reali del cliente.

---

---

# PARTE 2: GUIDA PER LA COSTRUZIONE DEL DFD

## OBIETTIVI DIDATTICI - PARTE 2

Questa seconda parte mira a:
1. **Modellare i processi** attraverso un Diagramma di flusso dei dati
2. **Identificare componenti chiave**: entità, processi, archivi, flussi
3. **Comprendere le relazioni** tra sottosistemi
4. **Far emergere problematiche tecniche**: concorrenza, sicurezza, integrazione
5. **Preparare alla progettazione database** (relazioni tra archivi)

---

## PREPARAZIONE PER LA PARTE 2

### Materiali necessari:
- ✅ Lavagna o LIM per disegnare insieme
- ✅ Pennarelli di colori diversi (es: blu=entità, rosso=processi, verde=archivi)
- ✅ Scheda studente con Parte 7 compilabile
- ✅ (Opzionale) Post-it colorati per costruzione collaborativa

### Convenzioni DFD da usare:
Assicuratevi che tutti usino la **stessa notazione**:

| Elemento | Simbolo | Descrizione |
|----------|---------|-------------|
| **Entità esterna** | Rettangolo | Attori esterni al sistema (Paziente, Medico, CUP) |
| **Processo** | Cerchio/Ovale | Trasformazione dati (P1, P2, P3...) |
| **Archivio dati** | Rettangolo doppio o linee parallele | Dove si salvano i dati (D1, D2, D3...) |
| **Flusso di dati** | Freccia → | Movimento di informazioni tra elementi |

### Tempo necessario:
- 20-25 minuti per la costruzione guidata
- 15 minuti per completamento scheda individuale
- 10 minuti per confronto risultati

---

## SVOLGIMENTO PARTE 2 - STEP BY STEP

### INTRODUZIONE (2 minuti)

**Cosa dire:**
> "Ora che abbiamo raccolto i requisiti nella prima intervista, dobbiamo **modellare il sistema**. Useremo il DFD - Diagramma di flusso dei dati - per visualizzare come fluiscono i dati. Concentreremo su due funzionalità critiche: Prenotazioni e Cartella Clinica."

**Disegnate sulla lavagna la legenda** con i simboli.

---

### SISTEMA PRENOTAZIONI (10 minuti)

#### Step 1: Identificare le entità esterne

**Domanda agli studenti:** "Chi sono gli attori che interagiscono con il sistema di prenotazione?"

**Risposte attese:**
- Paziente
- Personale CUP (Centro Unico Prenotazioni)
- Medico (indirettamente, per disponibilità)

**Disegnate i rettangoli** sulla lavagna mentre gli studenti rispondono.

---

#### Step 2: Identificare i processi principali

**Domanda:** "Quali azioni principali deve compiere il sistema?"

**Risposte attese:**
- P1: Gestisci Prenotazione (crea nuova prenotazione)
- P2: Modifica/Cancella Prenotazione
- (Opzionale) P6: Verifica Disponibilità

**Fate notare:** I processi sono **attivi** (verbi: gestisci, modifica, verifica)

**Disegnate i cerchi** con i nomi dei processi.

---

#### Step 3: Identificare gli archivi dati

**Domanda:** "Quali dati devono essere memorizzati?"

**Risposte attese:**
- D1: Archivio Prenotazioni (agenda appuntamenti)
- D2: Archivio Medici (specialità, disponibilità)
- D3: Archivio Pazienti (anagrafica)

**Fate notare:** Gli archivi sono **passivi** (nomi: Archivio di...)

**Disegnate i rettangoli doppi**.

---

#### Step 4: Tracciare i flussi di dati

**Domanda:** "Quali informazioni vengono scambiate?"

Guidateli a identificare:

**Flusso 1:** Paziente → P1 (Gestisci Prenotazione)
- *Dati:* Richiesta prenotazione (nome, CF, tipo visita, data preferita)

**Flusso 2:** P1 → D3 (Archivio Pazienti)
- *Azione:* Legge dati paziente / Verifica esistenza

**Flusso 3:** P1 → D2 (Archivio Medici)
- *Azione:* Legge disponibilità medici per quella specialità

**Flusso 4:** P1 → D1 (Archivio Prenotazioni)
- *Azione:* Verifica slot disponibili / Scrive nuova prenotazione

**Flusso 5:** P1 → Paziente
- *Dati:* Conferma prenotazione (data, ora, medico)

**Disegnate le frecce** etichettandole con i dati trasferiti.

---

### SISTEMA CARTELLA CLINICA (10 minuti)

#### Step 1: Entità esterne

**Domanda:** "Chi accede alla cartella clinica?"

**Risposte attese:**
- Medico
- Infermiere (se volete dettagliare)
- Laboratorio (inserisce referti)

---

#### Step 2: Processi

**Domanda:** "Cosa fanno questi attori con la cartella?"

**Risposte attese:**
- P3: Consulta Cartella (lettura)
- P4: Aggiorna Cartella (scrittura: nuova visita, diagnosi, prescrizione)
- P5: Autenticazione/Autorizzazione (controllo accessi)

**Fate notare:** P5 è un processo **trasversale** - serve per accedere a tutti gli altri!

---

#### Step 3: Archivi dati

**Domanda:** "Dove si salvano le informazioni cliniche?"

**Risposte attese:**
- D4: Archivio Cartelle Cliniche (anamnesi, visite, diagnosi, terapie, esami)
- D5: Archivio Utenti/Permessi (chi può fare cosa)

**Domanda critica:** "Perché non mettiamo tutto nell'Archivio Pazienti (D3)?"

**Risposta:** Separazione delle responsabilità:
- D3 = dati anagrafici (nome, indirizzo, CF)
- D4 = dati clinici (storia medica, diagnosi)

Sono **collegati** ma **distinti** per sicurezza e modularità.

---

#### Step 4: Flussi di dati

Guidateli a tracciare:

**Per P3 (Consulta):**
- Medico → P5 (Autenticazione) → [verifica] → D5
- P5 → P3 (token autorizzato)
- P3 → D4 (legge cartella ID paziente)
- P3 → Medico (visualizza dati clinici)

**Per P4 (Aggiorna):**
- Medico → P4 (nuovi dati: diagnosi, prescrizione)
- P4 → D4 (scrive/aggiorna record)
- P4 → Medico (conferma salvataggio)

---

### INTEGRAZIONE TRA I DUE SISTEMI (5 minuti)

**Domanda cruciale:** "I due sistemi devono comunicare?"

**Risposta:** SÌ! Quando?

**Scenario 1: Accettazione**
- Paziente arriva per visita prenotata
- P6: Gestisci Accettazione
  - Legge D1 (verifica prenotazione)
  - Legge/crea D4 (apre cartella)
  - Aggiorna D1 (stato: "in corso")

**Scenario 2: Durante la visita**
- Medico accede a P3 (Consulta Cartella)
- Il sistema sa quale paziente perché è collegato alla prenotazione attiva

**Fate disegnare** il processo P6 che "ponte" tra i due sistemi.

---

### PROBLEMATICHE DA FAR EMERGERE

#### 1. Concorrenza

**Domanda:** "Due medici modificano contemporaneamente la stessa cartella. Cosa succede?"

**Possibili soluzioni:**
- Lock pessimistico (chi apre per primo blocca)
- Lock ottimistico (controllo versione prima di salvare)
- Merge delle modifiche (se su campi diversi)

---

#### 2. Tempo reale

**Domanda:** "Come garantire che tutti vedano dati aggiornati 'in tempo reale'?"

**Soluzioni:**
- Refresh automatico periodico
- WebSockets/notifiche push
- Timestamp "ultimo aggiornamento"

---

#### 3. Sicurezza

**Domanda:** "Tutti i medici possono vedere/modificare tutto?"

**Risposta:** NO! Serve matrice di permessi:

| Ruolo | Consulta | Modifica | Cancella |
|-------|----------|----------|----------|
| Medico curante | ✅ Tutto | ✅ Sue visite | ❌ |
| Medico PS | ✅ Info emergenza | ✅ Intervento PS | ❌ |
| Infermiere | ✅ Terapie | ✅ Parametri vitali | ❌ |
| Amministrativo | ✅ Anagrafica | ❌ | ❌ |

Il processo P5 controlla questi permessi!

---

#### 4. Prenotazione in linea

**Domanda:** "Se il paziente prenota dall'app, cambia il DFD?"

**Risposta:** Il processo logico (P1) è lo stesso, ma:
- **Canale diverso**: interfaccia web/mobile invece di operatore CUP
- **Entità:** Paziente interagisce direttamente con P1
- **Validazioni aggiuntive:** CAPTCHA, conferma email, ecc.

Potremmo rappresentare due frecce verso P1:
- Una da "Paziente (app)"
- Una da "Operatore CUP"

---

## COMPLETAMENTO SCHEDA (15 minuti)

Dopo aver costruito insieme i DFD alla lavagna, date tempo agli studenti di:

1. **Ridisegnare** i diagrammi sulla loro scheda
2. **Completare le tabelle** (entità, processi, archivi)
3. **Rispondere** alle domande di comprensione

**Girate tra i banchi** per verificare che stiano usando correttamente i simboli.

---

## CONFRONTO E DISCUSSIONE (10 minuti)

**Domande per la discussione finale:**

1. **"Qual è la differenza tra processo e archivio dati?"**
   - Processo = azione attiva (trasforma dati)
   - Archivio = contenitore passivo (memorizza dati)

2. **"Perché serve separare D1 (Prenotazioni) da D4 (Cartelle)?"**
   - Dati con scopi diversi
   - Livelli di sicurezza diversi
   - Cicli vita diversi (prenotazione si chiude, cartella resta)

3. **"Il DFD mostra l'ORDINE temporale delle azioni?"**
   - NO! Il DFD mostra COSA fluisce, non QUANDO
   - Per l'ordine servono altri diagrammi (diagrammi di sequenza, flowchart)

4. **"Abbiamo dimenticato qualcosa di importante?"**
   - Possibili aggiunte: notifiche, stampe, report, backup...

---

## COLLEGAMENTI CON FASI SUCCESSIVE

**Fate capire agli studenti che:**

📌 **Dal DFD al Database:**
- Gli archivi (D1, D2, D3...) diventeranno **tabelle** nel database
- I flussi indicano le **relazioni** (chiavi esterne)
- Es: D1 (Prenotazioni) avrà FK verso D2 (Medici) e D3 (Pazienti)

📌 **Dal DFD ai Casi d'Uso:**
- Ogni processo può diventare un **use case**
- Le entità esterne sono gli **attori**

📌 **Dal DFD all'Architettura:**
- I processi potrebbero diventare **microservizi** separati
- Gli archivi potrebbero essere **database diversi**

**Il DFD è un ponte** tra requisiti e progettazione!

---

## ERRORI COMUNI DEGLI STUDENTI

### ❌ Errore 1: Confondere entità e archivi
**Sbagliato:** Mettere "Paziente" come archivio dati
**Corretto:** Paziente è entità esterna, D3 è "Archivio Pazienti"

### ❌ Errore 2: Processi troppo vaghi
**Sbagliato:** "P1: Gestisci Sistema"
**Corretto:** "P1: Gestisci Prenotazione" (specifico!)

### ❌ Errore 3: Frecce senza etichette
**Sbagliato:** Paziente → P1 (freccia vuota)
**Corretto:** Paziente → P1 [Richiesta prenotazione + dati]

### ❌ Errore 4: Troppi dettagli troppo presto
Il DFD deve essere **ad alto livello** inizialmente. Evitate di mettere 20 processi alla prima iterazione.

**Suggerite:** Partire con 3-5 processi principali, poi raffinare.

---

## VALUTAZIONE PARTE 2 (DFD)

Usate la griglia aggiornata nella scheda studente. Valutate:

### ✅ Identificazione entità e processi (0-2 punti)
- Ha identificato le entità esterne corrette?
- Ha nominato i processi in modo chiaro?

### ✅ Archivi dati e flussi (0-2 punti)
- Ha identificato gli archivi necessari?
- Ha tracciato i flussi principali con le etichette?

### ✅ Integrazione tra sistemi (0-1 punto)
- Ha capito come Prenotazioni e Cartelle comunicano?

### ✅ Correttezza del diagramma (0-2 punti)
- Ha usato i simboli corretti?
- Il diagramma è leggibile e coerente?

### ✅ Problematiche identificate (0-1 punto)
- Ha riconosciuto le criticità (concorrenza, sicurezza...)?

**Totale Parte 2: /8 punti**
**Totale complessivo (Parte 1 + Parte 2): /18 punti**

---

## ATTIVITÀ DI APPROFONDIMENTO

Se avete tempo o per homework:

### 🔹 Livello base:
- Completare il DFD aggiungendo processo di "Gestione Referti"
- Aggiungere l'entità "Laboratorio Analisi"

### 🔹 Livello intermedio:
- Espandere il DFD di livello 0 in un **DFD di livello 1** per il processo P1
- Dettagliare cosa succede DENTRO "Gestisci Prenotazione"

### 🔹 Livello avanzato:
- Trasformare il DFD in un **diagramma ER** (Entità-Relazioni)
- Definire attributi e chiavi per ogni archivio
- Progettare lo schema del database

---

## MESSAGGIO CHIAVE - PARTE 2

**Fate capire che:**

🎯 **Il DFD non è "disegnare per disegnare"** - è uno strumento per:
- Chiarire i requisiti ambigui
- Comunicare con il cliente e il team
- Identificare problemi prima di programmare
- Progettare l'architettura del sistema

🎯 **Ogni freccia è una potenziale criticità**:
- Sicurezza: chi autorizza quel flusso?
- Performance: quanto è grande quel dato?
- Affidabilità: cosa succede se il flusso si interrompe?

🎯 **Il DFD evolve**: non si fa una volta sola, si raffina iterativamente man mano che si capisce meglio il sistema.

---

## RISORSE AGGIUNTIVE PER DFD

### Tool software (da mostrare o far usare):
- Draw.io / diagrams.net (gratuito, online)
- Lucidchart
- Visual Paradigm
- Microsoft Visio

### Standard di riferimento:
- Notazione Yourdon-DeMarco (quella usata qui)
- Notazione Gane-Sarson (variante con frecce curve)

### Video tutorial consigliati:
- Cercate "DFD tutorial" su YouTube
- Mostrate esempi di DFD di sistemi reali

---

**Buon lavoro con la Parte 2! La modellazione è una competenza chiave per ogni informatico.** 🎓📊
