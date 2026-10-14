# Ethics — COOLIFY

**Project:** COOLIFY  
**Category:** INFRA_DEVOPS  
**Upstream:** see BENCH.json  
**Pinned commit:** `23611614874699f98f5a29349b946ea2bbc9b9a1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `655700a8c961214af6d09c5be08e781529e2a5266768f73fbdabb9006e79123b`  
**Date:** October 2026

## Position

COOLIFY is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
