# First Class Hub — Launch audit

Date: 2026-10-29

## Repository audit
- Repository: `mrzulqarnainnadabo/First-Class-Hub`
- Default branch at inspection: `main`
- Existing site: a single-file static `index.html`; no `package.json`, app framework, or `vercel.json` was found at the repository root.
- Existing `logo.svg` is a drawn SVG approximation, not the user-supplied JPEG. The revised page no longer references that SVG as the logo or favicon. Do not treat the existing SVG as approved brand artwork.

## Implemented in this branch
- Simplified the homepage copy and visual hierarchy while retaining the existing single-page static structure.
- Added search-engine directives (`index, follow`), richer Open Graph and Twitter card metadata, and a `robots.txt` that allows crawling. The social image reference points to the intended official logo JPEG path; it will not resolve until that image is uploaded. Canonical URL and sitemap are omitted until the production domain is confirmed.
- Preserved the accessible category filter and its live status announcement.
- Added eight keyboard-accessible native expandable detail panels so visitors can engage with each category without leaving the page.
- Prepared header/footer, favicon and social-preview references to the official JPEG path; these are intentionally launch-blocking until the binary image is uploaded.
- Added visible focus states, reduced-motion support, lazy loading on below-the-fold images, and mobile sticky actions.
- Updated the Google Maps link to use the directions endpoint and the supplied Kaduna destination address.
- Corrected the location copy to use the exact supplied address and postal code: No. 10 Rahma Road, Off Nnamdi Azikiwe Expressway (Western Bypass), Kaduna, Kaduna State, Nigeria, 800283.
- Kept telephone, opening hours, reviews, prices, and booking claims out of the page because verified details were not supplied.
- Marked catalogue imagery as illustrative in alt text so it is not presented as actual premises/product photography.

## Kaduna-only audit
The revised homepage, JSON-LD LocalBusiness address, and all displayed location copy refer only to Kaduna, Kaduna State, Nigeria. The address is consistent across the page. A complete repository-wide code search of every branch and a production crawl have not been completed, so this is not a claim that every historic file or deployed artifact has been cleared.

## Required before public launch
1. Upload the exact supplied JPEG unchanged at `assets/first-class-logo.jpeg`. The page now references this path but the image is not in the repository, so logo references currently do not resolve. Do not substitute the existing SVG.
2. Confirm or create the correct Kaduna Vercel project with access; current project lookup was denied/not found. Do not deploy to the `first-class-hub-kano` project without confirming ownership and intent.
3. Confirm the production domain, then set canonical metadata, absolute Open Graph/Twitter image URLs, and `sitemap.xml` with that verified domain. Submit the sitemap to Google Search Console and Bing Webmaster Tools.
4. Run a browser-based mobile/desktop visual review, test all remote image URLs and directions links, and verify the deployed source commit before publishing.
5. Replace illustrative stock photos with approved business photos when available.

## Test status
Source-level checks only. Category filters and expandable panels are present; browser-based interaction, mobile/desktop rendering, external image loading, automated accessibility, and production deployment have not been tested. `robots.txt` allows crawling. The official logo is missing and Vercel access/domain remain unresolved, so the branch must not be deployed as launch-ready.
