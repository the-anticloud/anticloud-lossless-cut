# Ethics — LOSSLESS_CUT

**Project:** LOSSLESS_CUT  
**Category:** MOVIES_MEDIA  
**Upstream:** see BENCH.json  
**Pinned commit:** `5154d0fb5901ffbe12bf398d1f46f2f08c1df64e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `87da3c84a10b9e7b7172d0ff4f62a20c7a91aca3b3029d72836f864371ccbbe1`  
**Date:** October 2026

## Position

LOSSLESS_CUT is packaged for offline deployment with a verifiable audit trail. The
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
