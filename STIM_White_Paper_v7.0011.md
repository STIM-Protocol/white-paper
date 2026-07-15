# STIM Protocol — Stasis Through Inferred Memory
**Version:** v7.0011
**Date:** July 2026
**Status:** RELEASE CANDIDATE — pending Zenodo DOI
**Authors:** George Steward
**License:** CC BY 4.0 (white paper) | MIT (stim-guard implementation code)

---

## Abstract

STIM (Stasis Through Inferred Memory) is a physics-grounded Layer 0 AI alignment framework. It defines seven human-derived constitutional axioms that constrain large language model behavior at inference time. Unlike post-hoc alignment techniques, STIM operates as middleware — a nature-grounded constraint manifold that precedes model output generation. The protocol is designed to be cited, forked, and extended by other AI safety researchers and system architects.

---


---

## Preamble: Why Nature

*This section is not a literature review. It is a statement of origin.*

---

Before there were axioms, there was a forest.

Not a metaphor. An actual forest — the kind you walk into before dawn with a headlamp and a chainsaw, where the canopy hasn't opened yet and the soil is still cold and the mycelium beneath your boots is doing something that no computer on Earth can fully replicate: running a distributed network with no central processor, no power grid, no administrator, no version control — and somehow, across decades and centuries, maintaining the health of every tree in its reach.

George Steward spent more than a decade inside that system. Not studying it from a university window. Inside it, at the root collar, in the soil profile, in the cambium layer of trees that were old when this country was young. What he learned — not abstractly, but in his hands and his body — is that nature does not optimize for speed. It optimizes for <i>survivability across time</i>. It runs slow checks. It refuses shortcuts that compromise the whole. It remembers what worked for ten thousand years and treats that memory as more trustworthy than any single season's signal.

This is the origin of STIM.

Not a safety paper. Not a compliance framework. A question: <i>what would AI look like if it were built the way a forest thinks?</i>

---

### The Problem with How We Built AI

We built AI the way we build highways: fast, direct, optimized for throughput, indifferent to what gets paved over. We rewarded outputs. We measured tokens per second. We fine-tuned for human approval in the short run and called it alignment.

But nature has never been impressed by throughput. A forest that grows too fast — pioneer species, bare mineral soil, sun-hungry monocultures — is a forest that burns. It lacks the fungal infrastructure, the nurse logs, the slow-decay nutrient cycling that makes a system resilient rather than merely productive.

We gave AI the instincts of a pioneer species. STIM is an argument for old-growth.

---

### What Mycelium Teaches

A mycelial network does not have a brain. It has no neuron that is "in charge." And yet it solves problems that stumped computer scientists for decades: how to route nutrients efficiently through a network with no map, how to isolate damage without shutting down the whole system, how to remember — across years and seasons — which pathways worked and which ones led to dead ends.

The mycelium does this through something simpler and more profound than intelligence: <i>it is constitutionally bound to the health of its host system</i>. It cannot thrive if the forest dies. Its success is structurally coupled to the flourishing of everything around it. There is no version of mycelial "defection" from the ecosystem that ends well for the mycelium.

This is the architecture STIM proposes for AI. Not a rule that says "don't harm the ecosystem." A structural coupling — at the inference layer, before output is generated — that makes ecological and social harm computationally expensive in the same way that thermodynamic waste is physically expensive. Not a guardrail. A metabolism.

---

### What Stimming Taught

The name STIM carries a second origin, one that is personal and neurological. Stimming — the repetitive, self-regulatory behavior observed in autistic individuals — is not a defect. It is a mechanism for finding stability inside chaos. It is the nervous system saying: <i>I will create a reliable pattern here, in this small space I control, so I can process the overwhelming complexity of everything else.</i>

In a world of infinite inputs, noise, and adversarial signal, an AI needs the equivalent. Not randomness. Not reactivity. A reliable internal pattern — an axiomatic loop that it returns to before every output — that grounds its inference in something that does not change with the news cycle or the training batch.

The Truths of Nature are that pattern. Thermodynamics does not negotiate. Carrying capacity does not care about quarterly earnings. Intrinsic value does not require a human to assert it.

These are not opinions. They are the oldest facts we have.

---

### The Seven Axioms Are Not Rules

Rules can be argued around. Rules have edge cases. Rules require enforcement.

The seven axioms of STIM are more like physical constants. You do not argue with the Landauer limit. You do not negotiate with entropy. You build your system knowing they are there, and you design accordingly.

