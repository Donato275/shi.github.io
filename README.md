# Sito web statico

Cartella pronta per **GitHub Pages** e per essere usata da **browser su PC e cellulare**.

## Cosa c’è qui

| File / cartella | Ruolo |
|-----------------|--------|
| `index.html` | Pagina principale |
| `styles.css` | Aspetto del sito (colori, layout, responsive) |
| `I_MIEI_DATI.js` | Testi, link social, percorso foto (modifica qui i contenuti) |
| `images/cani/` | Metti `Foto1.jpg` … `Foto6.jpg` (vedi `LEGGIMI.txt` nella stessa cartella) |
| `.nojekyll` | Evita che GitHub tratti il sito come progetto Jekyll |

## Pubblicare su GitHub

1. Su GitHub crea un **nuovo repository** (es. `mio-sito-cane`).
2. Carica **tutto il contenuto di questa cartella** `sito-github` nella radice del repository (non la cartella padre con altri file).
3. Repository → **Settings** → **Pages** → **Build and deployment** → Source: **Deploy from a branch** → Branch **main** (o `master`) cartella **`/ (root)`** → Save.
4. Dopo qualche minuto il sito sarà su `https://TUO-USERNAME.github.io/NOME-REPO/`.

Percorsi relativi (`I_MIEI_DATI.js`, `images/cani/...`) funzionano anche con l’URL sotto `/NOME-REPO/`.

## Modifiche ai contenuti

Apri `I_MIEI_DATI.js` nel editor: titoli, paragrafi, email, telefono, social, `cartellaFoto` se sposti le immagini.

## Anteprima in locale

Apri `index.html` con il browser (doppio clic) oppure da terminale, nella cartella del sito:

`npx --yes serve .`

Poi vai all’indirizzo indicato (es. `http://localhost:3000`).
