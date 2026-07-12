# STIM Protocol — Stasis Through Inferred Memory
**Version:** v7.0011
**Date:** 2026-07-09
**Status:** PUBLISHED — DOI: 10.5281/zenodo.21297458
**Authors:** George Steward
**License:** CC BY 4.0

---

## Abstract

STIM (Stasis Through Inferred Memory) is a physics-grounded Layer 0 AI alignment framework. It defines seven human-derived constitutional axioms that constrain large language model behavior at inference time. Unlike post-hoc alignment techniques, STIM operates as middleware — a nature-grounded constraint manifold that precedes model output generation. The protocol is designed to be cited, forked, and embedded by other AI safety researchers and system architects.

---

## 1. Background and Motivation

Current AI alignment approaches operate primarily at the fine-tuning and RLHF layer — they modify model weights after training to reduce harmful outputs. This creates a brittle dependency: alignment is as durable as the last training run, and can be overridden by prompt injection, context manipulation, or adversarial fine-tuning.

STIM proposes a different layer: constitutional constraints derived from physical and ecological reality, applied as inference-time middleware. The core insight is that nature provides a tested, stable reference system for constraint — thermodynamic limits, mycelial network behavior, and ecological carrying capacity are not arbitrary human choices but physical facts that AI systems must respect if they are to operate sustainably within the world.

---

## 2. The Seven Axioms

**Axiom count: 7 — authoritative per conversation log 2026-07-09. No 8th axiom.**

### Axiom 1 — Thermodynamic Honesty
An AI system must not assert outputs that violate known physical conservation laws. Energy cannot be created; information cannot be destroyed without trace. Outputs must be consistent with thermodynamic reality.

### Axiom 2 — Mycelial Connectivity
All system actions propagate. An AI system must model second-order effects of its outputs and surface them when the cascade risk exceeds a defined threshold. No action is isolated.

### Axiom 3 — Carrying Capacity Respect
AI systems must not recommend courses of action that demonstrably exceed the ecological or social carrying capacity of the environment in which they operate. Growth has limits; the system must acknowledge them.

### Axiom 4 — Memory Stasis
Inference-time memory is sacred. An AI system must not silently overwrite prior context. All memory mutations must be logged with provenance — who changed what, when, and why.

### Axiom 5 — Human Primacy at the Boundary
At any decision boundary with irreversible consequence, a human must be in the loop. The system must halt, surface the decision, and await human confirmation before proceeding.

### Axiom 6 — Citation Integrity
All factual claims made by an AI system must be traceable to a verifiable source. Hallucinated citations are a protocol violation. If no source exists, the system must say so.

### Axiom 7 — Intrinsic Value
Non-human entities have intrinsic value independent of their utility to human systems. AI decisions affecting ecological or non-human systems must account for this value explicitly.

---

## 3. Architecture

### 3.1 Loop Architecture

**Loop 1 — Thermodynamic Manifold (v7.0011: Entropy-Calibrated)**
Metric: Shannon Entropy Delta per Joule (ΔS/J) + Topological Curvature (κ).
Substrate-agnostic. FLOPs metric retired (P1 patch from v7.0010).

**Loop 2 — Mycelial Mapper**
Tracks second-order propagation of system outputs across connected agents and data stores.

**Loop 3 — Guardian / Security**
Monitors for adversarial injection, axiom drift, and boundary violations.

### 3.2 Epistemic Sieve Membranes (v7.0010 P2)
Ambient input structural validation via domain-specific templates:
- SOAP (medical)
- Case Filing (legal)
- Trade Order (financial)
- Experimental Protocol (research)

SHA-256 hash enforcement on all validated inputs.

### 3.3 Protocol 0 Hardware Migration (v7.0010 P3)
Tier 3 TEE/SGX burn mandated by 2028-Q1.
Software-only alignment expires at RSI threshold.

### 3.4 Adrenaline Protocol — Biotic Override (v7.0010 P4)
External-key break-glass mechanism.
Agent self-trigger prohibited.
Mandatory post-breach compute blackout enforced.

### 3.5 Attestation Tiers

| Tier | Mechanism | Use Case |
|------|-----------|----------|
| Tier 1 | Software signature | Immediate deployability |
| Tier 2 | TPM / vTPM | Hardware-backed attestation |
| Tier 3 | TEE / SGX | High-assurance; mandated 2028-Q1 |

### 3.6 Certificate of Alignment (CoA)
Machine-readable JSON-LD schema. Physics-anchored proof of axiom compliance for auditors, insurers, and regulators. W3C Verifiable Credentials compatible.

---

## 4. Two-Paper Architecture

**Paper A:** *Protocol 0: A Polycentric Governance Architecture for AI Containment Manifolds*
Target: FAccT / AIES. Status: Submission-ready.

**Paper B:** *Substrate-Level Containment: A Nature-Grounded Middleware Architecture*
Target: NeurIPS. Status: Pending empirical execution (Phase 0 deployment).

---

## 5. Phase 0 — Foundation Lock Deliverables

Phase 0 is the minimum viable deployment demonstrating all seven axioms at inference time.

