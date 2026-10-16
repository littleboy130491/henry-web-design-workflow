# 07 — Design System

**Reads:** `outputs/01-site-brief.md`, `outputs/03-key-factors.md`, `outputs/04-sitemap.md`, `outputs/06-references.md`, brand files in `inputs/`
**Writes:** `outputs/07-design-system/design-system.md`, `outputs/07-design-system/tokens.css`, `outputs/07-design-system/preview.html`

## Task
Create a design system that expresses the chosen visual direction, respects existing brand assets, and covers every component the sitemap needs.

## Steps
1. Start from the existing brand (logo, colors, fonts). Extend it; don't replace it unless the brief says a rebrand is in scope.
2. Use the direction chosen in step 06 (ask the user if none was chosen).
3. Define tokens, then components. Base the component list on the sections in `outputs/04-sitemap.md` — no unused components.

## Must include
- **Color** — brand, neutrals, surface/background, text, border, states (success/warning/error), with hex values. Check text contrast meets WCAG AA. Light mode required; dark mode only if needed.
- **Typography** — font families (Google Fonts or licensed brand fonts), type scale (display → caption) with size/line-height/weight for desktop and mobile.
- **Spacing & layout** — spacing scale, container widths, grid, breakpoints, section padding.
- **Shape & depth** — radius, borders, shadows.
- **Imagery style** — photo style, illustration style, icon set, image ratios (feeds steps 08–09).
- **Motion** — durations, easing, what animates and what doesn't. Respect `prefers-reduced-motion`.
- **Components** — buttons (all variants and states), links, nav/header, footer, cards, forms/inputs, testimonial, CTA band, and anything else the sitemap needs. For each: anatomy, variants, states, usage rules.
- **Voice in UI** — microcopy rules (button labels, error messages).

## Deliverables
- `tokens.css` — CSS custom properties for all tokens.
- `preview.html` — one page that renders the tokens and every component so it can be reviewed visually. Open it in a browser and check it before finishing.
