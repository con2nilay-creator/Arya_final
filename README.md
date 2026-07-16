# Arya Fitness — single self-contained site

## `index.html`
The entire website in one file — all images, fonts, and code are inlined. It works
by just opening it (double-click) or uploading it anywhere. **Zero setup, no `assets/`
folder needed.** This is the file to deploy.

### Deploy
- **GitHub Pages:** put `index.html` in a repo → Settings → Pages → Deploy from branch → `main` / root.
- **Any host (Netlify, Vercel, cPanel):** upload `index.html`. Done.

## `sections/` — source partials (for editing only)
Each section's markup, split out so it's easy to find and edit:

- `01-hero.html` · `02-marquee.html` · `03-about.html` · `04-facilities.html`
- `05-membership.html` · `06-why-choose.html` · `07-gallery.html` · `08-reviews.html`
- `09-google-reviews.html` · `10-outline-marquee.html` · `11-cta-banner.html` · `12-contact.html`

These are reference/editing copies. The live site is the bundled `index.html`;
after editing partials, the bundle must be regenerated to reflect changes.
