# Feature: Bacheca dei rappresentanti

## Nome della feature
Bacheca informativa dei rappresentanti di classe e d’istituto.

---

## Problema che risolve
Nella comunicazione scolastica le informazioni importanti (novità, avvisi, comunicazioni ufficiali)
vengono spesso diffuse in modo disorganizzato o tramite canali esterni, causando confusione o
mancata ricezione da parte degli studenti.

Questa feature risolve il problema offrendo una bacheca centralizzata e integrata nella piattaforma
scolastica.

---

## Descrizione del funzionamento
La bacheca è una sezione accessibile tramite il menu di navigazione.

Il funzionamento è il seguente:
- l’utente accede alla piattaforma tramite login simulato
- seleziona la voce “Bacheca” dal menu
- i rappresentanti possono inserire nuove comunicazioni
- ogni comunicazione viene visualizzata come un post nella bacheca
- gli studenti possono consultare le comunicazioni pubblicate

La funzionalità è simulata lato client e utilizza JavaScript per la gestione dinamica dei contenuti.

---

## Utenti coinvolti
La feature coinvolge due tipologie di utenti:
- **Rappresentanti**, che pubblicano comunicazioni e avvisi
- **Studenti**, che consultano la bacheca per rimanere aggiornati

---

## Limiti della feature
- Le comunicazioni non vengono salvate in modo permanente (assenza di database)
- Non è presente un sistema di notifiche automatiche
- Il controllo dei ruoli (studente/rappresentante) è simulato
- Non è prevista la modifica o cancellazione dei post

---

## Obiettivo della feature
L’obiettivo della bacheca è migliorare l’organizzazione e la trasparenza della comunicazione
scolastica, simulando il funzionamento di una piattaforma reale.
