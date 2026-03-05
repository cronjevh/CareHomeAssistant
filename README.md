# CareHomeAssistant

Public documentation repository for a DIY caregiving digital assistant built with Home Assistant, View Assist, and OpenClaw memory capabilities.

## Goals

- Keep a high-signal, assistant-friendly project context across related repositories.
- Document implementation details so others can reproduce and contribute.
- Evolve the documentation into a plug-and-play "Care Assistant" starter.

## Core Repositories

- https://github.com/cronjevh/OpenClawHomeAssistant
- https://github.com/cronjevh/View-Assist
- https://github.com/cronjevh/ViewAssistCompanionApp

## Documentation Wiki

- [Docs Home](docs/README.md)
- [Living Project Summary](docs/living/project-summary.md)
- [Active Workstreams](docs/living/workstreams.md)
- [Inbox Registry (generated)](docs/_generated/inbox-registry.md)

## Inbox Processing Workflow

1. Drop markdown files into `.PROMPTS/INBOX/`.
2. Run `pwsh -File scripts/process-inbox.ps1`.
3. Review generated output in `docs/source/` and `docs/_generated/`.
4. Update living pages in `docs/living/` if new decisions or priorities emerged.

## Repository Conventions

- `docs/source/`: Canonical copies of inbox artifacts, grouped by topic.
- `docs/_generated/`: Script-generated indexes and manifests.
- `docs/living/`: Curated, continuously maintained project narrative.

## License

This repository uses the [MIT License](LICENSE).
