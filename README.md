# Rubik's Cube Wishlist Project
Una web app interattiva pensata per tracciare la propria collezione dei desideri riguardanti i puzzle dei cubi di Rubik e lo Speedcubing.
Il progetto permette di consultare la lista dei cubi desiderati, visualizzarne i dettagli, le immagini e contrassegnare gli elementi acquistati o ottenuti con uno stato permanente.

---

## Funzionalità principali
- **Wishlist per Brand:** Catalogo completo dei rompicapi di speedcubing suddiviso per le principali marche del settore (**GAN**, **Rubik's**, **MoYu** e **QiYi**).
- **Stato "Posseduto" Permanente:** Quando un cubo viene segnato come ottenuto, la scheda cambia stato visivo (effetto opacità/completato) e l'azione diventa irreversibile, bloccando lo status nella collezione.
- **Custom Assets & UI:** Cursore personalizzato a tema cubo (`rubik_cursor.cur`), favicon dedicata ed elementi grafici su misura.
- **Design Responsive:** Interfaccia ottimalizzata per la consultazione da desktop e dispositivi mobili.

---

## Tecnologie Utilizzate

- **HTML5:** Strutturazione semantica delle pagine e delle card dei prodotti.
- **CSS3:** Styling avanzato, layout moderni (Flexbox/Grid), gestione degli stati opachi/disabilitati e cursore personalizzato.
- **JavaScript (ES6+):** Logica di interazione per il tracciamento degli elementi posseduti e gestione degli eventi DOM.

---

## Struttura del Progetto

```text
9_wishlist_rubiks_cube/
├── src/
│   ├── assets/
│   │   ├── cursor/
│   │   │   └── rubik_cursor.cur
│   │   ├── favicon/
│   │   │   └── rubik_favicon.ico
│   │   ├── font/
│   │   ├── image/
│   │   └── logo/
│   ├── js/
│   │   └── script.js
│   ├── styles/
│   │   └── style.css
│   └── index.html
├── LICENSE
└── README.md
```

---

## Installazione e Utilizzo
Basta scaricare il codice aprilo in web per poter vedere il carosello funzionante.
Istruzioni passo passo su come installare e configuare il progetto in locale.

1. Clonare il repository:
``` bash
git clone [https://github.com/denisalecexe/Rubiks_Cube_Wishlist.git](https://github.com/denisalecexe/Rubiks_Cube_Wishlist.git)
```

2. Accedere alla cartella del progetto:
``` bash
cd Rubiks_Cube_Wishlist
```

3. Avviare il progetto: non sono necessarie dipendenze esterne ed è sufficiente aprire il file src/index.html direttamente nel browser o avviarlo tramite un server locale (come l'estensione *Live Server* di **VS Code**).

---

## Contribuire al progetto
Le pull request sono benvenute.
Per modifiche sostanziali, si prega di aprire prima una segnalazione per discutere di cosa si desidera modificare.

---

## Autore
- **Denis (Dharelyx)** - Sviluppatore Junior appassionato di codice e problem solving.
- Progetto completato come parte del mio percorso.