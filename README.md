Carosello 3D Rotante

Questo progetto implementa un carosello di immagini tridimensionale, che ruota automaticamente per mostrare una galleria fotografica dinamica e accattivante. L'animazione e la disposizione delle immagini sono gestite interamente tramite le potenti funzionalità CSS.


Descrizione Approfondita del Progetto

Il carosello presenta una serie di immagini disposte in un cerchio virtuale che ruota continuamente. Questo effetto 3D è creato sfruttando le trasformazioni CSS (transform, rotateY, translateZ) e le animazioni con @keyframes. Ogni immagine, quando vi si passa sopra con il mouse, esegue una piccola animazione (translateY e scale) per attirare l'attenzione, dimostrando un'interazione fluida e puramente CSS-based.


Tecnologie Utilizzate

- HTML5: Struttura di base del carosello e contenitore delle immagini.

- Tailwind CSS: Utilizzato per utility class rapide e per la gestione del layout, del posizionamento e di alcune proprietà visive. Le animazioni custom sono definite nella configurazione Tailwind integrata.

- CSS3: La tecnologia fondamentale per questo progetto, che sfrutta:

  - Trasformazioni 3D (transform-style: preserve-3d, rotateY, translateZ) per la disposizione e il movimento delle immagini.

  - Animazioni (@keyframes) per il movimento rotatorio continuo del carosello e per l'effetto hover sulle singole immagini.

Funzionalità Principali

- Carosello 3D con Rotazione Automatica: Le immagini sono disposte in un cerchio e ruotano continuamente senza intervento dell'utente.

- Animazione Pure CSS: L'intero effetto 3D e il movimento sono gestiti unicamente tramite CSS, senza l'uso di JavaScript.

- Effetto Hover Interattivo: Al passaggio del mouse su un'immagine, questa si sposta leggermente verso l'alto e si ingrandisce, fornendo un feedback visivo.

- Design Flessibile: Utilizzo delle classi Tailwind per un layout responsivo e adattabile.


Come Avviare il Progetto

Segui questi semplici passaggi per visualizzare il progetto localmente:


Prerequisiti

Non sono richiesti particolari prerequisiti oltre a un browser web moderno che supporti le trasformazioni CSS3 (tutti i browser moderni lo fanno) e una connessione internet per caricare Tailwind CSS e Font Awesome tramite CDN.


Installazione

1. Clona il repository (o scarica la cartella del progetto):

git clone https://github.com/ValeVent/carosello-3d-rotante.git

Assicurati di sostituire 'carosello-3d-rotante.git' con il nome esatto del tuo repository.

2. Naviga nella directory del progetto:

cd carosello-3d-rotante


Avvio dell'Applicazione

- Assicurati che i file immagine a cui fa riferimento il progetto (URL di Unsplash) siano accessibili via internet, oppure sostituiscili con immagini locali.

- Apri il file index.html (o il nome del tuo file HTML principale) direttamente nel tuo browser web.

Se hai installato http-server globalmente (opzionale, per un server locale):

npm install -g http-server

http-server .

L'applicazione sarà accessibile all'indirizzo mostrato dal server (es. http://localhost:8080).


Stato del Progetto

Questo progetto è un'eccellente dimostrazione di come creare animazioni 3D complesse e coinvolgenti utilizzando esclusivamente HTML, CSS e Tailwind CSS, evidenziando le capacità avanzate di trasformazione e animazione web.


Contatti

GitHub: https://github.com/ValeVent

LinkedIn: https://www.linkedin.com/in/valentina-venturo

Sito Web: http://www.valentinaventuro.it
