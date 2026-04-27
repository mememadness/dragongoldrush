# Dragon Gold Rush — Roadmap

This roadmap tracks the major development milestones for Dragon Gold Rush. For detailed weekly progress, see the [Weekly Updates](WeeklyUpdates/).

**Last Updated:** 27 April 2026

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
| **Sprite Design & UI** | | | | | 🟩 | 🟩 | 🟩 | 🟩 | | | | |
| **Dragon Token Integration** | | | | | | | 🟧 | 🟧 | 🟧 | | | |
| **Story Mode** | | | | | | | 🟧 | 🟧 | 🟧 | 🟧 | 🟧 | 🟧 |
| **Dragon Token Economy** | | | | | | | | | ⬜ | ⬜ | ⬜ | ⬜ |
| **Fiber Network** | | | | | | | | | | ⬜ | ⬜ | ⬜ |

> 🟩 Completed · 🟧 In Progress · 🟥 Planned · ⬜ Future

---

## Month 1 — Music & Audio ✅ Completed

- 7 original tracks by Mondrin (one half of [Tunnel Club](https://tunnelclub.bandcamp.com/)) integrated with per-theme playback
- Title screen music, crossfade transitions, special item SFX
- iOS audio compatibility, mute/options controls
- All planned music and audio work is fully integrated and live

## Sprite Design & UI Enhancements ✅ Completed

- **Completed:** Treasure sprites V2, jewel variants, blocker rework, themed zone art (sanctum, abyss, throne, summit), desktop layout overhaul, unified font system, SHOP button and streamlined PLAY flow
- **Outcome:** [ludo.ai](https://ludo.ai) partnership delivered the full sprite library; engagement now closed

## Month 2–4 — Dragon Token Integration 🔄 In Progress (pulled forward)

The integration phase that brings Dragon Token into gameplay — building the credit system, payment infrastructure, and prize pool that the broader Dragon Token Economy depends on.

- **Completed:** Dragon credit system with reserve-confirm purchase flow, ACP cell architecture, prize pool with contributions and payouts, backend-authoritative special-item inventory, Dragon economics and pricing engine
- **In Progress:** Moving Dragon token payments from dev to full production, shop refinement using the new sprite library
- **Remaining:** In-game shop for special items powered by Dragon credits

## Months 4–9 — Story Mode 🔄 In Progress (New)

A new single-player progression mode introducing structured content beyond the existing leaderboard challenge. Designed as a long-running content track to drive player engagement and retention.

- **Planning:** 1000-level content roadmap with structured progression and narrative beats
- **Monetisation:** Free-to-play with a 2-item-per-attempt soft cap — accessible to new players, with item purchases via the Dragon credit system for those who want to push further
- **Engine foundation:** The robust gravity engine and new level schema (chains, irregular shapes, variants) provide the technical groundwork
- **Next:** Content production begins May 2026 using the new level authoring tools and sprite library

## Ongoing — Dragon Token Economy 🔄

The game has pivoted from UTXOSwap (a third-party DEX) to a native Dragon Token credit system. UTXOSwap is no longer actively maintained and its testnet is unsupported, so we built our own in-game swap and credit system. Dragon is now a first-class in-game currency.

- **Completed:** Credit purchase flow (reserve-confirm), ACP cell architecture, prize pool contributions and payouts, backend-authoritative inventory, Dragon economics and pricing engine
- **Planned:** Expanded in-game shop with special item purchases via credits, Dragon token staking rewards, tournament entry fees, player-to-player trading
- **Long-term vision:** Dragon Token as the sole in-game currency powering play, rewards, and marketplace — fully on-chain via Nervos CKB

## Future — Fiber Network Integration 🔮

- 1v1 battle mode via CKB Fiber Network (currently "Coming Soon" in battle lobby)
