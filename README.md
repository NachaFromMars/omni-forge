# Omni Forge Novel

> Multi-agent AI novel writing system with Sequential Competition, Mix Edition, and council-based quality gates.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)
[![Version](https://img.shields.io/badge/Version-1.2A-orange)](/)

## Overview

**Omni Forge Novel** is an orchestration skill for AI-assisted novel writing. It runs multiple AI agents against the same scene or chapter beat, evaluates outputs through a council scoring system, and selects (or mixes) the best result — producing consistently higher-quality prose than single-pass generation.

## Core Concepts

### Sequential Competition
Multiple AI agents each write the same passage independently. Outputs are scored across dimensions (prose quality, pacing, consistency, originality) and the winner advances to the next stage.

### Mix Edition
Instead of picking a single winner, the system extracts the strongest elements from each candidate and merges them into a hybrid output — combining narrative momentum from one draft with character voice from another.

### Council Evaluation
A dedicated evaluation agent (or panel) scores each candidate on a 0–10 rubric. Only outputs scoring ≥ 7 pass the gate and move forward.

## When to Use

- Writing chapters or scenes with high creative stakes (climax, twist, opening, ending)
- Breaking out of repetitive AI prose patterns
- Generating multiple stylistic variants before committing to a direction
- Long-form novel projects requiring consistent quality across 50–100+ chapters

## Files

| File | Purpose |
|---|---|
| `SKILL.md` | OpenClaw skill entrypoint |
| `forge-workflow.md` | Full pipeline workflow documentation |
| `checklist.md` | Pre/post-forge quality checklist |
| `diagnostics.md` | Debugging stuck agents, stalled outputs |

## Workflow at a Glance

```
Beat prompt → N agents write independently
     ↓
Council scores each output (0–10)
     ↓
Score ≥ 7?  ──Yes──► Select best / Mix edition
            ──No───► Retry with adjusted prompt
     ↓
Final output → Novel Guardian scan → FINAL
```

## Related Skills

- [novel-guardian](https://github.com/NachaFromMars/novel-guardian) — Continuity + consistency checker
- [novel-master](https://github.com/NachaFromMars/novel-master) — 5-layer chapter QA system
- [novelcore-ai](https://github.com/NachaFromMars/novelcore-ai) — Structured beat prompting (4-block, 3-variant)
- [forge-novel-guard](https://github.com/NachaFromMars/forge-novel-guard) — Pre/post-forge verification scripts

---

Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.
