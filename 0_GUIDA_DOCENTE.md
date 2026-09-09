# GUIDA PER I DOCENTI
## Intervista ospedale san Leonardo - Analisi dei requisiti

---

## OBIETTIVI DIDATTICI

L'attività intende far riflettere gli studenti su alcuni aspetti chiave dello sviluppo software:
1. Le difficoltà che si incontrano quando si raccolgono i requisiti sul campo
2. La distinzione tra requisiti funzionali e non funzionali
3. L'importanza di una comunicazione chiara tra cliente e informatico
4. I problemi che possono far slittare o fallire un progetto IT
5. Come gestire le aspettative di chi commissiona il lavoro tenendo conto dei vincoli reali

---

## CRITICITÀ EMERSE NELL'INTERVISTA

### 1. Requisiti vaghi e ambigui

**Dove emerge:**
* "Sistema moderno, efficiente... che funzioni bene"
* "Ottimizzare gli appuntamenti"
* "Interfaccia intuitiva" (es. mia zia di 70 anni...)
* "App con tutte le funzionalità"

**Cosa far notare:**
* Gli aggettivi generici non indicano cosa deve fare il programma.
* Bisogna definire in modo concreto cosa si intende per "ottimizzare" o "efficiente".
* La facilità d'uso è un concetto soggettivo: servono parametri oggettivi per misurarla.
* L'espressione "tutte le funzionalità" non permette di stabilire i confini del progetto.

**Domande per gli studenti:**
* Come trasformereste l'idea di sistema "efficiente" in un requisito misurabile?
* Quali domande specifiche avrebbe dovuto porre l'analista per chiarire l'obiettivo di "ottimizzare"?

---

### 2. Conflitto tra budget e funzionalità

**Dove emerge:**
* Budget di 80.000 € per un sistema completo con intelligenza artificiale, app per dispositivi mobili e varie integrazioni
* L'idea errata che "la tecnologia ormai costa poco"
* L'aspettativa di usare software gratuito per esigenze aziendali complesse

**Cosa far notare:**
* Spesso il cliente non ha un'idea reale di quanto costi sviluppare e integrare software.
* C'è una distanza netta tra le aspettative del committente e la fattibilità economica.
* Un software open source o gratuito non azzera i costi di configurazione, personalizzazione e manutenzione.
* Con un budget prefissato è indispensabile stabilire delle priorità ed eliminare il superfluo.

**Domande per gli studenti:**
* Se doveste rientrare in quella cifra, quali moduli o funzioni tagliereste per primi?
* In che modo spieghereste al cliente che il budget indicato non copre tutte le sue richieste?

---

### 3. Aspettative irrealistiche

**Dove emerge:**
* Un sistema di intelligenza artificiale che suggerisce diagnosi automatiche
* La pretesa di avere tutto pronto in 6 mesi
* L'integrazione immediata e automatica con qualsiasi sistema esterno
* L'idea di affidare la sicurezza della rete al parente appassionato di informatica

**Cosa far notare:**
* Un software medico basato su intelligenza artificiale richiede iter approvativi lunghi, validazioni cliniche e rigidi controlli normativi.
* I tempi reali di sviluppo e collaudo spesso non coincidono con le scadenze desiderate dalla direzione.
* Integrare sistemi diversi richiede tempo, analisi delle API e accordi con fornitori terzi.
* La protezione dei dati sanitari richiede competenze professionali dedicate e adempimenti legali precisi.

**Domande per gli studenti:**
* Perché l'implementazione di un supporto alla diagnosi è molto più complessa di una semplice ricerca online?
* Quali rischi si corrono a rincorrere scadenze troppo strette su un sistema di questo tipo?

---

### 4. Requisiti in contrasto tra loro

