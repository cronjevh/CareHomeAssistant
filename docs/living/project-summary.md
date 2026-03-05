# Project Summary

## Mission

CareHomeAssistant documents and operationalizes a DIY caregiving digital assistant focused on practical home use and accessibility for elderly users, including users with mild cognitive impairment (MCI).

## Solution Shape

- Device layer: View Assist Companion App (VACA) on Android-based display hardware.
- Home layer: Home Assistant voice pipeline (wake, STT, conversation, TTS, automations).
- Memory/context layer: OpenClaw integration patterns for personalization and continuity.

## Current Technical Focus

- Wake-word reliability and model fit for the intended user voice.
- Audio capture/DSP stability on constrained Echo Show 5 (Gen 2) hardware.
- Migration planning from OpenWakeWord to Porcupine.
- RNNoise integration and objective pre/post DSP diagnostics.
- Conversation cadence timing from wake detection to stream release and detect re-arm.
- HA dashboard response lifecycle behavior (deterministic auto-clear).

## Documentation Strategy

- Raw notes enter through `.PROMPTS/INBOX`.
- `scripts/process-inbox.ps1` ingests and categorizes all inbox markdown docs.
- Canonical source copies are kept in `docs/source/`.
- Living narrative is maintained in `docs/living/`.
