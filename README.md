# PricePump

Pacchetto finale pronto per GitHub Pages.

## Come caricarlo su GitHub senza terminale

1. Crea una repository GitHub chiamata **pricepump**.
2. Entra nella repository.
3. Clicca **Add file → Upload files**.
4. Trascina dentro tutti i file di questa cartella:
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
   - `icon-192.png`
   - `icon-512.png`
   - `.nojekyll`
5. Clicca **Commit changes**.
6. Vai in **Settings → Pages**.
7. In **Build and deployment**, scegli:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
8. Salva.

Il sito sarà disponibile a un indirizzo simile a:

`https://TUO-NOME-GITHUB.github.io/pricepump/`

## Importante

Questo pacchetto è impostato per una repository chiamata **pricepump**.
Se usi un nome repository diverso, vanno aggiornati i percorsi `/pricepump/` dentro:
- `manifest.json`
- `service-worker.js`
- registrazione service worker dentro `index.html`
