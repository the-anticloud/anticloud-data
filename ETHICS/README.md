# Ethics — DATA

**Project:** DATA  
**Category:** CARBON_CAPTURE  
**Upstream:** https://github.com/carbonplan/data  
**Pinned commit:** `70e07d6ebfa04fb78d71a230800a6e17b50baf92`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `d25a6f39eff0a6321f6b94ea9733ac9efff66dd4fb392533546c2cc85e50c205`  
**Date:** October 2026

## Position

DATA is packaged for offline deployment with a verifiable audit trail. The
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
