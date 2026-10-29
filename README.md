# First Class Hub

Responsive, mobile-first static website for First Class Hub with a black-and-gold visual direction.

## Project
- `index.html` — responsive homepage, interactive category filters, expandable service details, address and Google Maps directions.
- Static deployment; no build command or package manager is required.

## Local development
Open `index.html` in a browser or serve the repository root with any static file server.

## Launch blockers — do not publish yet
- The official supplied logo is a JPEG (1254 × 1254 RGB). It is not yet committed because the connected GitHub workflow can write text files but cannot transfer the local binary attachment. The page references `assets/first-class-logo.jpeg` in the header, footer, favicon and social preview, so those references will remain broken until the exact original image is uploaded to that path. Do not substitute the existing `logo.svg`.
- Vercel project access could not be verified for the discovered `first-class-hub-kano` project (project detail lookup returned 404 and deployment listing returned 403). Do not deploy there. Confirm/create the correct Kaduna project with authorized access.
- Canonical URL and XML sitemap are not configured because the production domain is unconfirmed. `robots.txt` allows crawling; after the production URL is verified, add the absolute sitemap URL and submit it in Google Search Console and Bing Webmaster Tools.
- Product and hero imagery are illustrative stock images, not verified photographs of the actual premises or inventory.
- Opening hours, telephone, pricing, reviews and booking functionality are not claimed because verified details were not supplied.

See [LAUNCH_AUDIT.md](./LAUNCH_AUDIT.md) for the current status and acceptance checks.
