# KIT DIDATTICO: Analisi Requisiti Software
## Intervista Ospedale San Leonardo

---

## 📋 CONTENUTO DEL KIT

Questo kit contiene tutto il materiale necessario per svolgere un'attività didattica completa sull'analisi dei requisiti software e modellazione DFD:

1. **1_COPIONE_INTERVISTA.md** - Script completo in 2 parti: intervista requisiti (15-20 min) + costruzione DFD (20-25 min)
2. **2_GUIDA_DOCENTE.md** - Guida completa con criticità, obiettivi didattici, suggerimenti per entrambe le parti
3. **3_SCHEDA_STUDENTE.md** - Scheda di lavoro strutturata con sezioni per requisiti e DFD
4. **4_SOLUZIONI_SUGGERITE.md** - Soluzioni di riferimento complete per i docenti

---

## 🎯 OBIETTIVO DELL'ATTIVITÀ

### PARTE 1 - Analisi Requisiti (Prima metà)
Far sperimentare agli studenti una situazione realistica di raccolta requisiti, evidenziando:
- Le difficoltà di comunicazione tra cliente e consulente tecnico
- Requisiti vaghi, ambigui, contrastanti
- Vincoli di tempo, budget e aspettative irrealistiche
- L'importanza di porre le domande giuste
- La gestione dello scope creep

### PARTE 2 - Modellazione DFD (Seconda metà)
Far costruire attivamente un Data Flow Diagram per:
- Modellare i processi del sistema (Prenotazioni e Cartella Clinica)
- Identificare entità esterne, processi, archivi dati e flussi
- Comprendere le relazioni e integrazioni tra sottosistemi
- Far emergere problematiche tecniche (concorrenza, sicurezza)
- Preparare il terreno per la progettazione del database

---

## 👥 DESTINATARI

Studenti di **classe 5ª superiore** (Informatica, Sistemi Informativi, ecc.)

---

## ⏱️ DURATA COMPLESSIVA

**Circa 2 ore (può essere divisa in due lezioni successive):**

### PARTE 1 - Analisi Requisiti (60-75 minuti):
- 5 min: Introduzione all'attività
- 15-20 min: Intervista simulata (Parte 1)
- 10 min: Completamento scheda individuale (Parti 1-2)
- 15 min: Confronto in gruppi
- 20-25 min: Discussione plenaria sulle criticità

### PARTE 2 - Costruzione DFD (50-60 minuti):
- 5 min: Introduzione al DFD e legenda simboli
- 20-25 min: Costruzione guidata DFD (Parte 2 intervista)
- 15 min: Completamento scheda DFD individuale (Parte 7)
- 10 min: Confronto diagrammi e discussione

### OPZIONE: Sintesi teorica finale (15 min)
- Collegamento con ingegneria del software
- Tecniche di elicitazione requisiti
- Dal DFD al database

**💡 SUGGERIMENTO:** Potete dividere in 2 lezioni consecutive (Parte 1 + Parte 2) oppure svolgere tutto in un'unica mattinata (2 ore).

---

## 📝 PREPARAZIONE

### Prima della lezione:

1. **Stampare le schede studente** (una per studente) - ora include Parte 7 per DFD
2. **Leggere bene il copione COMPLETO** (ora ha 2 parti) e provarlo tra i due docenti
3. **Studiare la guida docente** per conoscere tutte le criticità + istruzioni per DFD
4. **Preparare lo spazio:** due sedie/scrivanie per simulare l'ufficio
5. **Preparare lavagna/LIM** per disegnare il DFD insieme nella Parte 2

### Materiali necessari:

- ⬜ Copie della scheda studente aggiornata (n° studenti)
- ⬜ Penne/matite + **pennarelli colorati** per DFD
- ⬜ Lavagna o LIM per disegnare DFD collaborativamente
- ⬜ Proiettore (se volete mostrare esempi di DFD)
- ⬜ (Opzionale) Costumi/props per rendere più realistica la scenetta
- ⬜ (Opzionale) Post-it colorati per costruzione DFD interattiva

---

## 🎭 SVOLGIMENTO STEP-BY-STEP

### FASE 1: Introduzione (5 minuti)

**Cosa dire agli studenti:**

