# Spazio Mondi Migranti — GitHub Pages Ready

## File
- `index.html` → sito principale
- `posts.json` → post/news
- `gallery.json` → galleria immagini

## Pubblicazione su GitHub Pages
1. Crea un repository GitHub
2. Carica questi file nella **root** del repo
3. Vai su **Settings > Pages**
4. Come source scegli **Deploy from a branch**
5. Seleziona branch `main` e cartella `/root`
6. Salva

Dopo pochi secondi il sito sarà online.

## Mini area admin
Nel sito trovi il pulsante **Admin**.

Funzioni:
- aggiunta/modifica/eliminazione post
- aggiunta/modifica/eliminazione immagini
- salvataggio locale nel browser
- export di `posts.json`
- export di `gallery.json`
- import dei JSON aggiornati
- reset ai file originali del repo

## Nota importante
Su GitHub Pages il sito è statico.
L'area admin **non scrive direttamente sul repository GitHub**.
Quindi il flusso corretto è:
1. apri il sito
2. aggiorna i contenuti in Admin
3. clicca **Esporta posts.json** e **Esporta gallery.json**
4. sostituisci i file nel repo GitHub
5. fai commit

## Personalizzazioni rapide
Nel file `index.html` puoi modificare facilmente:
- email
- testi hero
- sezione donazioni / 5x1000
- link Instagram
- colori

## Consiglio pratico
Se vuoi in futuro una vera area admin online con login, conviene passare a:
- Supabase
- Firebase
- oppure Netlify CMS / Decap CMS

Ma per partire subito questa versione è perfetta: bella, veloce e semplice da gestire.