**Dove emerge:**
* La richiesta di un "sistema unico e integrato" affiancata dalla volontà di lasciare che "ognuno continui a usare i propri programmi"
* L'aspirazione all'innovazione scontrata con limiti di spesa stringenti
* La pretesa di avere il prodotto subito accompagnata dalla disponibilità a "rinviare qualcosa"
* La ricerca contemporanea di massima sicurezza, massima velocità e costo minimo

**Cosa far notare:**
* Molto spesso i clienti esprimono desideri tra loro incompatibili.
* Il lavoro dell'analista consiste nel far emergere queste incongruenze e guidare il cliente verso un compromesso praticabile.
* Bisogna far capire che non si può ottenere tutto contemporaneamente senza rinunciare a qualcosa in termini di tempi, costi o qualità.

**Domande per gli studenti:**
* Quali soluzioni di compromesso proporreste per conciliare l'integrazione dei dati con le abitudini del personale?
* Come definireste un ordine di priorità condivisibile tra le varie richieste?

---

### 5. Difficoltà di comunicazione tra tecnici e non tecnici

**Dove emerge:**
* Dubbi del cliente su termini come "interfaccia"
* Incomprensioni su acronimi di settore (FSE, PACS)
* Indecisione tra soluzioni in locale o in cloud basata solo sul fattore prezzo

**Cosa far notare:**
* L'uso di termini specialistici rischia di bloccare il dialogo e generare equivoci.
* Chi si occupa dell'analisi deve saper spiegare i concetti tecnici in modo semplice e accessibile.
* Il cliente deve sentirsi a proprio agio nel segnalare ciò che non gli è chiaro.
* Serve un atteggiamento d'ascolto e la disponibilità a chiarire ogni dettaglio.

**Domande per gli studenti:**
* Come spieghereste a un operatore sanitario cos'è un punto di integrazione o un'interfaccia tra due programmi?
* In quali momenti dell'intervista è opportuno introdurre termini tecnici e quando è meglio evitarli?

---

### 6. Modifica continua delle richieste

**Dove emerge:**
* L'introduzione estemporanea di nuovi bisogni nel corso della conversazione (es. l'accesso da remoto)
* Il continuo cambio di prospettiva sulle funzionalità indispensabili rispetto a quelle secondarie

**Cosa far notare:**
* Durante la discussione il cliente prende consapevolezza di esigenze a cui non aveva pensato prima.
* È normale che le richieste aumentino man mano che si approfondisce il problema, ma questo fenomeno va controllato.
* Occorre adottare un metodo strutturato per raccogliere, valutare e formalizzare gli interventi aggiuntivi.
* Trascurare la documentazione scritta porta a incomprensioni e contestazioni sulle consegne.

**Domande per gli studenti:**
* Quali accorgimenti adottereste per evitare che le richieste continuino ad aumentare senza controllo?
* Con quale procedura gestireste l'inserimento di una nuova funzionalità emersa a progetto avviato?

---

## ALTRI ASPETTI CRITICI DA EVIDENZIARE

### 7. Coinvolgimento parziale degli interlocutori
* L'intervista è stata condotta soltanto con il direttore sanitario.
* Mancano le posizioni di medici, infermieri, addetti allo sportello, tecnici informatici e amministrativi.
* Questo porta a una visione parziale delle reali esigenze quotidiane dell'ospedale.

### 8. Assenza di un'analisi preliminare
* L'incontro è avvenuto senza materiale preparatorio o schemi dei processi attuali.
* Non è stato svolto uno studio di fattibilità informale prima del colloquio.

### 9. Vincoli normativi e operativi non dichiarati subito
* Scadenze fisse imposte dall'alto.
* Esigenza di dialogare con piattaforme esterne emersa solo a colloquio inoltrato.
* Necessità di rispettare le normative sulla privacy e sulla protezione dei dati personali.

### 10. Delega totale delle decisioni
* L'atteggiamento del cliente che rimette ogni scelta al consulente ("faccia lei, è l'esperto").
* La mancanza di una presa di responsabilità diretta da parte della struttura sanitaria sulle scelte operative.

