# 10 — Build the Homepage

**Reads:** `outputs/04-sitemap.md`, `outputs/05-copy/home.md`, `outputs/05-copy/_global.md`, `outputs/07-design-system/`, `outputs/08-visual-assets.md`, `outputs/09-visuals/`, `outputs/06-references.md`
**Writes:** `outputs/site/` (homepage + shared header, footer, styles)

## Task
Build the homepage strictly from the design system, sitemap, and copy. This page sets the pattern for every other page, so build shared parts properly.

## Stack
Use the platform from the brief. If none is specified, use static HTML + CSS (+ minimal vanilla JS), importing `tokens.css`.

## Rules
- Use only design-system tokens and components. If you need something new, add it to the design system first and note it.
- Follow the section order and copy exactly. Don't rewrite copy; if something doesn't work in layout, flag it.
- Use the assigned visuals per slot. If a visual is still missing, use a clearly labeled placeholder with the correct ratio.
- Mobile-first and responsive at all design-system breakpoints. No horizontal scroll.
- Semantic HTML, one `<h1>`, logical heading order, alt text on images, visible focus states, keyboard-usable nav, labels on form fields.
- Performance: lazy-load below-the-fold images, size images correctly, no heavy libraries without reason.
- Fill in the title tag and meta description from step 04.
- Build header, footer, and shared components as reusable pieces.

## Before finishing
Open the page in a browser. Check desktop (1440px), tablet (768px), and mobile (375px). Take screenshots into `outputs/site/_screenshots/` and fix anything broken. Summarize what was built and any deviations from the design system or copy.