> "Oggi assisterete a un colloquio tra un cliente (il direttore di un ospedale) e un consulente informatico. Il vostro compito non è solo ascoltare, ma **lavorare come analisti di requisiti**. Dovrete:
> - Identificare i requisiti del sistema informatico richiesto
> - Distinguere tra requisiti funzionali e non funzionali  
> - Riconoscere i problemi e le criticità che emergono
> - Proporre soluzioni
>
> Durante l'intervista, prendete appunti liberamente sul retro della scheda. Poi avrete tempo per compilarla con calma."

**Distribuite le schede** e date 2 minuti per leggerle velocemente.

---

### FASE 2: Intervista Simulata (15-20 minuti)

**IMPORTANTE:**
- Recitate l'intervista in modo **naturalistico**, non come lettura meccanica
- Potete aggiungere piccole variazioni per renderla più credibile
- Non esagerate con la recitazione: deve sembrare una vera riunione di lavoro
- Mantenete il contatto visivo reciproco, non guardare sempre gli studenti

**Consigli di recitazione:**

**Dr. Martinelli (Dirigente):**
- Entusiasta ma confuso
- Interrompe a volte
- Parla di tecnologia senza capirla davvero
- Mostra urgenza e preoccupazione per i tempi
- Cordiale ma un po' pressante

**Ing. Rossi (Consulente):**
- Paziente e professionale
- Prende appunti
- Fa domande chiarificatrici
- Educato anche quando il cliente dice cose irrealistiche
- Cerca di riportare il cliente alla realtà senza offenderlo

---

### FASE 3: Completamento Individuale (10 minuti)

Appena finita l'intervista:

> "Avete 10 minuti per completare **almeno le parti 1 e 2** della scheda. Non preoccupatevi se non riuscite a finire tutto, completerete dopo la discussione."

**Gli studenti lavorano in silenzio** - girate tra i banchi per vedere come procedono.

---

### FASE 4: Confronto in Gruppi (15 minuti)

Dividete la classe in gruppi di 3-4 studenti:

> "Confrontate le vostre schede:
> - Quali requisiti avete identificato tutti?
> - Quali requisiti ha trovato qualcuno ma altri no?
> - Su quali criticità siete d'accordo?
> - Preparate 2-3 domande o osservazioni per la discussione plenaria."

**Nominare un portavoce** per gruppo.

---

### FASE 5: Discussione Plenaria (25 minuti)

Guidate la discussione con queste domande:

#### Round 1: Requisiti (10 minuti)
1. "Quali requisiti **funzionali** avete identificato come prioritari?"
2. "E quali **non funzionali**?"
3. "Quali erano chiari? Quali ambigui?"

➡️ Raccogliete alla lavagna/LIM una lista condivisa

#### Round 2: Criticità (10 minuti)
4. "Quali problemi avete notato nell'intervista?"
5. "Il Dr. Martinelli era un cliente difficile secondo voi? Perché?"
6. "E il consulente ha fatto un buon lavoro? Cosa avrebbe dovuto fare diversamente?"

➡️ Fate emergere le 6 criticità principali (vedi guida docente)

#### Round 3: Soluzioni (5 minuti)
7. "Come gestireste voi questo progetto?"
8. "Cosa mettereste nella Fase 1 e cosa rimandereste dopo?"

---

### FASE 6: Collegamento con la Teoria (15 minuti)

A questo punto **sistematizzate** quanto emerso:

**Concetti chiave da spiegare:**

1. **Requisito software:** Condizione o capacità di cui un utente ha bisogno per risolvere un problema o raggiungere un obiettivo

2. **Requisiti Funzionali vs Non Funzionali:**
   - **Funzionali:** COSA deve fare (es: "Il sistema deve gestire prenotazioni")
   - **Non funzionali:** COME deve farlo (es: "Deve rispondere in <2 secondi")

3. **Caratteristiche di un buon requisito:**
   - Chiaro e non ambiguo
   - Completo
   - Verificabile/testabile
   - Fattibile
   - Necessario
   - Prioritizzato

4. **Tecniche di elicitazione:**
   - Interviste (come oggi)
   - Questionari
   - Osservazione
   - Analisi documenti
   - Prototipazione
   - Workshop

5. **Gestione delle criticità:**
   - Change management
   - Prioritizzazione (MoSCoW)
   - Comunicazione efficace
   - Gestione aspettative

**Potete usare esempi dall'intervista** per ogni concetto.

---

---

# PARTE 2: COSTRUZIONE DEL DFD

