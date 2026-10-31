# fleet-logs

Append-only **machine logs** for the `timerloggedout-spec` fleet.

Created 2026-10-30 (owner order; plan + decisions by the certifications lane, `[MUSEai]@{role:{certifications}}`).

## Scope

**In scope — machine-written, append-only streams:**

- Challenge OSINT page-watch snapshots (pilot mirror — see `osint/challenge/`)
- Telemetry / Provenance / HindSight ledgers — *when they land* (currently built, not on monorepo master)
- Raw certification artifacts (execution receipts, notebooks) — index stays in the monorepo

**Out of scope — stays in [`termux-monorepo`](https://github.com/timerloggedout-spec/termux-monorepo):**

- State (`ops/challenge/coordinator.json`) — state is not a log; gates consume it in place
- Authored knowledge — roadmaps, Role Requirements Plans, ICM knowledge objects, `LEARNINGS`, `SKILL.md` (definitions, not evidence)
- Consumer-bound feeds (e.g. Delphi ledger feeds under `apps/help-wanted-dashboard/data/`) — the live dashboard reads them in place
- Certification *index* — cert ID / date / verification link are logged in the monorepo docs + issue #506 for public verifiability; this repo holds raw artifacts only

## Rules

- Append-only: corrections are new entries, never rewrites of landed entries.
- Public data only: nothing lands here that is not already public in the monorepo. No secrets, no credential material, ever.
- Every mirrored stream carries its source path + source blob sha (see `manifest.json` and per-stream `MIRROR.md`).
- Until a stream's status in `manifest.json` reads `cutover`, the monorepo copy is the source of truth and this copy is a mirror.

## Streams

See [`manifest.json`](manifest.json) — writer, source, consumer, sensitivity, and status per stream.
