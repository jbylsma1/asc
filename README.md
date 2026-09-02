# Align Software Consulting website

Static HTML/CSS/JavaScript site designed for GitHub + Cloudflare Pages.

## Files
- `index.html` — page content
- `styles.css` — full responsive styling
- `script.js` — navigation and reveal animation

## Deploy to Cloudflare Pages

1. Create a GitHub repository and put these files in the repository root.
2. Push to GitHub.
3. In Cloudflare, create/import a Pages project from the repository.
4. Framework preset: **None**
5. Build command: leave blank
6. Build output directory: `/` (or leave at the default root setting if Cloudflare accepts it)
7. Deploy.

## Before launch

Search `index.html` for:
- `hello@alignsoft.net` — replace if you want a different public email.
- `St. Louis, Missouri` — change if desired.
- Service descriptions — edit freely.

There are no image assets. The visual design is built entirely with HTML/CSS/SVG, so deployment is lightweight and there is no separate image hosting requirement.