**💡 Se volete dividere in 2 lezioni, questa parte può essere svolta nella lezione successiva.**

---

### FASE 7: Introduzione al DFD (5 minuti)

**Cosa dire agli studenti:**

> "Ora che abbiamo raccolto i requisiti, dobbiamo **modellare il sistema**. Per farlo useremo il DFD - Data Flow Diagram - che mostra chi fa cosa, quali dati fluiscono e dove si salvano. 
> 
> Assisterete alla seconda parte dell'intervista dove, insieme al consulente, costruirete il DFD per il sistema di prenotazione e la cartella clinica."

**Disegnate la LEGENDA sulla lavagna:**
- 🔲 Rettangolo = Entità esterna (Paziente, Medico)
- ⭕ Cerchio = Processo (P1, P2, P3...)
- 📦 Rettangolo doppio = Archivio dati (D1, D2, D3...)
- ➡️ Freccia = Flusso di dati

---

### FASE 8: Intervista Parte 2 - Costruzione Guidata DFD (20-25 minuti)

**Recitate la Parte 2 del copione** (dal file 1_COPIONE_INTERVISTA.md)

**IMPORTANTE:**
- **Fate PARTECIPARE gli studenti:** quando il copione dice `[PAUSA - I ragazzi rispondono]`, aspettate le risposte!
- **Disegnate insieme alla lavagna** man mano che procedete
- **Usate colori diversi:** es. blu per entità, rosso per processi, verde per archivi
- L'Ing. Rossi guida la costruzione facendo domande, gli studenti collaborano

**Cosa costruirete insieme:**
1. DFD Sistema Prenotazioni (entità, processi P1-P2, archivi D1-D2-D3, flussi)
2. DFD Cartella Clinica (entità, processi P3-P4-P5, archivi D4-D5, flussi)
3. Integrazione tra i due sistemi (processo P6)
4. Problematiche (concorrenza, tempo reale, sicurezza)

---

### FASE 9: Completamento Scheda DFD (15 minuti)

Dopo aver costruito insieme alla lavagna:

> "Ora avete 15 minuti per completare la **Parte 7 della vostra scheda**:
> - Ridisegnate i DFD sul vostro foglio
> - Compilate le tabelle (entità, processi, archivi, flussi)
> - Rispondete alle domande di comprensione"

**Gli studenti lavorano individualmente** - il diagramma alla lavagna resta visibile come riferimento.

**Girate tra i banchi** per verificare:
- Che usino i simboli corretti
- Che le frecce abbiano etichette (non frecce vuote!)
- Che distinguano entità da archivi

---

### FASE 10: Confronto e Discussione DFD (10 minuti)

**Confronto rapido in coppie/terzetti (5 min):**
- "Confrontate i vostri diagrammi con il compagno vicino"
- "Avete disegnato le stesse cose? Quali differenze?"

**Discussione plenaria (5 min):**

Domande chiave:

1. **"Qual è la differenza tra un'entità esterna e un archivio dati?"**
   - Studenti devono capire: entità = attore FUORI, archivio = dati DENTRO

2. **"Perché abbiamo separato D1 (Prenotazioni) da D4 (Cartelle)?  Non potevano essere un unico archivio?"**
   - Scopi diversi, sicurezza diversa, cicli vita diversi

3. **"Il DFD ci dice QUANDO succedono le cose? L'ordine temporale?"**
   - NO! Il DFD dice COSA fluisce, non QUANDO

4. **"Quali problemi tecnici avete identificato?"**
   - Concorrenza, tempo reale, sicurezza accessi, integrazione

**Collegate al futuro:**
- "Questi archivi diventeranno **tabelle nel database** che progetterete!"
- "I processi potrebbero diventare **microservizi** in un'architettura distribuita!"

---

### FASE 11: Chiusura e Sintesi (5 minuti)

**Messaggio finale:**

> "Avete fatto un lavoro completo: dalla raccolta requisiti alla modellazione dei processi. Questo è esattamente ciò che fa un analista professionista!
> 
> **Ricordate:** Il DFD non è "disegnare per disegnare" - è uno strumento per:
> - Chiarire requisiti ambigui
> - Comunicare con cliente e team
> - Identificare problemi PRIMA di programmare
> - Progettare l'architettura del sistema
>
> Ogni freccia che avete disegnato rappresenta dati che viaggeranno nel sistema: pensate a sicurezza, prestazioni, affidabilità!"

