# Vetrina Office Solution

Pagina unica (statica, senza build) che presenta i tre gestionali di Office Solution
— **interventia**, **Lucentia**, **Menù Digitale** — e rimanda alle pagine dedicate
di ciascun prodotto.

## File

```
.
├─ index.html          # la pagina (HTML + CSS + JS inline, nessuna dipendenza)
└─ assets/
   ├─ logo-mark.png        # solo simbolo (nav + favicon)
   ├─ logo-stacked.png     # logo verticale (hero)
   └─ logo-horizontal.png  # logo orizzontale (footer)
```

## Pubblicazione

È una cartella statica: caricala su qualsiasi hosting (Cloudflare Pages, Netlify,
GitHub Pages…) e funziona così com'è. Nessun `npm`, nessun build.

- **Cloudflare Pages → Upload assets**: trascina il *contenuto* di questa cartella.
- Oppure metti la cartella su un dominio/sottodominio ombrello dedicato.

## URL dei prodotti

Impostati in `index.html` (cerca `data-prodotto`):

| Prodotto       | href                                       |
|----------------|--------------------------------------------|
| interventia    | `https://interventia.pages.dev/setup.html` |
| Lucentia       | `https://lucentia-web.pages.dev/`          |
| Menù Digitale  | `https://menu-digitale-f3q.pages.dev/`     |

Contatti già impostati: WhatsApp `392 0241955`, email `amministrazione@cmav.it`,
sito `officesolutionoleggio.com`.
