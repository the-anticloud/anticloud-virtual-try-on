# Educators — VIRTUAL_TRY_ON

**Project:** VIRTUAL_TRY_ON  
**Category:** CLOTHING_RETAIL  
**Upstream:** see BENCH.json  
**Pinned commit:** `5baa6d14b96022443a8beeda147c5da6013b573c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `81e1d752ddc0647a2bddf12de96b23dc0ed2e45bc08fdbb498d8b3db965b4988`  
**Date:** October 2026

## Teaching with VIRTUAL_TRY_ON

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `81e1d752ddc0647a2bddf12de96b23dc0ed2e45bc08fdbb498d8b3db965b4988` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
