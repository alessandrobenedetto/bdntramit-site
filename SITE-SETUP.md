# BDN Tramit — sito vetrina

Bozza statica in HTML/CSS/JavaScript senza backend o comando di build.

## Contenuti da verificare prima del lancio
- Descrizione reale dell'azienda, servizi, valori, contatti, logo.
- Privacy, dati societari e altre informative applicabili.
- Togliere `noindex, nofollow` da `index.html` solamente quando il sito è definitivo.
- Verificare la grafia del dominio: nei messaggi precedenti è indicato `bdntramit.com`, mentre la pagina di conferma Cloudflare mostra `bndtramit.com`. NON presumere che siano lo stesso dominio.
- Una volta confermato il nome esatto, aggiungere l'URL canonico e il tag og:url.

## Pubblicazione su Cloudflare Pages
1. Aprire Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect to Git (le etichette potrebbero variare).
2. Autorizzare l'accesso al repository GitHub `alessandrobenedetto/bdntramit-site` e selezionare il branch `main`.
3. Framework preset: None; build command: vuoto; build output directory: `.`.
4. Avviare il deploy e testare il dominio temporaneo `*.pages.dev`.
5. In Custom domains, aggiungere esclusivamente il dominio effettivamente registrato, dopo averne confermato l'ortografia.
6. Verificare gli URL con e senza www e il certificato SSL.

Gli aggiornamenti su main vengono pubblicati automaticamente su Cloudflare Pages se l'integrazione Git è attiva.
