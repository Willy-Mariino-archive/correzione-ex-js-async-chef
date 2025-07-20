# Compleanno dello Chef – Modulo 1 Lezione 2

Questa repository contiene la **soluzione corretta** all’esercizio proposto durante la lezione, dedicato all’utilizzo di **JavaScript vanilla** per la gestione di chiamate API e manipolazione di oggetti.

> In questa versione, a differenza dell’esercizio precedente dove l’`userId` dello chef veniva selezionato manualmente (hardcodato), l’userID viene ora estratto automaticamente dalla ricetta tramite chiamata API, garantendo che venga sempre selezionato quello corretto e associato.

## Descrizione del progetto

L’obiettivo è recuperare la **data di nascita dello chef** associato a una ricetta, sfruttando le API di [dummyjson.com](https://dummyjson.com/). Il progetto mostra come:
- Effettuare chiamate asincrone con `fetch`
- Estrarre dati da oggetti JSON
- Collegare dati tra risorse diverse (ricetta → utente/chef)
- Gestire errori nelle chiamate API

## Funzionalità

- Recupero della ricetta tramite ID
- Estrazione dell’ID utente associato alla ricetta
- Recupero dei dati dello chef tramite l’ID utente
- Visualizzazione della data di nascita dello chef in console

