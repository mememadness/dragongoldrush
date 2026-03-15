# Dragon Gold Rush — Roadmap

This roadmap tracks the major development milestones for Dragon Gold Rush. For detailed weekly progress, see the [Weekly Updates](WeeklyUpdates/).

**Last Updated:** 15 March 2026

### Status Legend

| Status | Meaning |
|--------|---------|
| **Completed** | Fully integrated and live |
| **In Progress** | Actively being worked on |
| **Planned** | Scoped and scheduled |
| **Future** | On the radar, not yet scheduled |

---

## Project Timeline

```mermaid
---
config:
    theme: base
    themeVariables:
        doneTaskBkgColor: "#4a8c6f"
        doneTaskBorderColor: "#3a7a5f"
    gantt:
        useWidth: 1200
---
gantt
    title Dragon Gold Rush Development
    dateFormat YYYY-MM
    axisFormat %b %Y
    section Bootstrap
    Completed                         :done, 2025-10, 2026-01

    section Music & Audio — Integration & SFX
    Completed                         :done, 2026-01, 2026-03

    section Sprite Design & UI — Visual Updates
    In Progress                       :active, 2026-02, 2026-04

    section In-Game Rewards — Token & Shop
    Planned                           :2026-04, 2026-06

    section Fiber Network — 1v1 Battle Mode
    Future                            :2026-06, 2026-09
```

---

## Month 1 — Music & Audio ✅ Completed

- 7 original tracks by Mondrin (one half of [Tunnel Club](https://tunnelclub.bandcamp.com/)) integrated with per-theme playback
- Title screen music, crossfade transitions, special item SFX
- iOS audio compatibility, mute/options controls
- All planned music and audio work is fully integrated and live

## Month 1–2 — Sprite Design & UI Enhancements 🔄 In Progress

- **Completed:** Level restructure with new themed zones (sanctum, abyss, throne, summit) and background art
- **In Progress:** Sourcing artists for key visual updates — buttons, blocker items, and in-game UI elements
- **Target:** Initial visual updates by end of Month 2

## Post Month 2 — In-Game Rewards 📋 Planned

- Dragon Token integration
- In-game shop for special items
- Potential one-off original NFTs

## Future — Fiber Network Integration 🔮

- 1v1 battle mode via CKB Fiber Network (currently "Coming Soon" in battle lobby)
