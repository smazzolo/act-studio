# ACT Studio — Company Profile (web)

Versione web statica del Company Profile di **ACT Studio STP S.r.l.**
(studio tributario e societario, Roma).

## Struttura
- `index.html` — pagina unica del company profile
- `assets/img/` — immagini (logo, foto duotone navy, mappa Roma)
- `assets/fonts/` — EB Garamond + Inter (TTF self-hosted)

## Deploy su Vercel
Sito statico, nessun build step:
1. push del repo su GitHub
2. import del repo su Vercel → framework preset **Other**
3. output directory: root (`/`)

## Note
- Nessuna dipendenza, nessun JS di terze parti esterno.
- Font e immagini self-hosted (nessun hotlink).
- Sorgente PDF = file HTML separato con asset in base64 (non incluso qui).
