# First Class Hub

Professional public website for **First Class Hub**, Kaduna, Nigeria.

## Location (only)

No. 10 Rahma Road  
Off Nnamdi Azikiwe Expressway (Western Bypass)  
Kaduna, Kaduna State, Nigeria  
Postal Code: **800283**

Do not list Kano or any other city as a business location.

## Brand

- Official logo artwork is embedded in `index.html` (header/footer) from the supplied 1ST CLASS crest JPEG.
- `logo.svg` remains available for favicon / lightweight social fallback.
- Brand system: black, cream, restrained gold.

## Stack

Static site: `index.html` + `logo.svg` + `robots.txt`

Deploy on **Vercel** (static / no build).

## Domain note

Current default Vercel host may still contain `kano` in the subdomain string. That is a **project hostname**, not business copy.

Recommended next step (manual, needs your approval):
1. Vercel → Project Settings → Domains
2. Add a clean host such as `first-class-hub.vercel.app` or a custom domain (`firstclasshub.ng` if available)
3. Keep the old host as redirect until DNS is verified

## Local preview

Open `index.html` in a browser, or:

```bash
npx serve .
```
