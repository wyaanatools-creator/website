# Wyaana — static site

Self-contained pages (fonts, logo, backgrounds, cutouts and scripts are inlined):

- index.html — landing
- story.html — The Story
- trade.html — Hayyakum / Trade
- contact.html — Contact (WhatsApp +971 50 776 1848, emails, form)
- assets/products/ — bag photos loaded at runtime
- assets/ambience.mp3 — looping ambient track for the sound toggle (keep the assets folder next to the HTML)

## Publish on GitHub Pages
1. Create a repository (e.g. `wyaana-site`) and upload the contents of this folder to its root (keep `.nojekyll`).
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)` → Save.
3. The site appears at `https://<user>.github.io/wyaana-site/` within a minute or two.
4. Custom domain: Settings → Pages → Custom domain → `wyaana.ae`, then add the DNS records GitHub shows. Do this only when you're ready to go live.

Notes
- Contact and Trade forms are visual only; wire them to Formspree/Netlify Forms or your backend before launch.
- Shopify cart/checkout are prototypes; see the `shopify-handoff/` package for the integration plan.
- Fonts: 29LT Bukra is embedded — ensure your licence covers web use.