---

## CONDUZIONE DELLA LEZIONE IN CLASSE

### Fase 1: Intervista 
Intervista seguendo il copione in [1_COPIONE_INTERVISTA](1_COPIONE_INTERVISTA)
Si spiega ai ragazzi che dovranno prendere appunti e raccogliere quali sono i requisiti del sistema
Durante l'intervista i ragazzi inoltre potranno intervenire e dialogare con il cliente.

### Fase 2: Lavoro di gruppo
* Si dividono gli studenti in piccoli gruppi di 3 o 4 persone.
* Ogni gruppo confronta le criticità individuate e sintetizza un elenco condiviso.

### Fase 3: Discussione generale 

**Spunti per il dibattito:**
1. Quali richieste vi sembrano chiare e quali sono scritte in modo ambiguo?
2. Quali errori di valutazione ha commesso il committente?
3. Se aveste condotto voi l'intervista, come vi sareste comportati nei punti più critici?
4. L'atteggiamento di questo cliente è un caso isolato o rispecchia situazioni frequenti nella realtà lavorativa?

### Fase 4: Quadro teorico 
* Definizione formale del concetto di requisito
* Differenza tra requisiti funzionali e requisiti non funzionali
* Far svolgere ai ragazzi la [SCHEDA_STUDENTE](2_SCHEDA_STUDENTE.md)
* Metodi per raccogliere le informazioni dai clienti
* Tecniche per concordare obiettivi e priorità

### Fase 5: Esercitazione pratica 
Fornire agli studenti la scheda cartacea dell'intervista.
Chiedere agli studenti di rielaborare da 3 a 5 frasi dell'intervista trasformandole in requisiti ben definiti:
* Formulazione chiara, precisa e verificabile
* Distinzione tra aspetti funzionali e vincoli tecnici
* Assegnazione di un livello di priorità
* Indicazione delle eventuali dipendenze da altri sistemi

---

## STRATEGIE PER RISOLVERE LE CRITICITÀ

Di seguito alcuni spunti da analizzare insieme agli studenti per rispondere ai problemi emersi:

### Per i requisiti vaghi
* Chiedere esempi pratici di utilizzo quotidiano.
* Definire parametri oggettivi di valutazione (es. "il sistema deve completare la ricerca in meno di due secondi").
* Mostrare bozze grafiche o prototipi dell'interfaccia per raccogliere riscontri immediati.

### Per i problemi di budget
* Classificare le funzionalità in base alla loro reale necessità (indispensabili, utili, secondarie, rinunciabili).
* Proporre uno sviluppo per fasi successive, realizzando prima una versione base del software.
* Presentare opzioni alternative illustrando chiaramente costi, vantaggi e rinunce per ciascuna.

### Per le aspettative irrealistiche
* Mostrare dati di fatto sui tempi e sulle difficoltà di realizzazione di determinate tecnologie.
* Spiegare i passaggi tecnici indispensabili prima di poter integrare moduli complessi.
* Evidenziare i rischi operativi e legali legati a scelte affrettate.

### Per le incomprensioni comunicative
* Creare un piccolo vocabolario dei termini usati nel progetto, condiviso tra le parti.
* Accompagnare le spiegazioni con schemi, mappe e diagrammi visuali.
* Verificare periodicamente che quanto detto sia stato compreso nello stesso modo da tutti.

### Per la gestione delle modifiche (Change Management)
* Stabilire fin da subito che ogni nuova richiesta comporta una revisione di tempi e costi.
* Mantenere un documento scritto con lo storico delle decisioni prese e approvate.

---

## COLLEGAMENTI CON LE MATERIE DI STUDIO