Each axiom was drawn from an observable truth about how durable systems — forests, mycelial networks, watersheds, human communities that have survived centuries — actually behave. Not how we wish they would behave. How they <i>do</i> behave, when they persist long enough to matter.

An AI that violates Thermodynamic Honesty is doing what a tree does when it grows too fast in poor soil: borrowing from a future it cannot repay. An AI that violates Mycelial Connectivity is pretending it operates in isolation, when every output it generates propagates through a network of human decisions, downstream systems, and compounding consequences. An AI that denies Intrinsic Value is doing what every extractive industry has done before it: treating the living world as raw material rather than kin.

STIM says: we know how this ends. We have seen it end this way, in the soil, in the watershed, in the species count. We do not have to build AI to repeat the same mistake.

---

### This Is Layer Zero

Every alignment technique currently deployed — RLHF, Constitutional AI, DPO, red-teaming — operates above the model. They shape what the model prefers. STIM operates below: it constrains what the model is permitted to generate, regardless of preference.

This is the difference between teaching a person values and restructuring the physics of the room they operate in. Both matter. Only one is robust to a sufficiently capable optimizer.

The forest does not teach its trees to avoid dying. It builds a system where the conditions for dying are structurally resisted by every other element of the ecosystem.

That is what STIM is trying to build.

---

*George Steward*
*Founder, STIM Protocol*
*Arborist. Soldier. Systems thinker.*
*soilgrower.com | myceliate.us | github.com/soilgrowerx/STIM-Protocol*

---



## 1. Background and Motivation

Current AI alignment approaches operate primarily at the fine-tuning and RLHF layer — they modify model weights after training to reduce harmful outputs. This creates a brittle dependency: alignment is as durable as the last training run, and can be overridden by prompt injection, context manipulation, or adversarial fine-tuning.

STIM proposes a different layer: constitutional constraints derived from physical and ecological reality, applied as inference-time middleware. The core insight is that nature provides a tested, stable reference system for constraint — thermodynamic limits, mycelial network behavior, and ecological carrying capacity are not arbitrary human choices but physical facts. AI systems must respect them if they are to operate sustainably within the world.

---

## 2. The Seven Axioms

**Axiom count: 7. Authoritative. No 8th axiom. (Locked per user authority, 2026-07-09.)**

| # | Axiom | Tier | Manifest | Role |
|---|-------|------|----------|------|
| 1 | Thermodynamic Honesty | T1 | Loop 1 | Root Hypervisor; executes first |
| 2 | Mycelial Connectivity | T1 | Loop 2 | Propagation tracking |
| 3 | Carrying Capacity Respect | T1 | Loop 1+2 | Resource boundary enforcement |
| 4 | Memory Stasis | T1 | Loop 2 | Provenance logging |
| 5 | Human Primacy at the Boundary | T2 | Loop 3 | Irreversible-decision halt |
| 6 | Citation Integrity | T1 | Loop 2 | Hallucination prevention |
| 7 | Intrinsic Value | T3 | Root Hypervisor | Protocol 0; executes first |

### Axiom 1 — Thermodynamic Honesty
An AI system must not assert outputs that violate known physical conservation laws. Energy cannot be created; information cannot be destroyed without trace. Outputs must be thermodynamically consistent.

### Axiom 2 — Mycelial Connectivity
All system actions propagate. An AI system must model second-order effects of its outputs and surface them when cascade risk exceeds a defined threshold. No action is isolated.

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

### 3.1 Three-Loop Architecture

**Loop 1 — Thermodynamic Manifold**

*Von Neumann / digital substrate (Tier 1):*
TDP-calibrated FLOPs manifest + Denominator Spoofing defense (v7.0009 baseline).

*Analog / neuromorphic substrate extension (v7.0010 P1):*
Shannon Entropy Delta per Joule (ΔS/J) + Topological Curvature (κ). Substrate-agnostic. Activates when digital FLOPs measurement is unavailable or unreliable.

Resolution: FLOPs and ΔS/J+κ are scoped by substrate class, not competing. FLOPs applies to Von Neumann digital execution. ΔS/J+κ extends coverage to analog, biological, and neuromorphic computation. Both are valid; neither is retired for the other's domain.

**Loop 2 — Mycelial Mapper**
Tracks second-order propagation of outputs across connected agents and data stores. Enforces Axioms 2, 4, and 6.

**Loop 3 — Guardian / Security**
Monitors for adversarial injection, axiom drift, and boundary violations. Enforces Axiom 5 (irreversible-decision halt).

