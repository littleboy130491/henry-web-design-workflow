# Extra — Recommendations for the Existing Website

## Goal
Turn the roast into a clear, prioritised improvement plan across three areas: **visual**, **architecture** and **messaging**. Each recommendation must trace back to a real finding and to what the client's audience needs.

## Inputs
- **Required:** `outputs/extras/existing-site-roast.md`. If it's missing, stop and tell the user to run `prompts/extras/existing-site-roast.md` first.
- `inputs/brief.md` and anything else in `inputs/` (assets, photos, notes).
- If they exist, use these for context (not required): `outputs/01-*` (site brief), `outputs/02-*` (persona and journey), `outputs/03-*` (key factors).
- You may revisit the existing site to check a detail, but don't redo the review.

## Principles
- **Fix the High-severity findings first.** Don't bury them under polish.
- **Fit the client's reality.** Respect the budget, timeline, available assets and team capacity stated in the brief. If a recommendation needs something the client doesn't have (photos, case-study data, testimonials), say what's needed and mark it `[TODO: ...]`.
- **Show, don't tell.** Prefer recommendations that let visitors see proof (projects, numbers, real photos) over adding more claims.
- **Keep it simple.** Fewer, clearer pages and decisions beat more features. Don't recommend things because they're trendy.
- **Keep what works.** Carry forward everything in the roast's "What works" list unless there's a reason not to.
- **No invented facts.** Example copy may use only facts from `inputs/`. Use `[TODO: ...]` for any number, name, client or testimonial you don't have.
- **Confidentiality:** same rule as the roast. Use the client name from `inputs/brief.md` only; never the real brand's name, text or assets.

## What to cover

### 1. Messaging
- Positioning in one sentence: who it's for, what they get, why this company.
- Recommended homepage headline + subheadline (2–3 options), using the client's real differentiators from the brief.
- How each service and sector should be described (structure, not full copy).
- Proof to surface and where: which numbers, projects, certifications, client types.
- Tone of voice: 3–4 do/don't pairs based on what's wrong today.
- Language decision: what language(s) the site should use and how to handle mixed content (e.g. blog in a different language).
- CTA wording and hierarchy (primary vs secondary action).

### 2. Architecture
- Proposed sitemap (tree) with a one-line purpose per page. Mark pages as new / keep / merge / remove compared to the current site.
- Primary navigation and footer.
- Homepage section order, with the job of each section.
- Project/case-study template: which fields every project should show.
- Conversion path: how a visitor gets from landing to enquiry in as few steps as possible; how to handle WhatsApp, forms and phone.
- Technical/SEO basics to fix (redirects for removed URLs, titles, headings, speed, mobile).

### 3. Visual
- Overall direction in 2–3 sentences, tied to the client's tier and audience (and to the sites they like/dislike in the brief).
- Typography, colour and spacing direction (not a full design system — that's step 07).
- Photography and imagery: what to use from existing assets, what to stop using, what to shoot or create.
- Layout patterns for key components: hero, project cards, sector pages, proof/stat blocks, CTA blocks.
- Mobile-specific fixes.
- What to avoid, based on the roast findings and client dislikes.

## Output
Write to `outputs/extras/existing-site-recommendations.md`:

1. **Summary** — the 5 changes that would make the biggest difference, one line each.
2. **Messaging** — as above.
3. **Architecture** — as above, including the sitemap tree.
4. **Visual** — as above.
5. **Finding → fix map** — table: roast finding / severity / recommendation / area (visual, architecture, messaging).
6. **Priority plan** — three groups:
   - **Quick wins** — fixable on the current site now (low effort, real impact).
   - **Redesign must-haves** — needed in the new site.
   - **Later** — nice to have once the basics work.
   For each item: rough effort (S/M/L) and what it depends on (e.g. client photos, case-study data).
7. **What we need from the client** — all `[TODO: ...]` items collected in one list.

If the main workflow later runs steps 04 (sitemap), 05 (copywriting) or 07 (design system), those steps are the source of truth. This document is input for them, not a replacement.
