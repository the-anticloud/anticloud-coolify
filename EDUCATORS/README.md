# Educators — COOLIFY

**Project:** COOLIFY  
**Category:** INFRA_DEVOPS  
**Upstream:** see BENCH.json  
**Pinned commit:** `23611614874699f98f5a29349b946ea2bbc9b9a1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `655700a8c961214af6d09c5be08e781529e2a5266768f73fbdabb9006e79123b`  
**Date:** October 2026

## Teaching with COOLIFY

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `655700a8c961214af6d09c5be08e781529e2a5266768f73fbdabb9006e79123b` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
