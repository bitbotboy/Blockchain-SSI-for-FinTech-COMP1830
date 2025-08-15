# Architecture Decision Record (ADR-0001)

**Title:** Prefer Hybrid SSI Architecture (Permissioned core + public anchoring)

**Status:** Proposed  
**Context:** Need privacy, compliance, and auditability for KYC/AML.  
**Decision:** Use a permissioned ledger (e.g., Fabric/Corda) for VC issuance/verification logic; anchor state to a public chain for audit proofs.  
**Consequences:** Balances throughput and privacy with verifiability; manage off-chain PII, on-chain hashes and revocation registries.