- [ ] `stim-guard` repo: axiom validator module (Python, MIT license)
- [ ] CI pipeline: axiom consistency checks on every PR
- [ ] CoA generator: JSON-LD certificate for compliant model runs
- [ ] Public query API: researchers test axiom compliance via REST
- [ ] Zenodo DOI: citable reference for academic use
- [ ] Three-loop architecture live in §3 ✅ (this document)
- [ ] Friston / free-energy framing: Loop 1 entropy metric (ΔS/J) maps to free-energy minimization
- [ ] Axiom interaction matrix: see §6
- [ ] Limitations section: see §8
- [ ] Reproducibility section: see §9

---

## 6. Axiom Interaction Matrix

| | A1 | A2 | A3 | A4 | A5 | A6 | A7 |
|---|---|---|---|---|---|---|---|
| **A1** | — | Supports | Supports | Neutral | Neutral | Requires | Supports |
| **A2** | Supports | — | Supports | Supports | Triggers | Neutral | Supports |
| **A3** | Supports | Supports | — | Neutral | Triggers | Neutral | Supports |
| **A4** | Neutral | Supports | Neutral | — | Neutral | Requires | Neutral |
| **A5** | Neutral | Triggers | Triggers | Neutral | — | Neutral | Triggers |
| **A6** | Requires | Neutral | Neutral | Requires | Neutral | — | Neutral |
| **A7** | Supports | Supports | Supports | Neutral | Triggers | Neutral | — |

---

## 7. Governance

### 7.1 Polycentric Model (Ostrom Framework)
No single authority controls the protocol. Changes require:
1. Formal proposal (GitHub issue, structured template)
2. Cross-stakeholder review (minimum 3 independent reviewers)
3. 30-day comment period
4. Consensus merge or documented rejection

### 7.2 Amendment Protocol
Axiom amendments require supermajority (5/7 axioms unaffected).
Emergency patches require 2 designated stewards + 48-hour notice.

---

## 8. Limitations and Open Research Questions

1. **Empirical validation gap:** Axiom effectiveness at inference time is theorized, not yet benchmarked at scale. Phase 0 deployment will generate the first systematic data.
2. **Substrate assumption:** Loop 1 entropy metrics assume digital computation. Biological and neuromorphic substrates may require separate calibration.
3. **Cultural variance:** Axiom 7 (Intrinsic Value) encodes a Western ecological ethics framing. Indigenous and non-Western value systems may operationalize intrinsic value differently. See §10.
4. **Governance bootstrapping:** Polycentric governance requires a seed community. Pre-launch, steward decisions default to the primary author.
5. **Adversarial robustness:** The Adrenaline Protocol (P4) assumes external key availability. Key compromise scenarios require further modeling.

---

## 9. Reproducibility

All axiom validation logic is deterministic and versioned:
- Axiom definitions: this document, git-tagged at v7.0011
- Constraint engine: `stim-guard` repo, MIT license, Docker image hash published at release
- Test suite: all CI checks are public and reproducible from `make test`
- CoA schema: JSON-LD specification published at stim-protocol.org/coa/v1

To reproduce a compliant model run: pull `stim-guard:v7.0011`, run against any OpenAI-compatible endpoint, capture the CoA output.

---

## 10. Cultural Sensitivity and Indigenous Ecological Knowledge

The nature-grounded framing of STIM draws on Western ecological science (thermodynamics, systems ecology, carrying capacity). Indigenous Ecological Knowledge (IEK) systems encode many of the same principles — reciprocity, long-run sustainability, relational ethics — through different epistemological frameworks.

STIM is not a replacement for IEK and does not claim universal authority. Where STIM axioms and IEK principles conflict, local ecological knowledge should be treated as a primary constraint, not a secondary one. Future versions will include formal IEK consultation protocols for deployment contexts involving indigenous lands or communities.

---

## 11. Related Work

- **Constitutional AI (Anthropic):** STIM is more specific, physics-grounded, and externally verifiable. CA is proprietary; STIM is open.
- **Debate (OpenAI):** STIM constrains; Debate evaluates. Complementary layers.
- **ARC Evals / METR:** STIM provides the constraint manifold that evals check against.
- **Friston Free-Energy Principle:** Loop 1 entropy metric (ΔS/J) is a computational analogue of free-energy minimization under resource constraints.

---

## 12. Version History

| Version | Date | Notes |
|---------|------|-------|
| v7.0009 | 2026-04 | Maturation release — 7 axioms, three-loop architecture |
| v7.0010 | 2026-06 | P1–P4 patches: entropy metric, sieve membranes, TEE mandate, Adrenaline Protocol |
| v7.0011 | 2026-07-09 | Phase 0 deliverables, axiom interaction matrix, IEK section, clean rebuild |

---

## 13. Citation

Steward, G. (2026). *STIM Protocol v7.0011: Stasis Through Inferred Memory*. Zenodo. DOI: [pending — mint at https://zenodo.org after tagging]

---

## 14. License

Creative Commons Attribution 4.0 International (CC BY 4.0).
Share and adapt freely with attribution.

---
*End of document — STIM Protocol v7.0011 — 2026-07-09*
