# flowtechai.com.au

Parent-brand hub for **FlowTech AI Pty Ltd** — _Intelligence Behind the System_.

A static, dark-first site that introduces the parent brand, links to each division, showcases live client work, and folds the former automation page into a parent **Intelligence Layer** section (no live orchestration — described as in development).

## Structure

```
index.html          Single-page hub (hero · divisions · work · intelligence · contact)
privacy.html        Privacy Policy (AU Privacy Act 1988)
terms.html          Terms of Use (NSW governing law)
manifest.json       PWA manifest
assets/
  ft-ai-mark.svg    Canonical parent mark (14-peg umbrella, mono/Mist)
favicons/
  ft-icon.svg       SVG favicon (primary)
  favicon-16/32/48.png, favicon.ico, apple-touch-icon.png, icon-192/512.png
og-image.png        1200x630 social card
gen_assets.py       Regenerates favicons + OG card from the canonical marks
```

## Brand

- **Palette (parent neutral):** Obsidian `#0B1114` · Ink `#1A2230` · Slate `#5B6675` · Mist `#E7ECF2` · White `#FFFFFF`
- **Type:** Michroma (wordmark + short caps) · IBM Plex Sans (UI/body) — Google Fonts
- **Division accents:** Digital blue · FlowTrade green · FlowForge orange · FlowTech Automate purple (3-stop gradients)
- **Mark:** parent 14-peg umbrella sigil + ring

## Hosting / deploy

CloudFlare Pages — project `flowtechai-com-au` (Account `caab49ae881cd23f5e966fe824c583f1`, zone `flowtechai.com.au`).
Production deploys on push to `main` via `.github/workflows/deploy.yml` (Wrangler direct upload). Non-`main` branches deploy as previews.

## Contact

admin@flowtechai.com.au · Sydney NSW, Australia
