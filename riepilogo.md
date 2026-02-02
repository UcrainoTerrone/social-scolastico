# Riepilogo del lavoro svolto – ScuolaHub

## Introduzione
Il progetto **ScuolaHub** è una web application che simula un social scolastico, pensato per
migliorare la comunicazione e l’organizzazione della vita scolastica degli studenti.
Il lavoro è stato svolto seguendo le fasi del ciclo di sviluppo del software (SDLC),
con particolare attenzione all’organizzazione del codice e all’uso di Git.

---

## Organizzazione del lavoro
Il progetto è stato inizialmente realizzato come pagina HTML statica e successivamente
organizzato come repository Git.

La struttura principale del progetto è la seguente:
- `index.html`
- `README.md`
- `feature_bacheca.md`
- `riepilogo.md`

---

## Gestione del versionamento (Git)
Per simulare un ambiente di lavoro collaborativo è stato utilizzato **Git**.

Sono stati utilizzati i seguenti branch:
- **main**: branch principale contenente la versione stabile del progetto
- **feature_bacheca**: branch dedicato allo sviluppo della nuova funzionalità

Il branch della feature è stato successivamente unito al branch principale tramite merge.

---

## Implementazione della feature
La nuova funzionalità implementata è la **Bacheca dei rappresentanti**, che permette
ai rappresentanti di classe e d’istituto di pubblicare comunicazioni ufficiali visibili
a tutti gli studenti.

L’implementazione è stata realizzata in un branch dedicato e include:
- una nuova sezione HTML integrata nel layout principale
- gestione dinamica delle sezioni tramite JavaScript
- commenti nel codice per migliorare la leggibilità e la comprensione
- simulazione del ruolo utente (studente / rappresentante)

---

## Test della feature
Per verificare il corretto funzionamento della bacheca è stato eseguito un **test manuale**.

Il test ha previsto:
- accesso alla piattaforma
- navigazione verso la sezione “Bacheca”
- inserimento di una nuova comunicazione
- verifica della corretta visualizzazione del contenuto

Il test ha avuto esito positivo.

---

## Problemi incontrati e soluzioni
Durante lo sviluppo sono stati riscontrati alcuni problemi, tra cui:
- la mancata visualizzazione della sezione bacheca
- differenze tra branch locali e remoti (`main` / `master`)

I problemi sono stati risolti:
- posizionando correttamente la sezione all’interno del tag `<main>`
- allineando il branch principale locale con quello remoto

---

## Miglioramenti futuri
In futuro il progetto potrebbe essere migliorato con:
- integrazione di un backend e di un database
- sistema di notifiche per le nuove comunicazioni
- autenticazione reale degli utenti
- gestione avanzata dei ruoli e dei permessi

---

## Conclusione
Il progetto ha permesso di applicare in modo pratico le conoscenze di sviluppo web
e di gestione del versionamento, simulando un flusso di lavoro reale e organizzato.
