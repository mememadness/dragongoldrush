# Dragon Gold Rush — Roadmap

This roadmap tracks the major development milestones for Dragon Gold Rush. For detailed weekly progress, see the [Weekly Updates](WeeklyUpdates/).

**Last Updated:** 3 May 2026

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
| **Sprite Design & UI** | | | | | 🟩 | 🟩 | 🟩 | | | | | |
| **Dragon Token Integration** | | | | | | | 🟧 | 🟧 | 🟩 | | | |
| **Level Redesign (V2 sprites)** | | | | | | | 🟧 | 🟧 | 🟧 | | | |
| **Story Mode** | | | | | | | 🟧 | 🟧 | 🟩 | 🟧 | 🟧 | 🟧 |
| **Dragon Token Economy** | | | | | | | | | 🟧 | 🟧 | 🟧 | 🟧 |
| **Fiber Network** | | | | | | | | | | 🟥 | 🟥 | 🟥 |

> 🟩 Completed / Live · 🟧 In Progress · 🟥 Planned · ⬜ Future
>
> Grid covers the project's first year (Oct 2025 → Sep 2026). Story Mode, Dragon Token Economy, and Fiber Network all continue beyond the visible window.

---

## Month 1 — Music & Audio ✅ Completed

- 7 original tracks by Mondrin (one half of [Tunnel Club](https://tunnelclub.bandcamp.com/)) integrated with per-theme playback
- Title screen music, crossfade transitions, special item SFX
- iOS audio compatibility, mute/options controls
- All planned music and audio work is fully integrated and live

## Sprite Design & UI Enhancements ✅ Completed

- **Completed:** Treasure sprites V2, jewel variants, blocker rework, themed zone art (sanctum, abyss, throne, summit), desktop layout overhaul, unified font system, SHOP button and streamlined PLAY flow
- **Outcome:** [ludo.ai](https://ludo.ai) partnership delivered the full sprite library; engagement now closed

## Month 2–4 — Dragon Token Integration 🔄 In Progress (Pre-Prod UAT)

The integration phase that brings Dragon Token into gameplay — building the credit system, payment infrastructure, and prize pool that the broader Dragon Token Economy depends on.

- **Completed:** Dragon credit system with reserve-confirm purchase flow, ACP cell architecture, prize pool with contributions and payouts, backend-authoritative special-item inventory, Dragon economics and pricing engine, V2 sprite library integration, **v1.0.0 release candidate cut and promoted to pre-prod mainnet UAT**
- **In Progress:** Pre-prod UAT sign-off on v1.0.0, in-game shop refinement using the new sprite library
- **Next:** Production rollout of v1.0.0 once UAT is signed off

## Months 4–9 — Story Mode 🔄 In Progress (Targeting June 2026 Go-Live)

A new single-player progression mode introducing structured content beyond the existing leaderboard challenge. Designed as a long-running content track to drive player engagement and retention.

- **Planning:** 1000-level content roadmap with structured progression and narrative beats
- **Monetisation:** Free-to-play with a 2-item-per-attempt soft cap — accessible to new players, with item purchases via the Dragon credit system for those who want to push further
- **Engine foundation:** The robust gravity engine and new level schema (chains, irregular shapes, variants) provide the technical groundwork
- **Target:** Go-live in **June 2026** with the initial story mode content tranche
- **In flight:** Heavy level redesign work using the V2 sprite library — refreshing the existing level set and shaking down the production pipeline ahead of the Story Mode tranche

## Ongoing — Dragon Token Economy 🔄

The game has pivoted from UTXOSwap (a third-party DEX) to a native Dragon Token credit system. UTXOSwap is no longer actively maintained and its testnet is unsupported, so we built our own in-game swap and credit system. Dragon is now a first-class in-game currency.

- **Completed:** Credit purchase flow (reserve-confirm), ACP cell architecture, prize pool contributions and payouts, backend-authoritative inventory, Dragon economics and pricing engine
- **Planned:** Expanded in-game shop with special item purchases via credits, Dragon token staking rewards, tournament entry fees, player-to-player trading
- **Long-term vision:** Dragon Token as the sole in-game currency powering play, rewards, and marketplace — fully on-chain via Nervos CKB

## Months 10–12 — Fiber Network Integration 🟥 Planned (July 2026 start)

- 1v1 battle mode via CKB Fiber Network (currently "Coming Soon" in battle lobby)
- **Planned start:** July 2026, once the v1.0.0 production rollout and the initial Story Mode tranche are bedded in