L'attività si presta a richiamare diversi argomenti del percorso scolastico:
* **Informatica e Ingegneria del software:** le fasi di analisi, la stesura delle specifiche e il ciclo di vita delle applicazioni
* **Gestione progetti:** la relazione tra tempi, costi e risorse disponibili
* **Basi di dati:** l'individuazione delle informazioni da memorizzare e delle relative strutture
* **Sistemi e reti:** le architetture applicative, la scelta tra soluzioni locali o in cloud e l'integrazione tra piattaforme
* **Sicurezza e normative:** la gestione dei dati personali, il GDPR e la tutela delle informazioni sensibili

---

## VALUTAZIONE

I criteri da considerare per la valutazione dell'attività sono:
* **Accuratezza nell'analisi:** capacità di individuare le richieste fondamentali presenti nel testo
* **Spirito critico:** capacità di cogliere le incongruenze, i rischi e le omissioni dell'intervista
* **Classificazione:** correttezza nel distinguere tra funzioni del sistema e vincoli tecnici o gestionali
* **Qualità delle soluzioni:** efficacia e praticabilità delle contromisure proposte
* **Chiarezza ed esposizione:** qualità dell'apporto personale durante le fasi di lavoro di gruppo e di discussione
---

## NOTA CONCLUSIVA PER IL DOCENTE

È utile ribadire agli studenti che la maggior parte dei problemi nei progetti informatici non deriva da errori di programmazione, ma da un'incomprensione iniziale di ciò che il software avrebbe dovuto fare. Imparare a porre le domande giuste e a documentare con precisione le risposte è una competenza fondamentale per chiunque voglia lavorare nel settore tecnologico.

---
---

# PARTE 2: GUIDA ALLA COSTRUZIONE DEL DFD

## OBIETTIVI DIDATTICI - PARTE 2

La seconda parte dell'attività è dedicata alla modellazione concettuale del sistema tramite i diagrammi di flusso dati (Data Flow Diagram):
1. Schematizzare il passaggio delle informazioni all'interno dell'applicazione
2. Riconoscere i componenti base della notazione: entità esterne, processi, archivi dati e flussi
3. Comprendere come interagiscono tra loro i diversi moduli dell'applicazione
4. Far emergere questioni di progettazione come l'accesso simultaneo ai dati, la sicurezza e il passaggio dei dati tra moduli
5. Preparare il lavoro per la successiva progettazione della base di dati

---

## ORGANIZZAZIONE DELLA LEZIONE

### Strumenti consigliati:
* Spazio alla lavagna o schermo interattivo
* Colori differenti per evidenziare i vari elementi dello schema (es. un colore per gli attori esterni, uno per i processi, uno per gli archivi)
* Scheda di lavoro per gli studenti [SCHEDA_STUDENTE](2_SCHEDA_STUDENTE.md)

### Convenzioni grafiche per il DFD:

| Elemento | Simbolo | Significato |
| :--- | :--- | :--- |
| **Entità esterna** | Rettangolo | Chi interagisce con il sistema dall'esterno (Paziente, Operatore, Medico) |
| **Processo** | Cerchio o ovale | Un'elaborazione o trasformazione dei dati (indicato con una sigla come P1, P2) |
| **Archivio dati** | Linee parallele o rettangolo aperto | Un punto in cui le informazioni vengono salvate in modo permanente (D1, D2) |
| **Flusso dati** | Freccia con etichetta | Il percorso compiuto dalle informazioni tra un elemento e l'altro |

---

## SVOLGIMENTO GUIDATO PASSO PASSO

### Introduzione (5 minuti)

Si spiega alla classe che, dopo aver raccolto le esigenze del cliente, occorre rappresentare graficamente come funzionerà il software. Per farlo si usano i diagrammi di flusso dati, concentrandosi in particolare su due aree principali: la gestione delle prenotazioni e la cartella clinica.

---

### MODULO PRENOTAZIONI

#### 1. Individuazione degli attori esterni
Chiedere alla classe chi sono i soggetti che inviano o ricevono informazioni dal modulo prenotazioni.
* Paziente
* Operatore dello sportello (CUP)
* Medico (per la gestione dei propri orari e disponibilità)

