# Mirror record — challenge OSINT (pilot)

Mirrored 2026-10-30 by `[MUSEai]@{role:{certifications}}` (fleet-logs Phase 2 pilot: dual-write proof, before any writer cutover).

| File | Source (termux-monorepo @master) | Source blob sha |
|---|---|---|
| `snapshots.json` | `ops/challenge/osint/snapshots.json` | `136492ab9d6dae73c09543f55ca3802f3618e1a4` |
| `coverage.json` | `ops/challenge/osint/coverage.json` | `49a8aa303ee6609158119adddb242baf4f2b3a7c` |

Copies are byte-exact: the blob sha of each copy in this repo equals its source blob sha (git content addressing — verify with the contents API).

Status: **mirror only.** The monorepo workflow `challenge-osint-watch` still writes to the monorepo; cutover (Phase 3) requires the owning lane's writer change + a fresh mirror refresh, and is a separate decision.
