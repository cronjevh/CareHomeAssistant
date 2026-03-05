# Contributing

## Scope

This repository is documentation-first. Contributions should improve reproducibility, clarity, and operational safety for the caregiving assistant stack.

## Recommended Flow

1. Add raw notes to `.PROMPTS/INBOX/` as markdown.
2. Run `pwsh -File scripts/process-inbox.ps1`.
3. Review generated changes under:
   - `docs/source/`
   - `docs/_generated/`
4. Update curated docs in `docs/living/` as needed.
5. Open a PR with a clear summary of:
   - New or updated artifacts
   - Decisions captured
   - Any unresolved questions

## File Naming

- Use lowercase with hyphens where possible.
- Include dates for handoffs: `handoff-YYYY-MM-DD.md`.
- Keep one topic per file.

## Quality Bar

- Prefer explicit commands, versions, and paths over generic advice.
- Include device/environment assumptions.
- Mark uncertain items as hypotheses, not facts.
