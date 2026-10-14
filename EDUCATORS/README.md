# Educators — OPENBEHAVIOR

**Project:** OPENBEHAVIOR  
**Category:** PSYCHOLOGY  
**Upstream:** https://github.com/chen42/openbehavior  
**Pinned commit:** `f2d94cf2dc8312ae9e5fc149849a6ac7abaee278`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `615c913b426c7fcc5b3a4ea530f633fb0491a5828931aec682859620b6ab7dae`  
**Date:** October 2026

## Teaching with OPENBEHAVIOR

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `615c913b426c7fcc5b3a4ea530f633fb0491a5828931aec682859620b6ab7dae` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
