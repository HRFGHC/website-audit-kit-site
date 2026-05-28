# Website Audit Kit Static Website

Prepared: 2026-05-28T09:40:32Z

This folder is a deploy-ready static landing page for the Website Audit Kit v0.1.

## Files
- `index.html` — self-contained landing page with embedded CSS
- `robots.txt` — basic crawler allowance
- `sitemap.xml` — placeholder sitemap; replace the domain before production
- `_headers` — optional Cloudflare Pages security headers

## Important before publishing
1. Replace the placeholder CTA link in `index.html`:
   - `mailto:YOUR_EMAIL@example.com?subject=Website%20Audit%20Kit`
   - with your approved checkout/download URL.
2. Replace placeholder domain in `sitemap.xml` with the actual live URL.
3. If you want this to be a free lead magnet, copy the product ZIP into a public downloads folder and link to it.
4. If you want to sell the kit, use a marketplace/payment provider for checkout and file delivery; do not put the ZIP directly in this static public folder unless you intend it to be freely downloadable.

## Recommended host
Cloudflare Pages free tier for the static site. It gives a free `*.pages.dev` URL and can later connect a custom domain.

## Hostinger note
Hostinger is acceptable if you specifically want paid managed hosting/WordPress or already have a Hostinger plan/domain. For the current $0-budget mission, it is not the best first step because the static landing page can be hosted free.
