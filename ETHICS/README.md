# Ethics — OPENBEHAVIOR

**Project:** OPENBEHAVIOR  
**Category:** PSYCHOLOGY  
**Upstream:** https://github.com/chen42/openbehavior  
**Pinned commit:** `f2d94cf2dc8312ae9e5fc149849a6ac7abaee278`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `615c913b426c7fcc5b3a4ea530f633fb0491a5828931aec682859620b6ab7dae`  
**Date:** October 2026

## Position

OPENBEHAVIOR is packaged for offline deployment with a verifiable audit trail. The
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
