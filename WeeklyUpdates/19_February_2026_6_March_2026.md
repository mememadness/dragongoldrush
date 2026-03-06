# Dragon Gold Rush — Weekly Status Report

**Period:** 19 February 2026 — 6 March 2026
**Total Commits:** 215 | **Pull Requests Merged:** 38

---

## Week 1: 19 — 25 February 2026

**Focus:** Audio System, Visual Effects, Game Stability & CI/CD Improvements

### Game Client
- **Background Music & SFX:** Implemented looping background music with mute controls, special item sound effects (4-row/5-row combos), and volume balancing
- **iOS Audio Compatibility:** Resolved multiple iOS Safari audio issues — WebAudio context suspension, speaker playback routing, and Phaser audio lifecycle conflicts
- **Visual Effects:** Redesigned striped item activation effects (lightning strikes with color variety and directional variation)
- **Disclaimer/Terms Gate:** Added mandatory terms acceptance before gameplay with scrollable modal and practice mode on mainnet
- **Mobile Support:** Added landscape orientation prevention with overlay and pause/resume handling
- **Anti-Cheat System:** Fixed score anomalies — reset level bonus between sessions, replaced exponential bonus with linear growth, added challenge identity validation and anomaly monitoring
- **Variable Level Bonus:** Introduced performance-based level bonus with clamped component caps

### Backend
- **Challenge Completion:** Fixed challenge completion reliability with retry/fallback logic and lobby auto-recovery for stuck sessions
- **Session Management:** Fixed resumed game auto-submit, battle session cleanup, and deadlock prevention on level transitions

### CI/CD & DevOps
- **Issue-Driven Workflow:** Implemented GitHub Issue-driven branching and environment progression (DEV → TEST → PROD)
- **Deploy Pipeline Fixes:** Fixed PR deploy flow (production slot deploys, image tag matching, file change detection, permissions)
- **Frontend Rollback:** Added workflow_dispatch-based rollback capability
- **CI Simplification:** Consolidated branch triggers, added concurrency groups to prevent duplicate deploys

---

## Week 2: 26 February — 4 March 2026

**Focus:** Infrastructure Separation, Admin Dashboard Modernisation & Game Content

### Infrastructure & Terraform
- **Terraform State Separation:** Completed multi-phase decoupling of per-environment Terraform state (Phases 0–5)
- **Pipeline Decoupling:** Separated admin and backend build/deploy pipelines into independent workflows
- **CI/CD Secrets Migration:** Migrated all secrets from repository-level to GitHub Environments
- **Self-Hosted Runners:** Migrated all CI/CD workflows from GitHub-hosted to self-hosted runners
- **Deployment Verification:** Built automated post-deploy verification workflow with version SHA comparison across all services

### Admin Dashboard
- **React 19 Modernisation:** Rebuilt admin dashboard from vanilla JS to React 19 + Vite + TypeScript
- **Game Replay Viewer:** Added sprite-based grid visualization for replaying recorded game sessions
- **Analytics:** Added token analytics charts, payment statistics with date filtering, player click-through navigation, and level distribution metrics
- **Operational Tools:** Added wallet ledger session filtering, payout resend for failed transactions, stuck challenges view, and mobile-responsive card layouts
- **Authentication:** Configured Entra ID Easy Auth with post-login redirect and viewer role permissions

### Game Client
- **New Levels:** Added levels 11–30 with themed backgrounds and rebalanced difficulty progression

### Backend
- **Challenge Payouts:** Removed payout cap (5000 ckb), added challenge visibility tracking, and exposure monitoring
- **Leaderboard:** Added active scores leaderboard with potential payout calculations via CoinGecko pricing
- **Prize Pool:** Fixed prize pool display calculations, back-calculation for historical sessions, and reconciliation double-counting
- **Session Lifecycle:** Fixed server-side session completion marking on challenge end

---

## Week 3: 5 — 6 March 2026

**Focus:** Admin Dashboard Refinement & Payout Accuracy

### Admin Dashboard
- **Payout Columns:** Split challenge payout display into separate columns with filtering and session economics
- **Discrepancies Tab:** Built discrepancy detection with session/challenger/exclude filters, exposure totals, and alert notifications
- **Manual Send:** Fixed request body decoding on Azure, added auto-refresh and diagnostic logging
- **UX Polish:** Rounded CKB amounts to integers, centered dialogs, added copy-to-clipboard for notifications

### Backend
- **Payout Accuracy:** Removed 15% winner deduction, corrected prize pool and potential payout calculations, added payout validation tests
- **Payment Documentation:** Updated payment docs for USD-pegged clarity with safety validation rules

---

## Roadmap Progress

### Month 1 — Music & Audio (In Progress)
- **Completed:**  special item SFX, iOS audio compatibility, mute/options controls
- **In Progress:** Background music system, 6 additional original music tracks produced by one half of [Tunnel Club](https://tunnelclub.bandcamp.com/) — currently in testing, targeted for release end of March 2026

### Month 1–2 — Sprite Design & UI Enhancements (In Progress)
- **In Progress:** Sourcing artists for key visual updates — buttons, blocker items, and in-game UI elements
- **Target:** Initial visual updates by end of Month 2

### Post Month 2 — In-Game Rewards
- Dragon Token integration
- In-game shop for special items
- Potential one-off original NFTs

### Future — Fiber Network Integration
- 1v1 battle mode via CKB Fiber Network (currently "Coming Soon" in battle lobby)

---

## Upcoming Tasks (March 2026)

- Release new original music tracks into the game
- Finalise artist engagement for sprite and UI redesign
- Continue admin dashboard operational tooling improvements
- Ongoing game balancing based on player testing feedback
