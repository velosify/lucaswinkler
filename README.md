# Lucas Winkler — Royal Oak Real Estate

A single-page landing site for Lucas Winkler, Keller Williams Realty Metro.

## Structure

- `index.html` — the entire site (HTML, Tailwind via CDN, inline CSS/JS)
- `assets/` — images (portrait cutout, listings map)

## Deploying

This is a static site. Cloudflare Pages settings:

- **Framework preset:** None
- **Build command:** *(leave empty)*
- **Build output directory:** `/` (root)

No build step is required — Cloudflare serves `index.html` directly.
