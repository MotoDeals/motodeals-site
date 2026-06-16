# MotoDeals — sito

Sito statico (HTML/CSS/JS, nessun build) della campagna di affiliazione e del canale Telegram **MotoDeals**.

## Struttura
- `index.html` — landing page
- `blog.html` — archivio articoli ("Resoconto articoli")
- `articolo.html` — singolo articolo (apertura via `?slug=...`)
- `admin.html` — pannello offline per scrivere/gestire gli articoli ed esportare i dati
- `articles-data.js` — dati degli articoli
- `styles.css` — stile condiviso del sito
- `assets/` — loghi e immagini

## Pubblicazione
Sito ospitato su **Netlify**, collegato a questo repository GitHub: ogni `push` aggiorna automaticamente il sito online.

## Come gestire gli articoli
- **Offline:** apri `admin.html`, scrivi/modifica, premi *Esporta articles-data.js* e sostituisci il file.
- **Online (CMS live):** in arrivo su `/admin`, per pubblicare direttamente dal browser senza esportare file.