**Compiti a casa (opzionali - in aggiunta ai precedenti):**

⬜ **Opzione 5 (DFD):** Espandere il DFD: aggiungere il sistema "Gestione Referti" (Laboratorio, Radiologia)

⬜ **Opzione 6 (DFD):** Dettagliare il processo P1 in un DFD di Livello 1 (cosa succede DENTRO "Gestisci Prenotazione"?)

⬜ **Opzione 7 (Database):** Trasformare gli archivi D1-D5 in uno schema ER (Entità-Relazioni) con attributi e chiavi

**Raccogliete le schede complete** per la valutazione (ora valutazione su 18 punti: 10 per Parte 1 + 8 per Parte 2 DFD).

---

---

## 💡 CONSIGLI PRATICI

### Cosa fare se...

**Gli studenti faticano a identificare i requisiti (Parte 1):**
- Fermate l'intervista dopo 5-7 minuti e chiedete "Fino ad ora, cosa deve fare il sistema?"
- Riavviate l'intervista

**La discussione langue:**
- Fate domande più specifiche: "In quale momento il cliente ha detto qualcosa di poco chiaro?"
- Mostrate un esempio concreto dall'intervista

**Gli studenti si focalizzano solo sui requisiti funzionali:**
- Chiedete esplicitamente: "Il sistema deve essere veloce? Sicuro? Facile da usare? Questi che requisiti sono?"

**Gli studenti confondono entità e archivi (Parte 2 DFD):**
- Ribadite: "Il Paziente è fuori dal sistema (entità), i dati DEL paziente stanno dentro (archivio D3)"
- Usate analogia: "Il cuoco (entità) vs la ricetta scritta (archivio)"

**I diagrammi sono illeggibili:**
- Suggerite: "Disegnate prima a matita, poi ripassate"
- "Lasciate spazio tra gli elementi, non ammassate tutto"

**Non riescono a far stare tutto nel foglio:**
- "Va bene disegnare sul retro o su un foglio allegato"
- "Oppure dividete: un diagramma per Prenotazioni, uno per Cartelle"

**Finisce il tempo:**
- Prioritizzate: meglio fare bene Fasi 1-2-5-6 che fare tutto di corsa
- La discussione plenaria è la parte più formativa

---

## 📊 VALUTAZIONE

### Valutazione formativa (durante l'attività):
- Osservate chi partecipa attivamente (sia in Parte 1 che Parte 2)
- Chi fa domande pertinenti e contribuisce alla costruzione del DFD
- Chi aiuta il gruppo durante i confronti

### Valutazione sommativa (dalla scheda):

Usate la griglia aggiornata in fondo alla scheda studente:

#### PARTE 1 - Analisi Requisiti (/10 punti):
- Completezza requisiti identificati: 3 punti
- Riconoscimento criticità: 3 punti
- Distinzione funzionali/non-funzionali: 2 punti
- Proposte di soluzione: 2 punti

#### PARTE 2 - DFD (/8 punti):
- Identificazione entità e processi: 2 punti
- Archivi dati e flussi: 2 punti
- Integrazione tra sistemi: 1 punto
- Correttezza del diagramma: 2 punti
- Problematiche identificate: 1 punto

**TOTALE COMPLESSIVO: 18 punti**

### Criteri di eccellenza (voto 9-10):

**Parte 1:**
- Ha identificato almeno 8-10 requisiti funzionali
- Ha identificato almeno 4-5 requisiti non funzionali
- Ha riconosciuto almeno 4-5 delle 6 criticità principali
- Ha proposto soluzioni realistiche e ben motivate
- Ha distinto correttamente funzionali da non funzionali

**Parte 2:**
- Ha disegnato DFD completi e corretti con simboli standard
- Ha identificato tutte le entità principali (Paziente, Medico, CUP)
- Ha identificato i processi chiave (P1-P6)
- Ha compreso l'integrazione tra Prenotazioni e Cartelle
- Ha proposto soluzioni tecniche alle problematiche (concorrenza, sicurezza)

### Soglia di sufficienza (6) - almeno:
- 6-7 requisiti funzionali identificati
- 2-3 requisiti non funzionali
- 2-3 criticità riconosciute
- DFD con elementi base (almeno 2-3 processi, 2 archivi)
- Simboli usati anche se con qualche imprecisione

---

## 🔗 COLLEGAMENTI INTERDISCIPLINARI

