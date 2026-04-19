# Levelwright

> Open-source, handheld-native, system-level AI gaming assistant.
> Starting with Steam Deck.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Status: design complete](https://img.shields.io/badge/status-design%20complete-orange)](https://github.com/levelwright/levelwright/blob/main/DESIGN.md)
[![Phase 1: in progress](https://img.shields.io/badge/phase%201-in%20progress-yellow)](https://github.com/levelwright/levelwright/blob/main/docs/prd/levelwright-poc-prd.md)

---

## What we're building

An AI agent that runs locally on your Steam Deck (and, soon, other handhelds)
and actually knows what it's doing about handheld gaming. It can:

- Answer **"what's my battery, CPU temp, TDP?"** without tabbing out of a game
- Check **ProtonDB compatibility** and **Deck Verified** status before you buy or launch
- Recommend **"what should I play?"** from your library based on playtime, compat,
  and how much battery you actually have
- Scale to **ROG Ally, Legion Go, MSI Claw** via a pluggable hardware adapter

Think NVIDIA Project G-Assist, but open-source, handheld-first, AMD-friendly,
and not locked to Windows.

---

## Where it came from

Inspired by [TechDweeb&#39;s April Fools &#34;PocketDweeb&#34; concept](https://www.youtube.com/watch?v=JLG4d5Opo14) —
except we're building it for real. NVIDIA proved the concept viable when
their own April Fools joke (Project G-Assist) shipped as a real RTX product
in 2025. No one had built the open-source, handheld-native version. That's us.

---

## Repositories

| Repo                                                             | What's in it                                                                                                                            |
| ---------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| [**levelwright**](https://github.com/levelwright/levelwright) | Design docs, PRD, ADRs, Hermes plugins (`levelwright-system`, `levelwright-steam`), Decky plugin, install scripts. The whole stack. |

More repos may split off later (commercial desktop app, reference adapters for non-Deck handhelds). For now, everything lives in the main repo.

---

## Status

**Design phase:** complete. See [`DESIGN.md`](https://github.com/levelwright/levelwright/blob/main/DESIGN.md).
**PRD:** v0.1.0 scope locked. See [`docs/prd/levelwright-poc-prd.md`](https://github.com/levelwright/levelwright/blob/main/docs/prd/levelwright-poc-prd.md).
**Architecture Decisions:** 11 ADRs. See [`docs/adr/`](https://github.com/levelwright/levelwright/tree/main/docs/adr).
**First public release:** targeting Decky Plugin Store, summer 2026.

---

## Built on

- [Hermes-Agent](https://github.com/NousResearch/hermes-agent) — Python-based AI agent runtime with plugins, memory, and an OpenAI-compatible API
- [Decky Loader](https://github.com/SteamDeckHomebrew/decky-loader) — Steam Deck homebrew plugin framework
- [ProtonDB](https://www.protondb.com/) — community compatibility data
- Steam Web API — owned games, playtime, achievements

---

## Get involved

The project is in early build. Contribution process and CLA will be posted
when Phase 1 lands the first public release. Watch the main repo for updates.

---

**License:** MIT, for all core code.
See [`LICENSE`](https://github.com/levelwright/levelwright/blob/main/LICENSE) in the main repo.
