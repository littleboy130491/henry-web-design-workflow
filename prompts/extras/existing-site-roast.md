# Extra — Roast the Existing Website

## Goal
Give an honest, calibrated critique of the client's current website. Say plainly what is broken, weak or confusing, and also what already works. This is a diagnosis, not a performance: every point must be true, specific and weighted by how much it actually hurts the business.

## Inputs
- `inputs/brief.md` — the client's goals, audience, known problems, existing site notes.
- Any other material in `inputs/` (notes, screenshots, analytics exports).
- The existing site itself. Take the URL from `inputs/`. If no URL or screenshots are available, stop and ask the user for one.
- If they exist, use these for context (not required): `outputs/01-*` (site brief), `outputs/02-*` (persona and journey), `outputs/03-*` (key factors).

## Context first
Before judging anything, write down in 3–5 bullets what this site is for:
- Who visits it (from the brief or persona output), on what device, and at what stage of their decision.
- What the site needs them to do (enquire, WhatsApp, download, call, apply).
- What market and price tier the client is in, and what "good" looks like for that market. Compare to the client's real competitors and peers named in the brief, not to award-winning agency sites or global brands with 100x the budget.

Judge every issue against this context. A stock photo on a local service site is a trust problem; the same photo on a template blog is a non-issue. Say which one it is.

## How to review
Look at the site directly. Cover at least the homepage, one service/sector page, one project/portfolio page, the about page, the contact path, and the mobile version. Take screenshots where your tools allow and save them to `outputs/extras/screenshots/`.

Review these areas:
1. **First impression (5-second test)** — Can a first-time visitor tell what the company does, for whom, and where, without scrolling?
2. **Messaging** — Headlines, value proposition, service descriptions. Is it specific or generic? Does it say what the brief says makes the client different, or does it hide it? Is the language consistent (mixed languages, tone shifts)?
3. **Proof and trust** — Projects, numbers, clients, certifications, photos, testimonials. Is proof shown or just claimed? Are images real or stock/AI?
4. **Information architecture** — Navigation, page structure, how easy it is to find a relevant project or sector. Dead ends, duplicates, orphan pages.
5. **Visual design** — Hierarchy, typography, colour, spacing, image quality, consistency between pages. Does it look like the tier the client charges for?
6. **Conversion path** — CTAs, contact options, forms, WhatsApp links. How many steps to enquire? Anything confusing or contradictory (e.g. two numbers)?
7. **Technical basics** — Mobile layout, load speed (rough, observed), broken links or bugs, obvious SEO gaps (titles, headings, indexable content), accessibility basics (contrast, alt text, tap targets).

## Calibration rules
- **No inflation.** Don't use words like "disaster", "nightmare", "unusable" unless it truly is. A slightly off font size is a minor note, not a crisis.
- **Evidence for every point.** Name the page and the element. "The homepage hero says X, which doesn't mention Y" beats "the messaging is weak".
- **Separate what you saw from what you suspect.** If you couldn't verify something (e.g. load speed without a proper test, how a form behaves after submit), say so.
- **Rate severity** for every issue:
  - **High** — loses enquiries or damages trust with the target audience.
  - **Medium** — creates friction or weakens the pitch, but people still get through.
  - **Low** — polish; worth fixing during the redesign but not urgent.
- **Credit what works.** List the things worth keeping. If something is fine, say it's fine.
- **Check the brief's known problems.** Confirm, correct or add nuance to each problem the client already listed. Don't just repeat them as findings.
- **Tone:** direct and a bit sharp is fine, sarcasm and mockery are not. Write like a senior designer talking to a colleague, not a YouTube roast.

## Confidentiality
If the site you review belongs to the real brand behind a dummy brief, refer to it only by the client name in `inputs/brief.md`. Don't copy the real brand's name, copy text or images into `outputs/`. Describe or paraphrase instead of quoting.

## Output
Write to `outputs/extras/existing-site-roast.md`:

1. **The short version** — 4–6 sentences: overall verdict, the 3 problems that cost the client the most, and the 1–2 things worth keeping.
2. **Context** — the bullets from "Context first".
3. **What works** — keep list, with reasons.
4. **Findings by area** — one section per review area. Each finding: what it is, where (page/element), why it matters for this audience, severity. Mark unverified points as `(unverified)`.
5. **Known problems from the brief** — table: problem as stated / confirmed? / notes.
6. **Severity summary** — table of all findings sorted High → Low.
7. **Open questions / TODOs** — anything you couldn't check or need from the client, as `[TODO: ...]`.

Don't write solutions here beyond a one-line hint where it helps explain the problem. Recommendations are the next prompt (`existing-site-recommendations.md`).
