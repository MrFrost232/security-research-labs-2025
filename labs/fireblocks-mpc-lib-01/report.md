# Fireblocks mpc-lib — Critical Validation/DoS Evidence
Author: Sidney R. Swayzer (“mrfrost23”) • Date: 2025-09-05

## Summary
Fuzzing/triage artifacts related to suspected critical behavior in Fireblocks `mpc-lib` (e.g., signature validation or memory corruption). Reproduction must be done in isolated lab builds with sanitizers.

## Evidence Pack
All files preserved under `evidence/`. Images duplicated in `images/` for quick viewing.

## Reproduction Plan (lab/testnet only)
- Build with ASan/UBSan; capture minimal crashing inputs.
- Provide GDB backtrace and call stack.
- Minimize input and characterize root cause.
- Propose patch or defensive check; provide unit test to prevent regression.

## Proof of Concept (to add)
- Place Forge tests under `test/`.- Include commands to run (e.g., `forge test -vvv --match-test test_exploit`).- Attach minimal logs/assertions that prove impact without touching production systems.

## Ethics & Scope
Performed under **ROE** in `opsec/ROE.md`. No production systems are targeted. Any on-chain interactions must use **local forks/testnets** only.

