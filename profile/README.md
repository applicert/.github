# Applicert

**Privacy-first verification systems built on query-based data access and verifiable credentials.**

---

## What We’re Building

Applicert is focused on a simple idea:

> Verifiers should be able to ask questions of data — and receive verifiable answers — without exposing the underlying information.

This repository contains early work toward that model, centered around **Consent-Based Data Objects (CBDOs)**.

---

## CBDOs (Consent-Based Data Objects)

CBDOs extend verifiable credentials into an interactive system:

- Data remains under user control  
- Verifiers submit constrained queries  
- Responses are minimized (e.g. `true/false`, not raw data)  
- Every interaction is governed by policy, consent, and audit  

This enables:

- Privacy-preserving verification  
- Reduced data exposure and storage liability  
- Stronger alignment with real-world regulatory requirements  

---

## Reference Implementation

The first public reference implementation is now available:

👉 **CBDO Core Engine (v0.1 pre-release)**  
https://github.com/applicert/cbdo-core-engine

Includes:
- Core Engine execution pipeline  
- Query validation and replay protection  
- Consent state machine  
- Response minimization layer  
- Audit logging (hash-chained)  
- AgePass example profile and demo  

---

## Why This Matters

Most current systems require sharing full datasets to prove simple claims.

CBDOs demonstrate an alternative:

- Ask only what you need  
- Reveal only what is necessary  
- Prove the result cryptographically  

---

## Status

This is early-stage work:

- v0.1 is a **reference implementation**, not production-ready  
- Cryptographic proofs are currently stubbed  
- The focus is on validating the interaction model and architecture  

---

## Contributing / Feedback

This work is being shared for **review and discussion**.

If you have experience in:
- Verifiable Credentials (W3C)
- Decentralized Identity (DID)
- Cryptography / ZK systems
- Privacy-preserving architectures

Your feedback is especially valuable.

---

## Attribution

The CBDO model and associated materials are released under CC0 (public domain dedication).

Attribution is not required, but appreciated:

> "Consent-Based Data Objects (CBDOs), William Brian Williams / Applicert, 2026"

---

## License

Code in this organization is licensed under the Apache License 2.0 unless otherwise noted.
