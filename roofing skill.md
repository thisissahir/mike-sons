---
name: roofing-website-builder
description: Build state-of-the-art, high-end websites for American roofing contractors, and audit competitor roofing sites to extract what wins. Use whenever the work touches a roofing company website — designing, building, rebuilding, planning, writing copy, or critiquing one. Also use for analyzing other roofing businesses' sites to benchmark or reverse-engineer best practices, for roofing-specific local SEO/GEO/AEO and schema, service-area and location pages, storm-response and emergency-lead structure, or conversion architecture for roofers. Trigger even when phrased casually ("build a roofer site", "my roofing site doesn't get calls", "look at this roofing company's website and tell me what they did right", "make a premium roofing landing page", "why doesn't ChatGPT recommend roofers like us"). Carries current 2026 design, conversion, trust, and AI-search standards for the US roofing vertical — consult before writing any roofing web copy, code, or strategy.
---

# Roofing Website Builder

Build and audit roofing contractor websites that look high-end AND book jobs. A roofing site has one job: convert a homeowner who is scanning in panic ("Can you fix my roof?") into a call or form fill, while ranking in Google's map pack, AI Overviews, and answer engines (ChatGPT, Perplexity, Gemini, Claude).

Beauty alone loses. The sites that win are fast, trust-dense, locally specific, and built for both Google and AI from the first line. Treat every build as a lead engine wearing a premium suit, not a brochure.

## How to use this skill

Identify the job, then load the right reference:

| Job | Read |
|-----|------|
| Build or rebuild a roofing site / page | `references/build-playbook.md` |
| Audit a competitor's roofing site (or the client's own) | `references/competitor-audit.md` |
| Conversion + trust architecture decisions | `references/conversion-and-trust.md` |
| Local SEO, GEO/AEO, schema, service-area pages | `references/seo-geo-schema.md` |
| Visual design direction (premium look) | `references/visual-design.md` |

Most real requests touch several. A full build reads build-playbook + conversion-and-trust + seo-geo-schema + visual-design. A "look at this competitor" request reads competitor-audit first, then conversion-and-trust to judge what you find.

## The non-negotiables (apply to every roofing site)

These hold regardless of budget, platform, or region. Everything else is detail.

1. **Five-second clarity.** Above the fold answers three things instantly: who they are, what they do, where they serve. Hero formula: `#1 Trusted Roofing in [City, ST]` + one proof line (years / roofs installed / warranty) + a single dominant CTA. Homeowners assess credibility in seconds and leave if the path isn't obvious.

2. **Mobile-first, click-to-call everywhere.** ~60–67% of roofing searches are mobile, often mid-emergency. Sticky tap-to-call bar on mobile. One-tap phone number in the header. Forms that thumb-type easily.

3. **Speed is a ranking and conversion gate.** Target sub-2s load and strong Core Web Vitals (LCP, CLS, and INP — INP is the 2026 interaction metric). A 1.5s site converts roughly 3x a 3s site. AI engines deprioritize slow sites as "unprofessional."

4. **Trust architecture before sell.** Manufacturer certifications (GAF Master Elite, Owens Corning Platinum, CertainTeed SELECT ShingleMaster), BBB rating, license # + "licensed, bonded, insured", live Google review rating, warranty terms, real project photos. Stock photography reads as a lead-gen scam — use real work.

5. **Organize by homeowner problem, not by service taxonomy.** Someone with a leak needs different content than someone comparing materials. Lead with the panic state ("roof leak", "storm damage", "emergency repair"), then route to the service.

6. **Proof of work, dated and specific.** Before-and-afters with city, date, material, and a customer quote outsell generic testimonials. This doubles as visual data AI engines cite.

7. **Local specificity wins.** Roofing is hyperlocal — climate, materials, insurance rules, and codes vary. Name counties and cities explicitly. Cookie-cutter national copy fails both homeowners and Google's service-area ranking.

8. **Built for AI search, not just Google.** Question-based headings answered immediately in the first sentence, entity-consistent NAP everywhere, RoofingContractor schema with a GeoCircle service area, FAQ schema. The roofer who is the "source of truth" gets cited in the AI answer that now precedes the click.

## Workflow for a build

1. **Intake** — company name, exact service area (every city/county), services offered, certifications, license #, phone, years in business, # of roofs, warranty, real photo assets, financing offered, emergency/24-7 availability. If photos or certs are missing, flag it — they're load-bearing for trust.
2. **Architecture** — map pages before designing (see seo-geo-schema for the standard sitemap: home, services overview, one page per service, one page per city/service-area, emergency page, inspection page, about, contact, gallery, blog/resources).
3. **Design direction** — pick a premium visual lane (visual-design.md) and lock palette + type before laying out.
4. **Build** — production-ready code per Sahir's defaults: React or vanilla HTML/CSS/JS, single-file where possible, no placeholders, no lorem ipsum, real structure. Wire schema, CWV, click-to-call, and forms from the start.
5. **Conversion + trust pass** — run the page against conversion-and-trust.md checklist.
6. **SEO/GEO pass** — run against seo-geo-schema.md checklist and emit JSON-LD.
7. **Deliver** — the site plus a short note of what to populate (NAP, real photos, GBP link).

## Workflow for a competitor audit

Follow `references/competitor-audit.md` end to end. Short version: fetch the site, score it on the fixed rubric (clarity, trust, conversion, speed signals, local specificity, AI-readiness, design), pull the specific tactics worth stealing, and output a ranked findings list with what to copy and what to beat. Always end an audit by translating findings into concrete moves for the client's own build.

## Style rules (carry from Sahir's standing prefs)

No em dashes. No banned words (leverage, seamless, unlock, supercharge, robust). Use "improve" not "optimize" in client-facing copy. Sentence case UI labels. Complete, production-ready output — never partial scaffolds. Zero preamble in deliverables.
