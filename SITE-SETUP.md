# BDN Tramit — sito vetrina

Bozza statica in HTML/CSS/JavaScript senza backend o build.

## Da completare
- I testi attuali sono dimostrativi. Inserire descrizione reale, servizi, indirizzi, recapiti e logo.
- Togliere il meta `noindex, nofollow` in `index.html` solo quando il sito è pronto per l'indicizzazione.
- Verificare privacy e informative legali in funzione dei servizi effettivamente inseriti.

## Cloudflare Pages
1. Aprire Cloudflare > Workers & Pages > Create > Pages > Import an existing Git repository.
2. Selezionare `alessandrobenedetto/bdntramit-site` e branch `main`.
3. Framework preset: None; nessun comando di build; output directory: `.`.
4. Avviare il deploy, testare il dominio `*.pages.dev`, poi impostare Custom domains > `bdntramit.com`.
5. Se il dominio è registrato altrove, aggiungerlo come zona Cloudflare e configurare i nameserver presso il registrar secondo le indicazioni di Cloudflare.

Le modifiche al branch main sono pubblicate automaticamente.
