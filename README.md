# AquaLevel – sito

Landing page di AquaLevel per misurare l'interesse prima della produzione (smoke test Lean Startup). La pagina è in `site/index.html` e viene pubblicata su GitHub Pages dal workflow `.github/workflows/pages.yml` a ogni push su `main`.

Configurazione, in cima allo script di `site/index.html`:
- `FORMSPREE_ID`: l'ID del form Formspree che riceve le email (la parte finale di `https://formspree.io/f/…`).
- `GOATCOUNTER_CODE`: facoltativo, il codice GoatCounter per contare le visite senza cookie.

Per provarla in locale basta aprire `site/index.html` nel browser.
