# ME.NE.E.S.CO. — Landing Page

Landing istituzionale per la formazione e la gestione dei conflitti nella Pubblica Amministrazione.
Sito statico (HTML/CSS/JS), pubblicato tramite GitHub Pages.

## Checklist prima del go-live

Sostituire i seguenti placeholder:

1. **Dominio** — sostituire `https://www.meneesco.it/` con il dominio reale in:
   `index.html` (canonical, Open Graph, JSON-LD), `sitemap.xml`, `robots.txt`
2. **Google Analytics 4** — in `index.html`, impostare `GA_ID = 'G-XXXXXXXXXX'` con il Measurement ID reale
3. **Web3Forms** — in `index.html`, sostituire `INSERIRE-ACCESS-KEY-WEB3FORMS-CLIENTE` con la access key dell'account del cliente (la mail di destinazione è quella legata alla key)
4. **Dati legali** — in `privacy.html`, compilare `[RAGIONE SOCIALE]`, `[P.IVA]`, `[INDIRIZZO]`, `[EMAIL CLIENTE]`

## Pubblicazione (GitHub Pages)

1. Settings → Pages → Source: branch `main`, cartella `/ (root)`
2. Attendere la pubblicazione; l'URL sarà `https://<utente>.github.io/<repo>/`
3. (Opzionale) Custom domain: inserire il dominio in Settings → Pages e creare il record DNS dal registrar
