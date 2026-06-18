# Mike & Sons Roofing

Production website for Mike & Sons Roofing — a family-owned roofing contractor serving Northern Colorado (Fort Collins, Loveland, Windsor, Greeley). Static site, deployed on Vercel.

## Structure

- `index.html` — full single-page site (self-contained: HTML + CSS + vanilla JS)
- `logo-pack/` — brand logo assets (SVG + PNG, favicon, lockups)
- `mike and sons logo.png` — original reference logo
- `vercel.json` — Vercel config (clean URLs + security headers)

Built pixel-faithful from the Claude Design handoff, with added mobile responsiveness, a sticky click-to-call bar, and SEO/AEO essentials (RoofingContractor + FAQ JSON-LD schema, Open Graph tags).

## To populate before / shortly after launch

These are placeholders in the live build:

1. **Real photos** — hero image and the 4 project tiles use styled placeholders. Swap in real photos of the crew, truck, and finished roofs (real work outperforms stock and feeds AI search).
2. **Lead form delivery** — the quote form currently shows an on-page confirmation only. Wire it to an email/CRM endpoint (Formspree, Netlify Forms, or a backend) so leads actually arrive. See the `TODO` in the form submit handler.
3. **Verify NAP** — confirm phone `(970) 780-2900`, hours, license #, and exact service-area cities, then mirror them in the JSON-LD and Google Business Profile.
4. **Domain** — update the canonical / OG URLs in `index.html` once the real domain is set.

## Deploy

Static site, no build step. Vercel serves the files as-is from the repo root.
