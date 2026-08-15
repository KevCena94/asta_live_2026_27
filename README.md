# Asta Live 2026-27

Webapp statica HTML/CSS/JavaScript.

## Struttura
- `index.html` — interfaccia
- `style.css` — stile responsive
- `app.js` — logica
- `data/players.json` — dataset iniziale dei giocatori

## Dataset dinamico
Il pulsante `👥` in basso permette di caricare CSV/TXT/JSON, incollare un CSV, ricaricare il dataset online, esportare il JSON corrente o ripristinare i dati predefiniti.

Il dataset personalizzato viene salvato nel `localStorage` del browser e resta sul dispositivo/browser che lo ha caricato.

## Avvio locale
Usare VS Code + Live Server e aprire `index.html`.

## GitHub Pages
Creare un repository pubblico, caricare tutti i file mantenendo `data/`, poi in `Settings -> Pages` scegliere `Deploy from a branch`, branch `main`, cartella `/ (root)`.
