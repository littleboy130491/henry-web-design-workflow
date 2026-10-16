# 09 — Generate Visual Assets

**Reads:** `outputs/08-visual-assets.md`, `outputs/07-design-system/design-system.md`
**Writes:** `outputs/09-visuals/<slot-id>.<ext>` + `outputs/09-visuals/_log.md`

## Task
Generate every visual marked `generate` in the asset list, using the available AI image skill/tool (e.g. GPT Image, Nano Banana). If no image-generation tool is available, stop and tell the user.

## Steps
1. Before generating everything, make 1–2 test images for the most important slot (usually the hero) and show them to the user to lock the style. Continue only after approval.
2. Generate each slot using its prompt from step 08. Add the shared style suffix (palette, lighting, style) so all images look like one set.
3. Produce at the aspect ratio and size the slot requires. Make 2–3 variations per slot when it matters (hero, key sections).
4. Review each image: check for AI artifacts (hands, faces, text, logos, extra limbs, warped objects), off-brand colors, and whether it actually communicates the slot's purpose. Regenerate failures.
5. Export web-ready versions (WebP/AVIF + fallback, compressed) next to the originals.

## Log (`_log.md`)
For each slot: ID, final file, prompt used, tool/model, number of attempts, chosen variation and why, known issues.
Mark any slot that should be replaced by a real photo before launch.
