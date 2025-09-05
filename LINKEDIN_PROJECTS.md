# LinkedIn — Projects (copy/paste)

**Security Research Labs 2025**  
PoC-first writeups for web & smart-contract vulnerabilities with runnable Foundry tests, root-cause analysis, and mitigations. ROE-driven research (labs/testnets only).  
Link: your GitHub repo

**CDCETH — Integer Overflow (lab evidence)**  
Preserved screenshots/evidence and a report scaffold; PoC to be implemented on a **local mainnet fork** only.  
Folder: `labs/cdceth-overflow-01/`

**Chainlink — PermissionlessFeedsConsumer `onReport()` (unauthenticated call)**  
Evidence + report for a previously submitted issue where unauthorized callers could mutate `s_feedReports`. Forge PoC planned against a local fork with mitigation notes.  
Folder: `labs/chainlink-permissionlessfeeds-01/`

**Fireblocks mpc-lib — Critical validation/DoS (reported) + Open batch**  
Sanitizer-backed fuzzing evidence and triage notes (batch 1 — **reported**). Additional artifacts tracked as an **open** investigation (batch 2).  
Folders: `labs/fireblocks-mpc-lib-01/`, `labs/fireblocks-mpc-lib-02/`
