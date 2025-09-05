# Bug Bounty & Program Engagements
_Last updated: 2025-09-05_

This file lists sanctioned, policy-compliant engagements and outcomes. Keep details non-sensitive and link only to **public** write-ups or officially disclosed reports.

## Summary (copy for resumes/LinkedIn)
- Active on **HackerOne** and **Immunefi** with a report-first workflow (runnable PoCs, root cause, and mitigation).  
- Programs engaged include: Chainlink, Fireblocks, MetaMask, Crypto.com, Shopify, 1Password, Grammarly, LayerZero, Celer cBridge, Ref Finance (NEAR).  
- **CVE credit:** CVE-2025-54600 (libsodium ChaCha20 AEAD decrypt) — sanitizer-backed fuzzing and mitigation notes.  
- Findings documented in this repo as labs (lab folders under `/labs`), using testnets/local forks for blockchain targets.

---

## Selected Programs & Outcomes

| Date       | Program        | Asset/Scope (public)                     | Type                  | Outcome/Status        | Public Link |
|------------|----------------|------------------------------------------|-----------------------|-----------------------|-------------|
| 2025-07-29 | **Chainlink**  | PermissionlessFeedsConsumer.sol          | Smart Contracts (EVM) | **Reported** (#3273684)| (add link if public) |
| 2025-07-26 | **Fireblocks** | mpc-lib / crypto validation paths        | Crypto Library / Fuzz | **Reported** (#3272102)| (add link if public) |
| 2025-20-XX | **libsodium**  | ChaCha20 AEAD decrypt                    | Crypto Library        | **CVE credit: CVE-2025-54600** | (write-up link) |
| 2025-07-27 | **MetaMask**   | Wallet/SDK/Snaps (policy scope)          | Web/Wallet/App        | Engaged (in-scope)    | — |
| 2025-07-29 | **Crypto.com** | CDCETH smart contract + exchange URL     | Smart Contracts/Web   | Engaged (testnets/forks)| — |
| 2025-07-29 | **Shopify**    | GraphQL endpoints (policy scope)         | Web (GraphQL)         | Engaged               | — |
| 2025-07-27 | **1Password**  | Events API / Extensions (self-owned only)| Web/API               | Engaged               | — |
| 2025-07-27 | **Grammarly**  | Web/app ecosystem (policy scope)         | Web                   | Engaged               | — |
| 2025-07-30 | **LayerZero**  | EndpointV2/ULN (testnets/local forks)    | Smart Contracts       | Research in lab       | — |
| 2025-07-30 | **Celer cBridge** | Bridge contracts (policy scope)      | Smart Contracts       | Research in lab       | — |
| 2025-07-30 | **Ref Finance**| NEAR Rust contracts (boosted farming)    | Smart Contracts (NEAR)| Research in lab       | — |

> **Note:** Keep this table accurate and sanitized. Only add links once disclosures are public. Use testnets/local forks for any on-chain PoCs.

---

## Methodology (short)
1. **Scope & ROE first:** confirm in-scope assets and rules; create a local fork/testnet when applicable.  
2. **Recon & Modeling:** map auth flows, state machines, invariants.  
3. **Exploration:** manual probing + fuzzing/invariants tests (Foundry/AFL++/sanitizers).  
4. **PoC-first report:** executable tests, clear assertions, root cause, and mitigation.  
5. **Disclosure:** submit via program, coordinate fixes, publish sanitized write-up (if/when allowed).


---

## Evidence Folders Added
- `labs/cdceth-overflow-01` — evidence imported on 2025-09-05
- `labs/chainlink-permissionlessfeeds-01` — evidence imported on 2025-09-05
- `labs/fireblocks-mpc-lib-01` — evidence imported on 2025-09-05

- `labs/fireblocks-mpc-lib-02` — additional Fireblocks evidence imported on 2025-09-05; status: **Open**