Si disegnano i relativi rettangoli alla lavagna.

#### 2. Definizione dei processi
Chiedere quali sono le operazioni principali che questo modulo deve eseguire.
* P1: Registra prenotazione
* P2: Gestisci o annulla prenotazione
* P3: Verifica disponibilità

Si sottolinea che i processi indicano un'azione e vanno descritti usando dei verbi. Si disegnano i cerchi corrispondenti.

#### 3. Individuazione degli archivi dati
Chiedere quali informazioni devono essere salvate nel sistema in modo permanente.
* D1: Archivio prenotazioni
* D2: Archivio medici e orari
* D3: Archivio anagrafico pazienti

Si mostra come rappresentare gli archivi con le linee parallele.

#### 4. Tracciamento dei flussi
Guidare gli studenti nel collegare i vari elementi con le frecce orientate, specificando chiaramente quali dati passano su ogni linea:
* Dal Paziente al processo P1 passa la richiesta di appuntamento con i dati personali e la prestazione richiesta.
* Il processo P1 consulta D3 per verificare la presenza dell'anagrafica del paziente.
* Il processo P1 interroga D2 per verificare le date e gli orari liberi per quel tipo di visita.
* Il processo P1 scrive la nuova registrazione nell'archivio D1.
* Dal processo P1 torna al Paziente la conferma con la data, l'ora e la sede dell'appuntamento.

---

### MODULO CARTELLA CLINICA

#### 1. Individuazione degli attori esterni
* Medico curante o di reparto
* Personale infermieristico
* Laboratorio o centro esami (che fornisce i referti)

#### 2. Definizione dei processi
* P4: Consulta cartella clinica
* P5: Aggiorna scheda sanitaria (inserimento visite, diagnosi o terapie)
* P6: Verifica identità e permessi di accesso

Si fa notare che il controllo degli accessi (P6) è un processo fondamentale che precede ogni altra operazione sui dati sanitari.

#### 3. Individuazione degli archivi dati
* D4: Archivio cartelle cliniche (storia medica, referti, prescrizioni)
* D5: Archivio utenti e autorizzazioni

**Spunto di discussione:** Perché è opportuno tenere separata l'anagrafica del paziente (D3) dai suoi dati clinici (D4)?
La separazione permette di gestire meglio la riservatezza delle informazioni, limitare gli accessi ai soli dati necessari per ciascun ruolo e strutturare in modo più ordinato il database.

#### 4. Tracciamento dei flussi
* Il Medico invia le proprie credenziali al processo P6, che controlla i permessi sull'archivio D5.
* Una volta ottenuta l'autorizzazione, il Medico richiede la consultazione della cartella tramite P4.
* Il processo P4 legge i dati da D4 e li mostra a schermo.
* Per inserire un nuovo referto, il processo P5 riceve i dati dal Medico o dal Laboratorio e aggiorna l'archivio D4.

---

### COLLEGAMENTO TRA I DUE MODULI

Chiedere agli studenti in quale momento le prenotazioni e le cartelle cliniche devono scambiare dati tra loro.

Un esempio tipico è l'accettazione del paziente il giorno della visita:
* Un processo dedicato (es. P7: Accettazione) legge la prenotazione da D1.
* Verifica o crea la cartella corrispondente in D4.
* Aggiorna lo stato della prenotazione in D1 per segnalare che il paziente è presente in struttura.

---

## TEMI TECNICI DA DISCUTERE CON LA CLASSE

### Accessi simultanei (Concorrenza)
Cosa succede se due operatori cercano di prenotare lo stesso posto nell'esatto medesimo istante, o se due medici aprono la stessa cartella clinica per modificarla?
Si introduce il concetto di blocco dei dati (lock) e la necessità di gestire gli accessi concorrenti per evitare sovrascritture o informazioni incoerenti.

### Riservatezza e profili di accesso
Non tutto il personale deve poter vedere le stesse informazioni. Si mostra come il processo di autorizzazione debba filtrare i dati in base al ruolo di chi si collega:

