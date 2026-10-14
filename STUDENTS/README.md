# Students — DATA

**Project:** DATA  
**Category:** CARBON_CAPTURE  
**Upstream:** https://github.com/carbonplan/data  
**Pinned commit:** `70e07d6ebfa04fb78d71a230800a6e17b50baf92`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `d25a6f39eff0a6321f6b94ea9733ac9efff66dd4fb392533546c2cc85e50c205`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `70e07d6ebfa04fb78d71a230800a6e17b50baf92`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `d25a6f39eff0a6321f6b94ea9733ac9efff66dd4fb392533546c2cc85e50c205`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
