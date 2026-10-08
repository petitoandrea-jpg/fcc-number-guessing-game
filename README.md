# fcc-number-guessing-game
Sviluppo di un gioco a premi su terminale integrato con un database relazionale per il tracciamento delle statistiche dei giocatori.

Caratteristiche principali:

Generazione di numeri pseudo-casuali tramite la variabile shell $RANDOM e controllo dei tentativi tramite cicli iterativi until/while.

Connessione al database PostgreSQL per salvare lo storico: rilevamento di giocatori nuovi o di ritorno tramite verifica dell'username.

Tracciamento delle partite totali giocate e calcolo del record personale (best game) con aggiornamento transazionale a ogni sessione conclusa.
