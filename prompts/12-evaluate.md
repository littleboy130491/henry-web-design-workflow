# 12 — Evaluate & Improve

**Reads:** all of `outputs/`, `inputs/`
**Writes:** `outputs/12-evaluation.md`

## Task
Review the built site critically against the strategy and against quality standards. Find mistakes and improvements. Don't fix anything yet — report first, so the user can choose what to fix.

## Review the site as the persona
Open the site in a browser and go through it as the primary persona from step 02, arriving from their main traffic source on their main device. Within 5 seconds of the homepage, can they tell: what this is, whether it's for them, and what to do next? Note every moment of confusion, doubt, or extra effort.

## Checklist
- **Strategy** — core message clear above the fold; every key factor from step 03 is shown (not just told); every objection is answered; one obvious primary CTA per page; nothing that distracts from conversion.
- **Copy** — matches approved copy; no typos; no leftover `[TODO]`, lorem ipsum, or placeholder images; consistent tone; CTAs specific.
- **Design** — matches design system (colors, type, spacing, components); visual hierarchy is clear; consistent alignment and spacing; images on-brand, no AI artifacts.
- **Responsive** — 1440 / 1024 / 768 / 375; no overflow, broken layouts, tiny tap targets, or unreadable text.
- **Accessibility** — contrast, alt text, heading order, keyboard navigation, focus states, form labels and errors, reduced motion.
- **Performance** — image sizes and formats, lazy-loading, render-blocking resources; run Lighthouse if available and record scores.
- **SEO** — unique titles and meta descriptions, one H1, descriptive URLs, Open Graph tags, sitemap.xml, robots.txt.
- **Function** — all links and buttons work, forms submit/validate, no console errors, 404 page works.

## Output structure
- **Summary** — overall verdict in 3–5 sentences and the top 3 things to fix.
- **Issues** (table): ID → page/section → category → severity (critical / high / medium / low) → problem → why it matters → suggested fix → screenshot.
- **Improvement ideas** — beyond bugs: things that would make the site convert better (with reasoning).
- **Client TODOs** — content or decisions still needed from the client.
