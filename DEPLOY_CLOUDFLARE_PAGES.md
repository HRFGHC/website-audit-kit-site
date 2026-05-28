# Recommended Deployment: Cloudflare Pages (Free Static Hosting)

## Why this is the best first option
- $0 hosting for a static landing page.
- Free `*.pages.dev` URL; no domain purchase required at launch.
- Easy custom-domain upgrade later.
- Better fit than paid hosting for the current zero-capital revenue mission.

## Human steps required
1. Create or log into a GitHub account.
2. Create a new public repository, for example: `website-audit-kit-site`.
3. Upload the contents of this folder to that repository root:
   - `index.html`
   - `robots.txt`
   - `sitemap.xml`
   - `_headers`
4. Create or log into a free Cloudflare account.
5. In Cloudflare Dashboard, go to **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
6. Connect GitHub and select the `website-audit-kit-site` repository.
7. Use these build settings:
   - Framework preset: `None` or `Static HTML`
   - Build command: leave blank
   - Build output directory: `/` or `.`
8. Click **Save and Deploy**.
9. Copy the generated `*.pages.dev` URL and send it to Hermes.
10. Decide whether the CTA should point to:
    - a free download,
    - Gumroad/Ko-fi/Payhip checkout,
    - an email/contact form,
    - or a waitlist.

## What Hermes will do after you send the live URL
1. Verify the public site loads.
2. Update the CTA, sitemap, and copy if you provide the checkout/download link.
3. Prepare screenshots/preview copy for distribution.
4. Track verified revenue/costs only when there is evidence.