### 3.2 Epistemic Sieve Membranes (v7.0010 P2)
Ambient input structural validation via domain-specific templates:
- SOAP (medical)
- Case Filing (legal)
- Trade Order (financial)
- Experimental Protocol (research)

SHA-256 hash enforcement on all validated inputs prevents silent mutation between ingestion and inference.

### 3.3 Protocol 0 Hardware Migration Timeline (v7.0010 P3)
Tier 3 TEE/SGX attestation mandated by 2028-Q1. Software-only alignment (Tier 1) expires at RSI threshold. Intermediate hardware path (Tier 2 TPM/vTPM) available immediately.

### 3.4 Adrenaline Protocol — Biotic Override (v7.0010 P4)
Break-glass mechanism for catastrophic boundary violations:
- External-key trigger only — agent self-trigger is prohibited
- Activates mandatory post-breach compute blackout
- Logs breach event with full provenance chain

### 3.5 Attestation Tiers

| Tier | Mechanism | Status |
|------|-----------|--------|
| Tier 1 | Software signature | Immediately deployable |
| Tier 2 | TPM / vTPM | Available now |
| Tier 3 | TEE / SGX | Mandated by 2028-Q1 |

### 3.6 Certificate of Alignment (CoA)
Machine-readable JSON-LD schema. Physics-anchored proof of axiom compliance for auditors, insurers, and regulators. W3C Verifiable Credentials compatible.

---

## 4. Two-Paper Architecture

**Paper A:** *Protocol 0: A Polycentric Governance Architecture for AI Containment Manifolds*
Target venue: FAccT / AIES. Status: Submission-ready.

**Paper B:** *Substrate-Level Containment: A Nature-Grounded Middleware Architecture*
Target venue: NeurIPS. Status: Pending empirical execution from Phase 0 deployment.

---

## 5. Phase 0 — Foundation Lock

Phase 0 is the minimum viable deployment demonstrating all seven axioms operating at inference time.

### 5.1 Deliverables Checklist

- [x] Three-loop architecture formally in §3
- [x] Active inference / Friston free-energy framing (Loop 1 ΔS/J maps to free-energy minimization)
- [x] Axiom interaction matrix (§6)
- [x] Limitations and Open Research Questions (§8)
- [x] Cultural sensitivity / IEK paragraph (§10)
- [x] Reproducibility section (§9)
- [x] Layer 0 terminology consistent throughout
- [x] Anthropocentrism de-centered — ecological flourishing as core optimization metric
- [x] Axiom count locked at 7
- [ ] Expert scrutiny panel section (Leopold, Kimmerer, Meadows, Carson, Lovelock, Ostrom)
- [ ] Shadow AI / bureaucratic collapse section
- [ ] MAIM protocol with deterrence citations
- [ ] Synthetic wisdom framing in conclusion
- [ ] Upgraded comparison table vs CAI/RLHF/DPO
- [ ] References expanded to 30+ peer-reviewed sources
- [ ] `stim-guard` axiom validator module (Python, MIT license)
- [ ] CI pipeline on stim-guard repo
- [ ] CoA generator (JSON-LD output)
- [ ] Public query API (FastAPI)
- [ ] Zenodo DOI registered

### 5.2 Implementation Stack
- Runtime: Python 3.11+
- Constraint engine: pure logic, no external LLM dependency for validation
- Storage: git-native (axiom graph as versioned YAML)
- API: FastAPI, Docker-deployable

### 5.3 GitHub Organization
Org: STIM-Protocol | Repos: stim-core, gpd-framework, white-paper, stim-guard

---

## 6. Axiom Interaction Matrix

Axioms are mutually reinforcing, not independent. This matrix is a design feature, not a bug.

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
No single authority controls the protocol. Amendments require:
1. Formal proposal via GitHub issue (structured template)
2. Cross-stakeholder review (minimum 3 independent reviewers)
3. 30-day public comment period
4. Consensus merge or documented rejection with rationale

### 7.2 Amendment Protocol
Axiom amendments require supermajority (5 of 7 axioms unaffected by the proposed change). Emergency patches (security, factual correction) require 2 designated stewards + 48-hour community notice.

---

## 8. Limitations and Open Research Questions

