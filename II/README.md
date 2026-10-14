# Independent Insurance — VIRTUAL_TRY_ON

**Project:** VIRTUAL_TRY_ON  
**Category:** CLOTHING_RETAIL  
**Upstream:** see BENCH.json  
**Pinned commit:** `5baa6d14b96022443a8beeda147c5da6013b573c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `81e1d752ddc0647a2bddf12de96b23dc0ed2e45bc08fdbb498d8b3db965b4988`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | VIRTUAL_TRY_ON with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `81e1d752ddc0647a2bddf12de96b23dc0ed2e45bc08fdbb498d8b3db965b4988`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
