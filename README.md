# Security Research Labs 2025

**PoC-driven web & smart-contract security labs** (Foundry/AFL++), with clear ROE and mitigation notes.  
Project homepage: https://github.com/MrFrost232/security-research-labs-2025

## What’s inside
- **Labs** with reports + runnable tests/PoCs  
- **ROE** (rules of engagement) for lawful research  
- **Templates** to spin up new labs fast  
- LinkedIn copy blocks (headline/about/skills/projects)

## Labs
- [CDCETH — Integer Overflow](labs/cdceth-overflow-01/report.md)
- [Chainlink — PermissionlessFeedsConsumer `onReport()`](labs/chainlink-permissionlessfeeds-01/report.md)
- [Fireblocks mpc-lib — Batch 1 (reported)](labs/fireblocks-mpc-lib-01/report.md)
- [Fireblocks mpc-lib — Batch 2 (open)](labs/fireblocks-mpc-lib-02/report.md)

> Repros run on **testnets/local forks** only. See [`opsec/ROE.md`](opsec/ROE.md).

## Run tests (EVM labs)
1. Install Foundry → `curl -L https://foundry.paradigm.xyz | bash` then `foundryup`
2. In a lab: `forge build && forge test -vvv`

## Repo map

## Highlights
- CVE credit: libsodium ChaCha20 AEAD decrypt (sanitizer-backed fuzzing)
- Reports submitted: Chainlink (#3273684), Fireblocks (#3272102)

## Skills
Vulnerability Research • Web App Security • Smart Contract Auditing (Solidity/Foundry) • Fuzzing (AFL++/ASan/UBSan) • Cryptography • Reverse Engineering • Python/Bash/Go • AWS • OPSEC • Responsible Disclosure
