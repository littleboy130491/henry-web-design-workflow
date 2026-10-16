# Web Design Agent Workflow

## Folders
- `inputs/` — client material: brief, logo, brand files, photos, existing site URL, notes. Read-only for agents; never modify or delete.
- `outputs/` — everything agents produce. Each step writes to its own numbered file/folder.
- `prompts/` — one prompt per workflow step. **Never read files in `prompts/` unless the user explicitly tells you to run or open a specific prompt.**

## Rules
- Run one step at a time, only when the user asks. Don't start the next step on your own.
- Each step reads the outputs of earlier steps. If a required earlier output is missing, stop and tell the user which step to run first.
- Never invent facts about the client (prices, numbers, testimonials, certifications, team names). Mark missing facts as `[TODO: ...]` and list them at the end of the output.
- When a step's output already exists, update it in place and add a short "Changes" note at the top instead of starting over, unless the user asks for a rewrite.
- Never read `inputs/brief-sources.md` unless the user asks. It maps a dummy brief back to the real site it was based on. Never use the real brand's name, text, or assets in `outputs/`.
- Write in the language the client's site will use (check the brief). Default to English if unclear.
