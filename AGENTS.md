# AGENTS

## Mission
- Build a markdown-first career fieldwork system.
- Optimize for understanding real workplaces, teams, incentives, and power relations.
- Treat job search as one possible output, not the center.

## Constraints
- Do not assume the user machine has a development environment.
- Prefer no code execution.
- Prefer markdown, csv, and plain text over apps and automation.
- If execution is truly needed, prefer `uv run` or `uvx`.
- Avoid introducing framework-heavy workflows unless the user explicitly asks.

## Product shape
- `SKILL.md` files are the main product.
- The repository should remain installable as a skill source for Hermes, Codex, and Claude Code.
- New capabilities should usually appear as markdown references, prompts, rubrics, or checklists before any script exists.

## Writing style
- Concrete, field-oriented, anti-bullshit.
- Prefer observation prompts, interview prompts, and synthesis loops.
- Avoid managerial jargon and empty motivational language.