### Informatica:
- Ingegneria del software
- Basi di dati (progettazione)
- Sistemi e reti
- Tecnologie web

### Altre materie:
- **TPSIT:** Gestione progetti
- **Economia aziendale:** Analisi costi-benefici, budget
- **Italiano:** Comunicazione efficace, documenti tecnici
- **Diritto:** GDPR, normative sanitarie
- **Inglese:** Terminologia tecnica IT

---

## 📚 APPROFONDIMENTI (per docenti)

### Standard e metodologie:
- **IEEE 830:** Standard per Specifiche Requisiti Software
- **ISO/IEC 25010:** Qualità del software
- **Agile/Scrum:** User Stories e Product Backlog
- **UML:** Use Case Diagram per requisiti

### Bibliografia:
- Sommerville, "Ingegneria del Software"
- Wiegers & Beatty, "Software Requirements"
- Pressman, "Principi di Ingegneria del Software"

### Caso reale famoso:
- **Healthcare.gov (2013):** Il portale USA per l'assicurazione sanitaria fallì al lancio proprio per requisiti mal gestiti, interfacce complesse, e tempistiche irrealistiche. Costò centinaia di milioni in più del previsto.

---

## ✅ CHECKLIST PRE-ATTIVITÀ

**Una settimana prima:**
- ⬜ Fotocopiare schede studente
- ⬜ Leggere e provare copione tra i due docenti
- ⬜ Studiare guida docente

**Il giorno prima:**
- ⬜ Preparare l'aula (disposizione per intervista)
- ⬜ Verificare di avere materiali sufficienti
- ⬜ Decidere composizione gruppi (se non casuale)

**All'inizio della lezione:**
- ⬜ Spiegare obiettivi e modalità
- ⬜ Distribuire schede
- ⬜ Dare 2 minuti per lettura rapida

---

## 📧 FEEDBACK E MIGLIORAMENTI

Dopo aver svolto l'attività, prendete nota di:
- Cosa ha funzionato bene?
- Cosa modifichereste?
- Quanto tempo avete effettivamente impiegato?
- Quali domande degli studenti non avevate previsto?

Questo vi aiuterà a migliorare l'attività per le classi future.

---

## 🎓 MESSAGGI CHIAVE DA TRASMETTERE

Concludete l'attività assicurandovi che gli studenti abbiano compreso:

### PARTE 1 - Analisi Requisiti:
1. ✅ L'analisi requisiti è una fase **critica** e spesso **sottovalutata**
2. ✅ I problemi di comunicazione sono **normali** e vanno **gestiti attivamente**
3. ✅ Requisiti vaghi sono **pericolosi** quanto requisiti sbagliati
4. ✅ Un bravo tecnico non è solo competente, ma sa anche **comunicare e mediare**
5. ✅ Errori nella fase di analisi costano **10-100 volte di più** se scoperti dopo
6. ✅ Non esiste "il cliente perfetto": saper gestire clienti difficili è una **competenza professionale**

### PARTE 2 - Modellazione DFD:
7. ✅ Il DFD non è "disegnare per disegnare" - è uno strumento per **chiarire e comunicare**
8. ✅ Ogni freccia (flusso di dati) è una **potenziale criticità** (sicurezza, performance, affidabilità)
9. ✅ Gli archivi del DFD diventeranno **tabelle nel database** - stiamo già progettando!
10. ✅ Il DFD **evolve iterativamente** - non si fa una volta sola e poi è perfetto
11. ✅ **Identificare i problemi prima di programmare** fa risparmiare tempo e denaro
12. ✅ La modellazione è una **competenza chiave** per ogni informatico, non solo teoria

**SINTESI FINALE:** Un progetto IT ha successo non solo per la tecnologia, ma per quanto bene si comprendono i bisogni reali del cliente E si modella correttamente il sistema prima di svilupparlo.

---

## 📞 SUPPORTO

Per domande o suggerimenti su questo kit didattico, potete contattarvi tra colleghi o condividere l'esperienza in comunità di docenti.

---

**Buona lezione! 🎉**

---

**Versione:** 2.0 (con Parte 2 - DFD)  
**Data creazione:** 5 Febbraio 2026  
**Ultima revisione:** 5 Febbraio 2026 (aggiunta Parte DFD)  
**Autore:** Kit didattico per Gestione Progetti - Analisi Requisiti Software e Modellazione DFD
