# Blockchain for FinTech — Self-Sovereign Identity (SSI) (COMP1830)

A recruiter-friendly summary of my **Blockchain for FinTech** coursework.  
Focus: applying **Self-Sovereign Identity (SSI)** to KYC/AML in FinTech; evaluating platforms (Ethereum, Hyperledger Fabric, Corda), consensus (PoS, BFT), and a high-level system design.

## What this shows recruiters
- **Problem framing:** clear motivation, constraints of current identity management (security, cost, redundancy).
- **Architecture thinking:** public / private / hybrid chain trade-offs; SSI with verifiable credentials; PoS and BFT suitability.
- **Critical evaluation:** benefits (privacy, efficiency), risks (scalability, GDPR “right to be forgotten”, adoption).
- **Communication:** concise report with citations and structured conclusions (see `/report`).

## Key takeaways
- **Use case:** Replace fragmented KYC with SSI so users control disclosure while institutions verify proofs.
- **Platform choice:** **Hybrid** (permissioned ledger + public anchoring) to balance privacy, transparency, and scale.
- **Consensus:** **PoS** for efficiency on public layers; **BFT** for permissioned layers requiring finality and throughput.
- **Compliance lens:** Handle GDPR deletion by storing PII off-chain, with only hashes and revocation registries on-chain.

## Contents
- `report/COMP1830_Blockchain_for_FinTech_Report.pdf` — full write-up with references.
- `labs/` — (placeholder) selected lab exercises: smart-contract snippets, wallet/tx steps, or SDK scripts.
- `docs/` — text-only architecture notes, ADRs (Architecture Decision Records).

## Topics (GitHub “About”)
blockchain, fintech, identity, self-sovereign-identity, verifiable-credentials, hyperledger-fabric, ethereum, corda, consensus, privacy, security

## Roadmap
- Add 3 working lab exercises with short READMEs.
- Create 2–3 more ADRs for consensus choice and data minimisation.
- Add a `SECURITY.md` outlining PII handling and revocation.

---
**Author:** Kruthika Mysore Bhaskar  
**License:** MIT
