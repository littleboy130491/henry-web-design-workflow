# 11 — Build All Remaining Pages

**Reads:** `outputs/04-sitemap.md`, `outputs/05-copy/`, `outputs/07-design-system/`, `outputs/09-visuals/`, `outputs/08-visual-assets.md`, existing `outputs/site/`
**Writes:** `outputs/site/`

## Task
Build every remaining page in the sitemap, consistent with the homepage.

## Rules
- Same rules as step 10 (design-system only, exact copy, accessibility, responsive, performance, SEO meta).
- Reuse the homepage's header, footer, and shared components. Don't duplicate or fork them.
- Build pages in sitemap order. After each page, check it in the browser before moving on.
- Wire up all links: nav, footer, in-content links, CTAs. No dead links (`#` placeholders must be listed).
- Forms: working markup and validation; note which backend/integration is needed (from the brief).
- Add a 404 page, favicon, `sitemap.xml`, and `robots.txt` if the stack doesn't generate them.

## Before finishing
- Screenshot each page at 1440 / 768 / 375 into `outputs/site/_screenshots/`.
- Click through every conversion path from step 04 and confirm it works end to end.
- Output a page checklist: page → built → copy complete → visuals final/placeholder → open TODOs.
