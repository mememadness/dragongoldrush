# Dragon Gold Rush — Roadmap

This roadmap tracks the major development milestones for Dragon Gold Rush. For detailed weekly progress, see the [Weekly Updates](WeeklyUpdates/).

**Last Updated:** 20 April 2026

### Status Legend

| Status | Meaning |
|--------|---------|
| **Completed** | Fully integrated and live |
| **In Progress** | Actively being worked on |
| **Planned** | Scoped and scheduled |
| **Future** | On the radar, not yet scheduled |

---

## Project Timeline

| Milestone | Oct | Nov | Dec | Jan | Feb | Mar | Apr | May | Jun | Jul | Aug | Sep |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **Bootstrap** | 🟩 | 🟩 | 🟩 | | | | | | | | | |
| **Music & Audio** | | | | 🟩 | 🟩 | 🟩 | | | | | | |
| **Sprite Design & UI** | | | | | 🟧 | 🟧 | 🟧 | 🟧 | | | | |
| **In-Game Rewards** | | | | | | | 🟧 | 🟧 | 🟧 | | | |
| **Dragon Token Economy** | | | | | | | | | ⬜ | ⬜ | ⬜ | ⬜ |
| **Fiber Network** | | | | | | | | | | ⬜ | ⬜ | ⬜ |

> 🟩 Completed · 🟧 In Progress · 🟥 Planned · ⬜ Future

---

## Month 1 — Music & Audio ✅ Completed

- 7 original tracks by Mondrin (one half of [Tunnel Club](https://tunnelclub.bandcamp.com/)) integrated with per-theme playback
- Title screen music, crossfade transitions, special item SFX
- iOS audio compatibility, mute/options controls
- All planned music and audio work is fully integrated and live

## Month 1–3 — Sprite Design & UI Enhancements 🔄 In Progress

- **Completed:** Level restructure with new themed zones (sanctum, abyss, throne, summit) and background art
- **In Progress:** Evaluating [ludo.ai](https://ludo.ai) for AI-assisted game asset generation, replacing earlier Fiverr-based approach
- **Revised Target:** Visual updates now expected Month 3–4 (slipped from original Month 2 target while sourcing approach is refined)

## Month 2–4 — In-Game Rewards 🔄 In Progress (pulled forward)

- **Completed:** Dragon credit system with reserve-confirm purchase flow, ACP cell architecture, prize pool with contributions and payouts, backend-authoritative special-item inventory, Dragon economics and pricing engine
- **In Progress:** Moving Dragon token payments from dev to full production, shop refinement
- **Remaining:** In-game shop for special items, potential one-off original NFTs

## Ongoing — Dragon Token Economy 🔄

The game has pivoted from routing payments through UTXOSwap (a third-party DEX) to a native Dragon Token credit system. Dragon is now a first-class in-game currency.

- **Completed:** Credit purchase flow (reserve-confirm), ACP cell architecture, prize pool contributions and payouts, backend-authoritative inventory, Dragon economics and pricing engine
- **Planned:** Expanded in-game shop with special item purchases via credits, Dragon token staking rewards, tournament entry fees, player-to-player trading
- **Long-term vision:** Dragon Token as the sole in-game currency powering play, rewards, and marketplace — fully on-chain via Nervos CKB

## Future — Fiber Network Integration 🔮

- 1v1 battle mode via CKB Fiber Network (currently "Coming Soon" in battle lobby)
