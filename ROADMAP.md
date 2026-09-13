# Dragon Gold Rush — Roadmap

This roadmap tracks the major development milestones for Dragon Gold Rush. For detailed weekly progress, see the [Weekly Updates](WeeklyUpdates/).

**Last Updated:** 13 September 2026

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
| **Dragon Token Integration** | | | | | | | 🟩 | 🟩 | 🟩 | 🟩 | | |
| **Level Redesign (V2 sprites)** | | | | | | | 🟩 | 🟩 | 🟩 | | | |
| **Story Mode** | | | | | | | 🟩 | 🟩 | 🟩 | 🟩 | 🟩 | 🟩 |
| **New Coin (DGC) & Swap Desk** | | | | | | | | | | 🟧 | 🟧 | 🟧 |
| **Fiber Network** | | | | | | | | | | | | 🟥 |

> 🟩 Completed / Live · 🟧 In Progress · 🟥 Planned · ⬜ Future
>
> Grid covers the project's first year (Oct 2025 → Sep 2026). Story Mode content, the DGC launch, and Fiber Network continue beyond the visible window.

---

## Month 1 — Music & Audio ✅ Completed

- 7 original tracks by Mondrin (one half of [Tunnel Club](https://tunnelclub.bandcamp.com/)) integrated with per-theme playback
- Title screen music, crossfade transitions, special item SFX
- iOS audio compatibility, mute/options controls
- All planned music and audio work is fully integrated and live

## Sprite Design & UI Enhancements ✅ Completed

- **Completed:** Treasure sprites V2, jewel variants, blocker rework, themed zone art (sanctum, abyss, throne, summit), desktop layout overhaul, unified font system, SHOP button and streamlined PLAY flow
- **Outcome:** [ludo.ai](https://ludo.ai) partnership delivered the full sprite library; engagement now closed

## Months 2–4 — Dragon Token Integration ✅ Completed

The integration phase that brought the game's token into gameplay — the credit system, payment infrastructure, and prize pool the wider token economy builds on.

- **Completed:** Dragon credit system with reserve-confirm purchase flow, prize pool with contributions and payouts, backend-authoritative special-item inventory, token economics and pricing engine, V2 sprite library integration
- **Shipped:** v1.0.0 released to production in May; **v1.5.0 released 19 July** with server-verified scoring live in every environment

## Months 4–9 — Story Mode ✅ Live (June 2026 go-live achieved)

The single-player adventure went live on schedule: **200 hand-crafted levels across 14 themed chapters**, each with its own art and music, a scrolling story map with star ratings, and a per-level item picker.

- **Live:** structured progression with solver-derived star targets, chapter themes and music, wallet-saved progress across devices
- **Monetisation as designed:** free-to-play with a 2-item-per-attempt soft cap — accessible to new players, items purchasable via the credit system for those who want the edge
- **Ongoing:** further content tranches on the 1000-level roadmap, plus continuous level tuning driven by an automated play-testing bot
- **New:** a player guide — [How to Play Story Mode](docs/how-to-play-story-mode.md)

## New Coin (DGC) & Swap Desk 🔄 In Progress

The token economy's next chapter: the game is introducing its own new coin, **DGC (Dragon Gold Coin)**, replacing the original DRAGON token (now shown in-game as **DRG**, the legacy coin).

- **Why:** the third-party exchange that priced the old token shut down; the game now runs its own in-game market, making the economy self-contained and fully on-chain via Nervos CKB
- **Built and in final testing:**
  - **In-game pool** — buy DGC directly in the game; a transparent price curve where the price starts low and rises with demand
  - **1:1 swap desk** — holders of the old DRAGON coin swap it one-for-one for DGC, either with one tap in the game or by simply sending coins from any wallet (detected automatically); anything that can't be honoured is refunded automatically
  - **Public burns** — every old coin swapped in is permanently destroyed on-chain, verifiable by anyone
  - The complete journey — swap, automatic payout, burn — has been rehearsed end-to-end on testnet, including fully automated play-through by bot accounts
- **Next:** the official DGC launch — mint, published holders list for the swap, and the desk opening. Dates will be announced when final decisions are locked
- **Guides ready for launch:** [How to Swap Your Old DRAGON](docs/how-to-swap-old-dragon.md)

## Fiber Network Integration 🟥 Planned

- 1v1 battle mode via CKB Fiber Network (currently "Coming Soon" in the battle lobby)
- Scheduled to start after the DGC launch is bedded in
