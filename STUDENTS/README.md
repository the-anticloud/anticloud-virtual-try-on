# Students — VIRTUAL_TRY_ON

**Project:** VIRTUAL_TRY_ON  
**Category:** CLOTHING_RETAIL  
**Upstream:** see BENCH.json  
**Pinned commit:** `5baa6d14b96022443a8beeda147c5da6013b573c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `81e1d752ddc0647a2bddf12de96b23dc0ed2e45bc08fdbb498d8b3db965b4988`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `5baa6d14b96022443a8beeda147c5da6013b573c`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `81e1d752ddc0647a2bddf12de96b23dc0ed2e45bc08fdbb498d8b3db965b4988`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
