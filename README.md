# Agentic Music OS

> The SIP-conformant operating system for AI-assisted music creation and production — part of the [FrankX Intelligence Systems](https://github.com/frankxai/frankxai/blob/main/ECOSYSTEM.md) family.

## What this is

Agentic Music OS is the **operation layer** for music: it turns intent ("a dark synthwave track at 110 BPM with a hopeful bridge") into a produced, iterated, release-ready output by orchestrating generation, arrangement, and mastering agents. It composes the music substrate below it.

## Where it sits in the stack

```
agentic-music-os  →  composes  →  music-intelligence-system (substrate)
                                   SIS (memory) · ACOS (skills) · SIP (standard)
```

- **Substrate:** [music-intelligence-systems](https://github.com/frankxai/music-intelligence-systems) holds theory, references, and production knowledge.
- **Generation:** wraps [suno-mcp-server](https://github.com/frankxai/suno-mcp-server) and other model providers.
- **Memory & skills:** [SIS](https://github.com/frankxai/Starlight-Intelligence-System) + [ACOS](https://github.com/frankxai/agentic-creator-os).
- **Frequency/state work:** sibling to [vibe-os](https://github.com/frankxai/vibe-os).

## Planned modules

- `compose/` — prompt → song spec → generation → variations
- `arrange/` — structure, transitions, stems
- `master/` — loudness, EQ, release prep
- `taste/` — learns the producer's preferences over time (12,000+ songs of signal)
- `agent-skills/` — installable music skills for any runtime

## Status

🌱 Scaffolding. OS contract defined; `compose/` first.

---

<sub>Part of the <a href="https://github.com/frankxai/frankxai/blob/main/ECOSYSTEM.md">FrankX ecosystem</a>.</sub>
