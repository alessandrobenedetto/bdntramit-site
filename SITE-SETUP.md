# bndtramit — sito e pubblicazione

Sito statico HTML/CSS/JavaScript, senza dipendenze o build. Il nome pubblico è `bndtramit`; il repository conserva il nome storico `alessandrobenedetto/bdntramit-site`.

## Hosting verificato
- Cloudflare Pages: progetto `bdntramit-site`, branch `main`, directory di pubblicazione `.`.
- `bndtramit.com` e `www.bndtramit.com` puntano tramite CNAME a `bdntramit-site.pages.dev`.
- Non creare un nuovo progetto Workers o migrare l'hosting per modificare la pagina.
- Gli aggiornamenti su `main` attivano la pubblicazione tramite l'integrazione Cloudflare; verificarne il check sul commit.

## Contenuti e contatti
- Posizionamento: coordinamento internazionale per persone, famiglie e PMI, con focus iniziale Italia–Spagna.
- Quattro aree: Property & Investments, Business & Expansion, Private & Family Affairs, Relocation & Lifestyle.
- Responsabile: Gian Marco Benedetto. Luca e Antonio Benedetto: area legale, con descrizione volutamente essenziale su indicazione del titolare del progetto.
- Recapito temporaneo autorizzato: aml.benedetto@gmail.com. I link mailto aprono il programma di posta; non inviano automaticamente e non richiedono un backend.
- Sedi indicate dal titolare: KaleidoLAB a Barcellona e Studio Legale Benedetto a La Spezia.
- Indirizzo La Spezia: via Enrico Tazzoli 72, 19126, verificato sul sito ufficiale https://www.studiolegalebenedetto.com/chi-siamo/ il 22 novembre 2026.
- KaleidoLAB a Barcellona riscontrato su https://xeu.cat/associacio-kaleidolab/ e nelle notizie sul fondatore. L'indirizzo stradale, disponibile solo da un elenco esterno, non è pubblicato finché non confermato direttamente.

## Materiale ancora da fornire
- Fotografie autentiche del team e delle sedi, con autorizzazione alla pubblicazione.
- Casi studio realmente svolti: sintesi, paesi coinvolti, ruolo del desk, risultato verificato e autorizzazione alla pubblicazione anonimizzata. Non sostituirli con esempi presentati come casi reali o testimonianze inventate.
- Le tre guide attuali sono orientamenti organizzativi originali, non casi studio né consulenze individuali. Ogni guida ha una CTA email pertinente.
- Dati societari e informativa applicabile, da completare con informazioni effettive del titolare.
- Conservato il precedente `noindex, nofollow` in attesa della definizione dei dati per il lancio definitivo. Canonical e og:url ora usano il dominio verificato.

## Verifica locale
Eseguire `python -m http.server 8765 --bind 127.0.0.1` dalla cartella del sito e aprire http://127.0.0.1:8765/.
Controllare layout desktop/mobile, menu da tastiera, guide espandibili e destinazioni dei link email. Il menu rimane navigabile anche senza JavaScript.
