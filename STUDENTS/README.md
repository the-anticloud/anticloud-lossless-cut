# Students — LOSSLESS_CUT

**Project:** LOSSLESS_CUT  
**Category:** MOVIES_MEDIA  
**Upstream:** see BENCH.json  
**Pinned commit:** `5154d0fb5901ffbe12bf398d1f46f2f08c1df64e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `87da3c84a10b9e7b7172d0ff4f62a20c7a91aca3b3029d72836f864371ccbbe1`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `5154d0fb5901ffbe12bf398d1f46f2f08c1df64e`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `87da3c84a10b9e7b7172d0ff4f62a20c7a91aca3b3029d72836f864371ccbbe1`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
