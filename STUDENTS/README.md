# Students — OPENBEHAVIOR

**Project:** OPENBEHAVIOR  
**Category:** PSYCHOLOGY  
**Upstream:** https://github.com/chen42/openbehavior  
**Pinned commit:** `f2d94cf2dc8312ae9e5fc149849a6ac7abaee278`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `615c913b426c7fcc5b3a4ea530f633fb0491a5828931aec682859620b6ab7dae`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `f2d94cf2dc8312ae9e5fc149849a6ac7abaee278`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `615c913b426c7fcc5b3a4ea530f633fb0491a5828931aec682859620b6ab7dae`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
