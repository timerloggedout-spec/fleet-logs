# telemetry/ — pending landing

Reserved for the Provenance + HindSight telemetry ledgers (`provenance-ledger.jsonl`, `hindsight-payloads.jsonl`, `ingest-receipt.json`).

State at reservation (2026-10-30): the ingest build exists (2026-10-28) but is **not on termux-monorepo master**. When it lands, its append-only outputs home here per `manifest.json` (stream `telemetry-provenance-hindsight`); the ingest code and its contract doc stay in the monorepo.

Contract reminder (from the build): Provenance and HindSight are separate sinks; payloads carry ids/counts/hashes only, with a secret-shape guard. No raw telemetry with credential material ever lands here.
