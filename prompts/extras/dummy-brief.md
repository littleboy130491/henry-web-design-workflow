# Extra — Create a Dummy Client Brief

**Reads:** what the user gives in the message — a **concept** (e.g. "boutique dental clinic in Bali"), a **live URL**, or both. Plus any files the user points to.
**Writes:** `inputs/brief.md` (+ `inputs/brief-sources.md` when a URL was used)

## Task
Write a realistic, thorough client brief that the main workflow can start from (step 01). It should read like a brief a real client filled in after a discovery call: a bit informal, but full of usable facts.

## Mode A — From a concept
1. Expand the concept into a believable business: name, location, size, history, offer, prices, customers, competitors.
2. Research the industry (real competitors, typical prices, common customer complaints, how people search for it) so the details are realistic, not generic.
3. Make it internally consistent: prices match the market and positioning, team size matches revenue, and so on.

## Mode B — From a live URL
1. Scrape the site (homepage plus the key pages: about, services/products, pricing, contact) and note structure, offer, audience, tone, proof, and visible weaknesses.
2. Use the real site only as **inspiration for the business model and industry**. Then **anonymize everything** (see Masking rules).
3. Frame the brief as if this fictional client wants a redesign: include "current site problems" based on what you observed, written about the fictional business.

## Masking rules (Mode B, mandatory)
- Make up a new **business name**, **domain**, **tagline**, and **product/service names**. They must not resemble the original (no near-spellings, same initials, or puns on it). Quickly check that the new name isn't an obvious existing brand in the same industry.
- Replace all **people's names**: founders, team, testimonial authors, client/partner companies.
- Replace **contact details**: address (keep the same city/region unless the user says otherwise), phone, email, social handles.
- Change **exact numbers** slightly (years, client counts, prices within ±10–20%) so they're realistic but not traceable.
- **Never copy** text, slogans, testimonials, logos, photos, or brand colors. Paraphrase facts in your own words, describe images instead of reusing them, and propose a different color direction.
- Don't mention the original brand or URL anywhere in `inputs/brief.md`.
- Keep the mapping (original → dummy) only in `inputs/brief-sources.md`, marked **internal reference — do not use in outputs**. Later steps must not read this file.

## Brief structure (`inputs/brief.md`)
Write it from the client's point of view ("We are…"), in the language the user asks for (default English).
1. **About us** — name, what we do, location, founded, team size, story.
2. **Products/services** — list with short descriptions, prices or price ranges, best-sellers.
3. **What makes us different** — the client's own view (can be a bit vague or biased, like real clients).
4. **Our customers** — who buys, why, how they find us, common questions and objections.
5. **Competitors** — 3–5 (fictional names in Mode B; real ones are OK in Mode A) with what they do better/worse.
6. **Current situation** — existing site/social presence and its problems, how leads come in now.
7. **Goals for the new website** — primary conversion, secondary goals, success metrics.
8. **Brand** — existing logo/colors/fonts (described), tone of voice, sites they like and dislike.
9. **Content we have** — photos, testimonials (fictional names), case studies, certifications, stats.
10. **Technical** — preferred platform, pages they think they need, integrations (WhatsApp, booking, payments, CRM), languages.
11. **Timeline & budget** — deadline and budget range.
12. **Must-haves / must-avoids.**

## Realism
- Include 2–3 realistic imperfections: an unclear goal, a wish that conflicts with the audience, a missing asset. Step 01 should have something to refine and ask about.
- Be specific: real-sounding numbers, named products, concrete customer quotes. Avoid generic filler.
- At the end, add a short **Brief summary** (5 bullets) so the user can check the scenario quickly.
