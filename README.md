# Firefighter Water Drop Game

## Concept del Gioco

### Area di Gioco
- Rettangolo con proporzioni simili a uno schermo smartphone
- Orientamento verticale

### Personaggio Principale
- Un pompiere stilizzato 
- Posizionato nella parte bassa dello schermo
- Movimento limitato: solo destra e sinistra

### Meccanica di Sparo

#### Goccioline d'Acqua
- Numero di goccioline definito all'inizio di ogni livello
- Quantità variabile in base al livello di difficoltà
- Ogni gocciolina può spegnere una fiammella

#### Controllo del Getto
- Attivazione: tocco sullo schermo
- Angolazione del getto:
  - Stato iniziale: 0 gradi (orizzontale)
  - Mantenendo premuto: angolazione graduale fino a 90 gradi
  - Continuando a tenere premuto: ritorno graduale a 0 gradi
- Interruzione del tocco:
  - Blocco del cambiamento di angolazione
  - Goccioline continuano il loro percorso fino ad esaurimento

### Obiettivo del Gioco
- Spegnere tutte le fiammelle del livello
- Passaggio al livello successivo dopo aver eliminato tutte le fiamme

### Elementi di Gioco

#### Fiammelle
- Posizionate su piattaforme o oggetti
- Posizione e comportamento variano nei diversi livelli
- Ogni fiammella richiede una gocciolina per essere spenta

#### Fisica delle Goccioline
- Simulazione di comportamento realistico
- Capacità di:
  - Rimbalzare
  - Scivolare sugli oggetti
  - Interagire con l'ambiente di gioco

### Progressione
- Livelli a difficoltà crescente
- Variazioni possibili:
  - Numero di goccioline
  - Posizione e numero di fiammelle
  - Complessità delle piattaforme

## Specifiche Tecniche Previste
- Sviluppo con Phaser.js
- Gestione fisica con Matter.js
- Compatibilità: iOS e Android
- Grafica procedurale