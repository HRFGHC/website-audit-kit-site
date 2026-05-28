# Alternative Deployment: Hostinger

## Is Hostinger OK?
Yes. Hostinger is acceptable if you want paid managed hosting, WordPress, email/domain bundles, or you already own a Hostinger plan/domain.

## Why it is not my recommended first step here
The current site is static HTML and the standing mission starts with a $0 budget. Cloudflare Pages or GitHub Pages can host this at no monthly cost. Hostinger introduces hosting/domain spend and renewal pricing before the offer has traction.

## Human steps if you still choose Hostinger
1. Decide that you approve spending money on hosting/domain. Hermes cannot make paid commitments without explicit approval.
2. Create or log into your Hostinger account.
3. Choose a plan only if you are comfortable with the renewal price, not just the introductory promo price.
4. If buying a domain, choose and purchase the domain yourself.
5. In Hostinger hPanel, open **Websites** → your site → **File Manager**.
6. Open `public_html`.
7. Upload the files from this folder:
   - `index.html`
   - `robots.txt`
   - `sitemap.xml`
8. If Hostinger supports custom headers for your plan, add equivalent security headers from `_headers`; otherwise skip `_headers`.
9. Replace the placeholder CTA with your approved checkout/download/contact link.
10. Send Hermes the live URL.

## What Hermes will do after you send the live URL
1. Verify the public site loads.
2. Check for obvious broken links/rendering issues.
3. Help update copy, CTA, sitemap, and launch assets.
