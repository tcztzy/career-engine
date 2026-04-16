# career-engine

Markdown-first skill project for understanding real work, not just getting hired.

## Core idea

Most career tools optimize for applications.
`career-engine` optimizes for a deeper loop:

1. observe real work
2. map teams, incentives, and status games
3. talk to people
4. test hypotheses about roles and environments
5. record what changed in your model of work
6. decide where to get closer and where to stay away

The project is intentionally low-tech:

- markdown first
- no assumed dev environment
- avoid running code unless truly needed
- if a script is necessary, prefer `uv run` or `uvx`
- skill files are the main product

## Layout

- `SKILL.md`: repo entrypoint
- `skills/career-engine/SKILL.md`: installable main skill
- `skills/career-engine/references/loop.md`: field loop and artifact model
- `.codex-plugin/plugin.json`: Codex repo plugin manifest
- `.claude-plugin/marketplace.json`: Claude Code marketplace manifest

## Install

### Hermes

Use the repo `skills/` directory as a local skill root.

### Codex

Open the repo as a repo plugin and install the plugin from `.codex-plugin/plugin.json`.

### Claude Code

Use `.claude-plugin/marketplace.json` as the marketplace manifest.

## Scope

This project is for:

- role sensing
- team and manager reading
- workplace ethnography
- informational interview loops
- offer interpretation in social context
- learning what kinds of work make a life better or worse

It is not mainly:

- resume automation
- spray-and-pray application volume
- shallow keyword matching
