# Active Workstreams

## Priorities

1. Wake-word reliability for real-world elderly-user speech patterns.
2. Conversation cadence improvements in wake-to-stream-to-release flow.
3. Predictable HA UX behavior for streamed AI response cards.
4. Repeatable model testing and deployment workflow.

## Workstream Map

| Workstream | Current State | Primary Artifacts |
| --- | --- | --- |
| Platform setup and tooling | Baseline setup captured; update as toolchains change | `docs/source/setup/AGENTIC_DEV_SETUP.md`, `docs/source/setup/lineageos-adb-setup.md` |
| App architecture and behavior | Core architecture documented; needs periodic sync with code changes | `docs/source/reference/CLAUDE.md`, `docs/source/architecture/elderly-voice-assist-overview.md` |
| Wake-word and DSP evolution | Active research and implementation planning | `docs/source/research/porcupine-migration-plan.md`, `docs/source/research/rnnoise-impplementation-plan.md`, `docs/source/research/porcupine-exploration.md` |
| Session continuity and handoff | Two handoffs currently ingested | `docs/source/handoffs/handoff-2026-02-28.md`, `docs/source/handoffs/handoff-2026-03-01.md` |
| Troubleshooting playbooks | Multiple targeted troubleshooting docs ingested | `docs/source/troubleshooting/*.md` |

## Next Documentation Actions

1. Add a stable architecture diagram once protocol/data flow is finalized.
2. Normalize typo-prone filenames in source docs while preserving original references.
3. Add a short "reproduce on fresh machine" checklist tied to tested versions.