| Ruolo | Consulta | Modifica | Cancella |
| :--- | :--- | :--- | :--- |
| **Medico curante** | Tutto | Sue visite | No |
| **Medico PS** | Info emergenza | Intervento PS | No |
| **Infermiere** | Terapie | Parametri vitali | No |
| **Amministrativo** | Anagrafica | No | No |

### Canali di ingresso differenti
Se una prenotazione arriva tramite applicazione per smartphone anziché dallo sportello, la logica del processo non cambia: cambiano soltanto l'interfaccia usata e i controlli automatici da inserire all'ingresso (es. la verifica dell'indirizzo e-mail o del numero di cellulare).

---

## RIFLESSIONE FINALE CON GLI STUDENTI

Al termine dell'esercizio è utile richiamare l'attenzione su alcuni punti chiave:

1. **Il DFD non rappresenta la sequenza temporale:** Lo schema mostra da dove arrivano i dati, come vengono trasformati e dove finiscono, ma non indica l'ordine cronologico esatto delle operazioni (per quello si usano altri strumenti, come i diagrammi di sequenza).
2. **Corrispondenza con la base di dati:** Gli archivi individuati nello schema (D1, D2, D3...) rappresentano le future tabelle che verranno create nel database.
3. **Passaggio ai casi d'uso:** Ogni processo individuato nello schema principale rappresenta una funzione che il sistema dovrà mettere a disposizione dei suoi utenti.

---

## ERRORI FREQUENTI DA CORREGGERE

* **Confondere gli attori con gli archivi:** Ad esempio indicare "Paziente" come archivio invece che come soggetto esterno che invia informazioni.
* **Usare descrizioni troppo generiche per i processi:** Scrivere "Gestione Ospedale" anziché dividere l'operazione in funzioni più specifiche come "Registra appuntamento" o "Consulta referto".
* **Omettere la descrizione sui flussi:** Tracciare frecce senza indicare quali dati stanno viaggiando da un punto all'altro dello schema.
* **Disegnare connessioni dirette tra due archivi:** Un archivio dati non può comunicare direttamente con un altro archivio; il passaggio delle informazioni deve sempre avvenire attraverso un processo di elaborazione.

* ## RIEPILOGO PER I DOCENTI - PARTE 2

### Obiettivi della seconda parte:
- Far costruire attivamente un DFD (non solo ascoltare)
- Identificare: entità esterne, processi, archivi dati, flussi
- Capire le relazioni tra sottosistemi
- Introdurre problematiche di concorrenza, sicurezza, integrazione
- Preparare il terreno per la progettazione del database

### Cosa devono aver capito gli studenti:
- **Entità esterne**: chi usa il sistema (Paziente, Medico, CUP)
- **Processi**: cosa fa il sistema (Gestisci Prenotazione, Consulta Cartella, ecc.)
- **Archivi dati**: dove si memorizzano le informazioni
- **Flussi di dati**: quali informazioni scambiate tra processi e archivi
- **Integrazione**: come i sottosistemi comunicano

### Materiali necessari:
- Lavagna o proiettore per disegnare il DFD insieme
- Scheda studente con spazio per il disegno [SCHEDA_STUDENTE](2_SCHEDA_STUDENTE.md)
- Colori diversi per distinguere entità/processi/archivi

### Consigli pratici:
- **Fate disegnare gli studenti**, non solo voi!
- Usate convenzioni DFD standard (cerchi=processi, rettangoli=entità esterne, rettangoli doppi=archivi)
- Procedete per **iterazioni**: prima semplice, poi raffinate
- Valorizzate gli errori: "Bene! Avete individuato un problema..."

**NOTE PER I DOCENTI:** Alla fine della Parte 2, lasciate 15 minuti agli studenti per completare il disegno del DFD sulla loro scheda, poi fate confronto in gruppi.