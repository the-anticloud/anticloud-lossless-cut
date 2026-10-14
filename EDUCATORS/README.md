# Educators — LOSSLESS_CUT

**Project:** LOSSLESS_CUT  
**Category:** MOVIES_MEDIA  
**Upstream:** see BENCH.json  
**Pinned commit:** `5154d0fb5901ffbe12bf398d1f46f2f08c1df64e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `87da3c84a10b9e7b7172d0ff4f62a20c7a91aca3b3029d72836f864371ccbbe1`  
**Date:** October 2026

## Teaching with LOSSLESS_CUT

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `87da3c84a10b9e7b7172d0ff4f62a20c7a91aca3b3029d72836f864371ccbbe1` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
