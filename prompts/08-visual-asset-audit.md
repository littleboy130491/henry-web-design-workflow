# 08 — Visual Asset Audit & Shot List

**Reads:** everything in `inputs/`, `outputs/04-sitemap.md`, `outputs/05-copy/`, `outputs/07-design-system/design-system.md`
**Writes:** `outputs/08-visual-assets.md`

## Task
Match every visual the site needs to an existing asset from `inputs/`. For anything missing, write a detailed brief so it can be generated (step 09), shot, or sourced.

## Steps
1. Inventory all images/video/logos in `inputs/`: filename, what it shows, resolution, quality (usable / needs editing / unusable), and any rights concerns.
2. Go page by page, section by section through the sitemap and the "Visual note" in the copy. List every visual slot.
3. Assign an existing asset where it fits. Otherwise, mark it as missing.

## Output structure
**Asset inventory** (table): file → description → resolution → quality → suggested use.

**Visual slots** (table): ID (e.g. `home-hero-01`) → page/section → purpose (what it must communicate) → status (`have` / `edit` / `generate` / `photoshoot` / `stock` / `illustration` / `icon`) → source file or "missing".

**Missing asset briefs** — for each missing item:
- ID, placement, aspect ratio and minimum size (from the design system).
- What it must communicate (tie to the key factor from step 03).
- Subject, setting, people (age, look, clothing, expression — matching the persona), composition, camera angle, lighting, color palette (from the design system), mood, style.
- Space reserved for text overlay, if any.
- What to avoid (clichés, competitor look-alikes, anything off-brand).
- **Recommended source** — AI-generated, real photoshoot, or stock — and why. Use real photos for things that must be authentic (team, actual products, real projects, office); AI is fine for atmospheric, abstract, or illustrative visuals.
- A ready-to-use **image generation prompt** for items marked `generate`.
