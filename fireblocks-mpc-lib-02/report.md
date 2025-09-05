# Fireblocks mpc-lib — Open Issue Evidence (Batch 2)
Author: Sidney R. Swayzer (“mrfrost23”) • Date: 2025-09-05

## Status
**Open / Pending program response** (evidence preserved; no public details).

## Summary
This folder contains additional artifacts related to suspected critical behavior in Fireblocks `mpc-lib` (e.g., signature validation edge cases or potential DoS conditions). All reproduction must be performed in an **isolated lab build** with sanitizers enabled—no production testing.

## Evidence Pack
Original files preserved in `evidence/`. Quick-view images duplicated in `images/`.

## Reproduction Plan (lab only)
- Build with **ASan/UBSan** enabled.
- Capture minimal reproducer input; record GDB backtrace and relevant call stack.
- Characterize root cause (logic vs. memory), propose fix, and create a **unit test** preventing regression.

## Proof of Concept (to add)
Place a minimal PoC under `test/` or link a C/C++ harness in `poc/`. Show exact build flags and run command used in lab.

## Ethics & Scope
As per `opsec/ROE.md`: **responsible disclosure**, **no production targets**, and documented good-faith research.
