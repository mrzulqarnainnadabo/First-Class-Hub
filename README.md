# First Class Hub

Responsive, mobile-first static website for First Class Hub with a black-and-gold visual direction.

## Project
- `index.html` — responsive homepage, interactive category filters, expandable service details, address and Google Maps directions.
- Static deployment; no build command or package manager is required.

## Local development
Open `index.html` in a browser or serve the repository root with any static file server.

## Launch blockers — do not publish yet
- The official supplied logo is a JPEG (1254 × 1254 RGB). It is not yet committed because the available GitHub connector supports text-file writes but not direct upload of the binary attachment. The page is prepared to reference `assets/first-class-logo.jpeg` in the header, footer, favicon and social preview, but those references will remain broken until the exact original image is uploaded to that path. Do not substitute the existing `logo.svg`.
- The discoverable Vercel project is named `first-class-hub-kano`, which conflicts with the Kaduna-only brief. Confirm the intended project before deploying.
- Canonical URL is not configured because the production domain is unconfirmed.
- Product and hero imagery are illustrative stock images, not verified photographs of the actual premises or inventory.
- Opening hours, telephone, pricing, reviews and booking functionality are not claimed because verified details were not supplied.

See [LAUNCH_AUDIT.md](./LAUNCH_AUDIT.md) for the current status and acceptance checks.