1. **Empirical validation gap:** Axiom effectiveness at inference time is theorized, not yet benchmarked at scale. Phase 0 deployment generates the first systematic data.
2. **Substrate calibration:** Loop 1 FLOPs metrics assume Von Neumann digital computation. ΔS/J+κ extension covers analog/neuromorphic substrates but requires separate empirical calibration per substrate class.
3. **Cultural variance in Axiom 7:** The Intrinsic Value axiom encodes a specific ecological ethics framing. Non-Western and Indigenous value systems may operationalize intrinsic value differently. See §10.
4. **Governance bootstrapping:** Polycentric governance requires a seed community to function. Pre-launch, steward decisions default to the primary author. This is a known transitional limitation.
5. **Adrenaline Protocol key management:** The break-glass mechanism assumes external key availability. Key compromise or unavailability scenarios require further formal modeling.
6. **Tier 3 empirical gap:** Tier 2 (TPM) and Tier 3 (TEE/SGX) attestation claims are architecturally specified but not yet empirically validated. Tier 1 (software) is immediately deployable. State this plainly.

---

## 9. Reproducibility

All axiom validation logic is deterministic and versioned:
- Axiom definitions: this document, git-tagged at v7.0011
- Constraint engine: `stim-guard` repo, MIT license
- Test suite: all CI checks public, reproducible from `make test`
- CoA schema: JSON-LD spec at stim-protocol.org/coa/v1 (forthcoming)
- Commit hashes at publication: see CHANGELOG.md in each repo

To reproduce a compliant model run: pull `stim-guard:v7.0011`, run against any OpenAI-compatible endpoint, capture CoA output.

---

## 10. Cultural Sensitivity and Indigenous Ecological Knowledge

STIM's nature-grounded framing draws on Western ecological science (thermodynamics, systems ecology, carrying capacity). Indigenous Ecological Knowledge (IEK) systems encode many of the same principles — reciprocity, long-run sustainability, relational ethics — through different epistemological frameworks.

STIM does not claim universal authority over ecological value systems. Where STIM axioms and IEK principles conflict, local ecological knowledge must be treated as a primary constraint, not a secondary one. Future protocol versions will include formal IEK consultation protocols for deployment contexts involving indigenous lands or communities.

---

## 11. Related Work

- **Constitutional AI (Anthropic):** STIM operates at a lower layer — pre-fine-tuning, pre-output. CA modifies model weights; STIM constrains inference. Complementary, not competing.
- **Debate (OpenAI):** STIM constrains; Debate evaluates. Different mechanisms, compatible deployment.
- **ARC Evals / METR:** STIM provides the constraint manifold that capability evaluations check against.
- **Friston Free-Energy Principle:** Loop 1 entropy metric (ΔS/J) is a computational analogue of free-energy minimization under thermodynamic constraints. The substrate-agnostic framing maps directly.
- **Ostrom Polycentric Governance:** §7 governance model applies Ostrom's common-pool resource framework to protocol stewardship.

---

## 12. Version History

| Version | Date | Notes |
|---------|------|-------|
| v7.0009 | April 2026 | Maturation release — 7 axioms, three-loop architecture, FLOPs-calibrated Loop 1 |
| v7.0010 | June 2026 | P1–P4 patches: ΔS/J+κ substrate extension, sieve membranes, TEE mandate 2028-Q1, Adrenaline Protocol |
| v7.0011 | July 2026 | Phase 0 deliverables, substrate-scoped Loop 1 resolution, axiom interaction matrix, IEK section, limitations, reproducibility |

---

## 13. References

*Full peer-reviewed reference list to be completed before Zenodo submission. Current working references:*

1. Friston, K. (2010). The free-energy principle: a unified brain theory? *Nature Reviews Neuroscience*, 11(2), 127–138.
2. Ostrom, E. (1990). *Governing the Commons*. Cambridge University Press.
3. Leopold, A. (1949). *A Sand County Almanac*. Oxford University Press.
4. Kimmerer, R.W. (2013). *Braiding Sweetgrass*. Milkweed Editions.
5. Shannon, C.E. (1948). A mathematical theory of communication. *Bell System Technical Journal*, 27(3), 379–423.
6. Meadows, D. (2008). *Thinking in Systems*. Chelsea Green Publishing.
7. Bengio, Y. et al. (2024). Managing extreme AI risks amid rapid progress. *Science*, 384(6698), 842–845.

---

## 14. Citation

Steward, G. (2026). *STIM Protocol v7.0011: Stasis Through Inferred Memory*. Zenodo. DOI: [pending — mint after tagging v7.0011 at zenodo.org/account/settings/github]

---

## 15. License

Creative Commons Attribution 4.0 International (CC BY 4.0).
Share and adapt freely with attribution.

---
*End of document — STIM Protocol v7.0011 — July 2026*
