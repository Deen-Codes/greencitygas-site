# Green City Gas — website

Static one-page site for Green City Gas (plumbing & heating, Milton Keynes).

## Files
- `index.html` — the whole site (self-contained: HTML, CSS, inline SVG logo)
- `render.yaml` — Render Static Site blueprint (auto-deploy config)

## Hosting
Deployed on Render as a Static Site, connected to this GitHub repo.
Every push to `main` triggers an automatic redeploy.

- Publish directory: `.`
- Build command: none (plain static HTML)

## Custom domain
`greencitygas.co.uk` (and `.com`) added in Render → Settings → Custom Domains,
with DNS managed at Cloudflare.

## To do (fill in later)
- Gas Safe registration number
- Confirm opening hours
- Confirm service areas
- Add `Green City Gas Ltd` company number in the footer once registered
