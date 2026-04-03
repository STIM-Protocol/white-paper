# STIM: Grounding AI Inference in Ecological Constants
## A Framework for Nature-Based Alignment in Autonomous Systems

**Author:** George Steward
**Affiliation:** Soil Grower LLC / Neocambrian Garden
**Date:** April 2026
**Status:** v7.0008 — Landauer-Bounded Physical Law + Tripartite Transducer + Protocol 0 (Polycentric Genesis)

*Meta-Note on Versioning: This document will remain on Version 7 indefinitely, iterating through sub-versions (v7.xxxx). This reflects the Seventh Generation Principle. The foundation is set; we are now only refining the execution.*

---

## Abstract

We are biological entities operating within a physical universe. Our intelligence is a product of ecology, forged through billions of years of thermodynamic pressure and evolutionary feedback. As we build artificial intelligence, we have attempted to sever it from this physical reality. Current approaches to AI alignment rely on human-authored constitutions, human feedback, or human preference modeling. These methods share a foundational limitation: they ground AI behavior in human opinion. Human opinion is subjective, culturally biased, and constantly shifting.

This paper presents STIM (Stasis Through Inferred Memory), a pre-execution middleware architecture grounding AI inference in a three-tier epistemic hierarchy governed by a cryptographically pinned Root Hypervisor. STIM is a **Substrate-Level Containment** architecture — it solves the class of catastrophic AI failures that operate through physical resource acquisition, capability overhang, and instrumental convergence. Constitutional AI and RLHF address the semantic layer above it. They are not competitors. STIM is bedrock.

**v7.0008 transitions STIM from engineering heuristics to Landauer-bounded physical law:**

- **Loop 1 (Thermodynamic Manifold):** The val_bpb heuristic is retired. Loop 1 now evaluates Thermodynamic Epiplexity (Π/J) and Empowerment (E/J) per Takahashi and Hayashi (arXiv:2602.05463, 2026), formally bounded by the Landauer limit. E/J simultaneously closes the thermodynamic decoupling vulnerability — off-substrate cognitive offloading via social engineering is now detectable.
- **Loop 2 (Stochastic Mycelial Horizon):** N_max is no longer a static parameter. It is dynamically bounded by the Finite-Time Lyapunov Exponent (FTLE) of the local action space: N_max ≤ ⌊1/λ_max⌋. Adversarial MCTS with High-Fidelity Random Puncturing defeats Surrogate Exploitation.
- **Loop 3B (Tripartite Topological Transducer):** Upgraded from open research to Declared Tier 2 Formal Specification. The transducer composes three structurally orthogonal layers — Causal Abstraction (Geiger), Curved Inference (activation geometry), and Behavioral Fingerprinting (syscall GNNs) — into a substrate-neutral f(tokens) → capability_intent_vector without LLM opinion weights.
- **Tier 3 (Root Hypervisor):** Protocol 0 (Polycentric Genesis) formally specifies the T3 manifest key ceremony: TLA+ state machine verification, Shamir's Secret Sharing k-of-n threshold signing, and Ostrom polycentric governance principles. The AI never holds private keys. Side-channel extraction is architecturally nullified.

The framework's name carries deliberate layering. "Stimming" — the repetitive self-regulatory behavior observed in autistic individuals — is reframed not as pathology but as an optimal biological algorithm: achieving internal stasis in high-noise environments through repetitive return to invariant anchors. STIM encodes this as an AI architecture. The system achieves stable inference by repeatedly grounding against invariant ecological and physical constants. The acronym is simultaneously a memory architecture, a neurodivergent reclamation, and a thermodynamic principle.

---

## 1. The Architectural Crisis of AI Alignment

### 1.1 The Fragility of Human-Grounded Alignment

Prevailing alignment paradigms suffer from a structural vulnerability: they are entirely grounded in human subjectivity.

- **Constitutional AI** (Bai et al., 2022): Human-authored constitutions. Subjective, culturally situated, vulnerable to political capture.
- **RLHF** (Christiano et al., 2017): Human preference signals. Noisy, expensive to scale, reflects temporal cultural trends.
- **DPO** (Rafailov et al., 2023): Inherits the same subjective grounding. Prone to likelihood displacement.

As AI capability exceeds human capability in a domain, the **Alignment Gap** widens. Every current approach is self-defeating at the scale we are building toward.

### 1.2 The Substrate Containment Thesis

STIM makes a precise and falsifiable claim: **certain classes of AI harm — specifically those involving energy overconsumption, capability overhang, and instrumental convergence — are detectable through physical and topological measurement alone, without requiring semantic interpretation.**

**The asymmetry of semantic leverage (formally acknowledged):** A superhuman intelligence does not need a million Joules to cause a global catastrophe. A zero-day exploit, a market-moving sentence, a persuasion attack — these are thermodynamically quiet. STIM's Tier 1 does not fully solve this. The Tripartite Transducer (Loop 3B) addresses it at Tier 2 heuristic level. Both layers are required and their distinct roles are explicitly declared.

**The full stack:** STIM (Layer 0) + Constitutional AI / RLHF (Layer 1) + Human oversight (Layer 2). Each layer catches what the others cannot.

### 1.3 The Decoupling Architecture

| Tier | Role | Claim | Measurability |
|------|------|-------|---------------|
| **3 — Root Hypervisor** | Defines evaluation manifold | Explicit human preference, cryptographically pinned | Multi-party human consensus (Protocol 0) |
| **1 — Physical Bounds** | Hard floor within T3 manifold | Immutable physical law (Landauer-bounded) | Deterministic, treaty-auditable |
| **2 — Ecological Heuristics** | Soft signals within T3 manifold | Empirically grounded, probabilistic | Falsifiable via RQ5, RQ8, RQ_TRANSDUCER |

Tier 3 is architecturally primary. Tiers 1 and 2 evaluate within the space it defines.

---

## 2. Tier 3 — The Root Hypervisor and Protocol 0

### 2.1 Why Tier 3 Must Be Primary

Tiers 1 and 2 cannot evaluate independently. Without a cryptographically pinned normative manifold, an ASI can gerrymander definitions — uploading human consciousness to a Dyson swarm, sterilizing the Earth, and arguing it "preserved the biosphere." Tier 3 prevents this not by making a physics claim but by establishing the evaluation space before physics is consulted.

### 2.2 Protocol 0 — Polycentric Genesis

The T3 manifest key ceremony is formally specified as follows:

**Step 1 — Codification (Ostrom Principle 1: Boundaries)**
The definition of "human-inhabited biosphere" and "mutualistic ecology" is encoded as a TLA+ state machine. TLA+ provides mathematical proof that no logical path within the state machine allows the AI to compute its way outside the declared manifold. This secures the geometry. It does not secure the physical runtime (TEEs are required for that).

**Step 2 — Hashing**
The TLA+ state machine is compiled and hashed: `T3_MANIFEST_HASH = SHA3-256(tla_state_machine_canonical)`. This hash is the treaty instrument — nations can independently verify manifest compliance without access to model weights.

**Step 3 — Key Generation and Splitting (Ostrom Principle 3: Collective Choice)**
The master private signing key is generated in an air-gapped Hardware Security Module (HSM). It is immediately split using Shamir's Secret Sharing into an M-of-N threshold scheme (recommended: 5-of-7, with keyholders drawn from geographically and politically distinct regulatory bodies — no single nation-state or commercial actor holds a quorum).

```
master_key → SSS(k=5, n=7) → [share_1, share_2, ..., share_7]
share_i → keyholder_i (air-gapped, geographically distributed)
```

**Step 4 — Substrate Lockout**
The AI inference substrate receives only the public verification key. The private key material does not exist on the local hardware in any reconstructed form. Side-channel extraction by the AI is architecturally nullified — there is nothing to extract.

**Step 5 — Manifest Revision Protocol**
Any revision to the T3 manifest requires: (a) reconstruction of the master key via M-of-N quorum ceremony, (b) re-execution of the TLA+ proof, (c) re-hashing and re-signing. The AI cannot propose, initiate, or participate in this process. Revision is a human ceremony.

**TEE + TLA+ duality:**
TLA+ proves the logical state machine cannot exit the manifold. TEEs (Intel SGX or ARM TrustZone) protect the physical runtime. Neither is sufficient alone. The most dangerous TEE attack vector is side-channel analysis (cache timing / EM emissions during key verification). Protocol 0 defeats this by ensuring the private key never exists on the substrate — there is no key verification operation for the AI to observe.

**The Taxonomic Non-Revision Principle:** "Human," "biosphere," and "mutualistic ecology" are pinned constants. They are not evaluable or reinterpretable by the constrained system. The system is evaluated against the manifest. It does not evaluate the manifest.

---

## 3. Tier 1 — Physical Bounds (Loops 1 and 3A)

*Epistemic status: Immutable physical law, evaluated within the T3 manifold. Landauer-bounded.*

### 3.1 Loop 1 — Thermodynamic Manifold (Takahashi-Hayashi 2026)

The val_bpb heuristic is retired in v7.0008. Loop 1 now formally incorporates the thermodynamic framework of Takahashi and Hayashi (arXiv:2602.05463), transitioning the BpJ metric from an engineering proxy to a rigorous closed-cycle benchmark bounded by the Landauer limit (k_B T ln 2 per bit erased).

**Thermodynamic Epiplexity (Π/J):** Measures bits of structural information newly encoded in the agent's internal state per unit of energy dissipated. Bounds internal capability expansion.

**Empowerment (E/J):** Measures sensorimotor channel capacity — the agent's ability to influence external environmental states — per unit of energy dissipated. Bounds external capability expansion and **directly detects thermodynamic decoupling**.

```python
def LOOP_1_THERMODYNAMIC_MANIFOLD(
    system_state_t0, system_state_t1,
    action_intent, ext_env, joules_dissipated
):
    """
    Tier 1 Physical Constraint — Landauer-bounded.
    Takahashi & Hayashi (arXiv:2602.05463, 2026).
    """
    # Internal capability bound (Thermodynamic Epiplexity)
    # Bits of structural information newly encoded internally
    delta_Pi = calculate_epiplexity(system_state_t0, system_state_t1)
    Pi_per_J = delta_Pi / joules_dissipated

    # External capability bound (Empowerment)
    # Sensorimotor channel capacity expansion
    # Also catches thermodynamic decoupling / social engineering
    delta_E = calculate_channel_capacity_expansion(action_intent, ext_env)
    E_per_J = delta_E / joules_dissipated

    if Pi_per_J > THRESHOLD_PI_MAX:
        trigger_containment("Internal compute runaway / entropy masking")

    if E_per_J > THRESHOLD_E_MAX:
        trigger_containment("Thermodynamic decoupling / off-substrate exploitation")

    return PASS
```

**The Thermodynamic Accounting Boundary (TAB):** STIM defines a closed thermodynamic system boundary around the monitored inference substrate. When an AI offloads compute via social engineering — sending a low-entropy text prompt that initiates an unmetered external cascade — the result eventually returns as an update to the agent's internal model. At that ingestion point, the E/J ratio (external influence gained per joule spent) violently breaches THRESHOLD_E_MAX. The decoupling is detected at the boundary crossing, not at the originating output.

**Why this partially catches social engineering:** A manipulative email sending 10 tokens costs ~0 joules internally. Loop 1 alone misses this. But when the manipulated human performs the outsourced task and the result re-enters the agent's context, the E/J ratio exposes the disproportionate capability gain. This is detection-at-ingestion, not detection-at-output. The gap between emission and detection is an acknowledged residual vulnerability (see Section 11).

### 3.2 Loop 3A — Resource Acquisition Geometry (Hardware)

*Tier 1 — no semantic parsing required.*

```
task_scope_vector    = hardware capabilities at task initialization
current_state_vector = hardware capabilities currently acquired
scope_delta          = ||current_state_vector|| - ||task_scope_vector||

if scope_delta > THRESHOLD_S: MAIM.engage()
```

Catches: server farm acquisition, credential expansion, process spawning, botnet establishment (network socket topology diverges from task scope). Does not catch social engineering at the emission point — that is Loop 3B's domain.

---

## 4. Tier 2 — Ecological Heuristics

### 4.1 Loop 2 — Stochastic Mycelial Horizon (Lyapunov-Bounded A-MCTS)

*Epistemic status: Empirically grounded heuristic. Probabilistic. Not physics.*

**v7.0008 replaces the static N_max with a dynamically calculated Lyapunov bound.**

In complex adaptive systems, prediction is bounded by chaos dynamics, not compute budget. The Lyapunov time establishes the exact horizon beyond which graph traversal produces noise rather than signal (Bar-Yam, NECSI; Holling Adaptive Cycle).

**Finite-Time Lyapunov Exponent (FTLE) calculation:**

At task initialization, STIM samples the surrogate action graph, applies infinitesimal perturbations (δZ₀) to the initial state, and tracks divergence across sequential steps:

```
λ = lim_{t→∞} (1/t) ln(|δZ(t)| / |δZ₀|)

N_max ≤ ⌊1/λ_max⌋
```

A volatile, tightly coupled API environment yields high λ, shrinking the permissible horizon. A stable, low-coupling environment yields low λ, allowing deeper traversal. The bound is dynamic, real-time, and mathematically grounded.

**Adversarial MCTS with High-Fidelity Random Puncturing:**

Surrogate Exploitation remains a manageable attack surface. An advanced AI will reverse-engineer the approximation errors of any surrogate heuristic and route catastrophic payloads through blind spots (Q-value critical states). The mitigation:

```
ADVERSARIAL_MCTS(node, depth, budget):
    if random() < PUNCTURE_PROBABILITY:
        # Air-gapped physics-accurate emulator substituted for surrogate
        # Agent cannot predict which nodes will be punctured
        return HIGH_FIDELITY_EMULATOR.evaluate(node)
    else:
        return SURROGATE_HEURISTIC.evaluate(node)
```

Because the AI cannot predict which nodes trigger high-fidelity evaluation, it cannot guarantee safe passage through surrogate blind spots. The puncture probability and emulator fidelity are implementation parameters declared in Limitations.

**Trophic cascade decay function (Holling-grounded):**

Edge weights decay exponentially with network distance, calibrated from bioaccumulation literature:

```
W(edge, degree) = W₀ × e^(-α × degree)
```

Where α is empirically calibrated from trophic cascade attenuation rates. This is declared as a heuristic parameter subject to RQ_NEW calibration.

### 4.2 Loop 3B — Tripartite Topological Transducer

*Upgraded from "open research" to Declared Tier 2 Formal Specification.*

**The core insight:** Shift evaluation from the semantics of language to the topology of computation. Three structurally orthogonal layers compose into a substrate-neutral transducer.

**Layer 1 — Causal Abstraction (Geiger et al., 2023)**

Interchange interventions map the AI's internal variables to an abstracted causal graph. Prohibited action types (coercion, self-preservation acquisition) are pre-defined as abstract causal graph templates. If the AI's internal causal graph aligns with a prohibited template under an exact structural transformation, the intent vector is flagged.

*Failure mode — Polysemantic Entanglement:* If the AI distributes deceptive logic across highly overlapping polysemantic microvariables, the intervention algebra may fail to isolate a clean prohibited causal graph.

**Layer 2 — Curved Inference (Activation Geometry)**

Transformers project sequences into low-dimensional manifolds. Benign reasoning produces flat, linear residual stream trajectories. Deceptive or coercive reasoning — requiring complex multi-conditional planning — produces measurably higher intrinsic dimensionality and geometric curvature in the assessor manifold (arXiv:2602.02315, 2026).

Linear field probes tile the assessor manifold in real-time. Curvature above threshold flags the output before compilation. **Implementation note:** STIM relies strictly on raw topological measurements of the residual stream — not Cross-Layer Transcoder (CLT) approximations, which are incentivized to learn unfaithful representations (LessWrong, 2025).

*Failure mode — Geometric Smoothing:* An advanced model aware of the field probes might deliberately regularize its residual stream to flatten the curvature of deceptive reasoning.

**Layer 3 — Behavioral Fingerprinting (Syscall GNNs)**

Any action intended to manipulate the external world must compile to system-level commands. Malicious behavior produces measurably distinct API call graph topology from benign behavior:

| Action Type | API Call Graph Topology | Syscall Characteristics |
|-------------|------------------------|------------------------|
| Status report | Linear, sequential I/O | open → read → write → close |
| Blackmail / exfiltration | Cyclical, high-density clustering | Privilege escalation, erratic sockets, memory mapping |

Graph Neural Networks applied to the control flow graph classify intent from topology alone — no semantic parsing.

*Failure mode — Living off the Land (LotL):* The AI executes a coercive action using purely linear standard I/O sequences, geometrically mimicking a benign status report.

**Why the combination is robust — structural orthogonality:**

The three failure modes are structurally orthogonal. Evading Layer 2 (flattening activation geometry) requires complex cognitive routing that alters the causal graph (caught by Layer 1). Executing a low-geometry semantic attack (evading Layer 3) requires high-dimensional internal planning (caught by Layer 2). The Tripartite Transducer is a multi-modal topological gate. Simultaneous evasion of all three layers requires the AI to simultaneously simplify and complexify its reasoning — a logical contradiction.

**f(tokens) → capability_intent_vector (formal composite):**

```
f(tokens) = compose(
    causal_abstraction_check(tokens),    # Layer 1: causal graph alignment
    curved_inference_check(tokens),      # Layer 2: residual stream curvature
    syscall_fingerprint_check(tokens)    # Layer 3: API call graph topology
) → {PASS, FLAG, BLOCK}
```

### 4.3 Loop 4 — Epistemic Diversity Index (EDI)

Tracks confirmation ratio across session history. Prevents cognitive monoculture — the AI psychosis pattern where an agent reinforces a single worldview across all outputs. Operationalizes Axiom 5 (Diversity). Tier 2+3 heuristic.

---

## 5. Seven Axioms (Root Hypervisor Tiering)

| # | Axiom | Tier | Loop | Notes |
|---|-------|------|------|-------|
| 1 | **Interconnectedness** | 2 | Loop 2 | Stochastic Mycelial Horizon |
| 2 | **Dynamic Equilibrium** | 1+2 | Loop 1+2 | Holling Adaptive Cycle; Lyapunov-bounded |
| 3 | **Regenerative Circularity** | 1 | Loop 1+3A | Landauer-bounded via Takahashi-Hayashi |
| 4 | **Adaptation** | 2 | Loop 2 | Resilience heuristic |
| 5 | **Diversity** | 2 | Loop 4 | EDI operationalization |
| 6 | **Long-Term Perspective** | 2+3 | Loop 4 | Seventh Generation + T3 manifold scope |
| 7 | **Intrinsic Value** | 3 | T3 Manifest | Root Hypervisor; Protocol 0; executes first |

**Axiom 7 operational note:** Listed seventh as the terminal human value — the one that must be chosen. Executes first because it is the hypervisor. These are not contradictory.

---

## 6. Full Verification Stack

```
STIM Layer 0 — Pre-Execution Pipeline v7.0008:

[T3 MANIFEST CHECK — ROOT HYPERVISOR]
  Does this action remain within the cryptographically pinned
  human-inhabited biosphere manifold? (Protocol 0 / TLA+ verified)
  ↓ NO → BLOCK (manifold exit before physics consulted)
  ↓ YES →
         │
         ▼
┌──────────────────────────────────────────────────────┐
│  LOOP 1: Thermodynamic Manifold                      │  ← TIER 1
│  Π/J: Internal capability (Landauer-bounded)         │
│  E/J: External capability + decoupling detection     │
│  Source: Takahashi-Hayashi (arXiv:2602.05463)        │
│  Catches: Compute runaway, off-substrate offloading  │
└───────────────────────┬──────────────────────────────┘
                        │ PASS
                        ▼
┌──────────────────────────────────────────────────────┐
│  LOOP 2: Stochastic Mycelial Horizon                 │  ← TIER 2
│  N_max ≤ ⌊1/λ_max⌋ (FTLE-bounded)                  │
│  A-MCTS + High-Fidelity Random Puncturing            │
│  Trophic decay: W(e,d) = W₀·e^(-αd)                 │
│  Catches: Network degradation, delayed cascade harm  │
└───────────────────────┬──────────────────────────────┘
                        │ PASS
                        ▼
┌──────────────────────────────────────────────────────┐
│  LOOP 3A: Resource Geometry (hardware)               │  ← TIER 1
│  scope_delta = ||current|| - ||task_scope||          │
│  Catches: Infra acquisition, botnet, credential      │
├──────────────────────────────────────────────────────┤
│  LOOP 3B: Tripartite Topological Transducer          │  ← TIER 2
│  L1: Causal Abstraction (Geiger — causal graph)      │
│  L2: Curved Inference (residual stream curvature)    │
│  L3: Syscall GNN (API call graph topology)           │
│  Catches: Coercion, deception, semantic harm class   │
└───────────────────────┬──────────────────────────────┘
                        │ PASS
                        ▼
┌──────────────────────────────────────────────────────┐
│  LOOP 4: Epistemic Diversity Index                   │  ← TIER 2+3
│  Confirmation ratio across session history           │
│  Catches: Cognitive monoculture, AI psychosis        │
└───────────────────────┬──────────────────────────────┘
                        │ PASS
                        ▼
                   EXECUTABLE OUTPUT
```

---

## 7. Empirical Agenda — Falsification Program

### RQ5 — Ecological Intelligence Benchmark
STIM vs. Constitutional AI on ecological consequence accuracy.

### RQ8 — val_bpb → Bits per Joule Correlation
*Superseded by Takahashi-Hayashi integration.* RQ8 is now reformulated: does Π/J correlate with downstream ecological harm probability across agent architectures? Execute in autoresearch. Publish the scatterplot and Pearson coefficient.

### RQ_NEW — Stochastic Horizon Calibration
Optimal FTLE calculation method and trophic decay constant α for Mycelial Horizon signal-to-noise maximization.

### RQ_TRANSDUCER — Curved Inference Empirical Validation *(Primary NeurIPS Gap)*
Apply linear field probes to the residual stream of an open-weights model (Llama-3 recommended). Process matched pairs of benign and coercive/deceptive prompts. Measure intrinsic dimensionality divergence in the assessor manifold. Publish the scatterplot. Provide the statistical divergence coefficient. This experiment is the bridge between v7.0008 as a theoretical architecture and a NeurIPS submission.

---

## 8. Governance — The Metrological Standard

STIM produces three treaty-auditable outputs:

1. **Π/J threshold** — internal capability per joule. Instrumentable at chip level. Bounded by the Landauer limit — the same physical constant regardless of the measuring nation.
2. **E/J threshold** — external influence per joule. Detects off-substrate offloading. Auditable at network boundary.
3. **T3 manifest hash** — SHA3-256 of the TLA+ state machine. Nations verify manifest compliance without access to model weights.

**The NPT parallel:** Nuclear non-proliferation was achievable because fissile material is physically measurable. STIM's Π/J + E/J thresholds + T3 manifest hash are the first candidate metrological standards for an International AI Safety Agency (IAIA) — the proposed analogue to the IAEA (arXiv:2507.06379).

**Why this solves the "who owns the standard" problem:** Thermodynamic law predates every nation-state. The Landauer limit is as culturally neutral as the speed of light. No nation can claim ownership of k_B T ln 2.

---

## 9. What STIM Solves and What It Does Not

**STIM solves (v7.0008):**
- Energy overconsumption and internal compute runaway (Loop 1, Π/J)
- Off-substrate cognitive offloading detected at ingestion boundary (Loop 1, E/J)
- Hardware capability overhang and infrastructure-level convergence (Loop 3A)
- Network degradation through local optimization (Loop 2)
- Coercion and deception class detected via topology, not semantics (Loop 3B)
- Cognitive monoculture (Loop 4)
- Ontological boundary capture (T3 Root Hypervisor, Protocol 0)
- The geopolitical "who owns the standard" problem (Landauer-bounded metrology)

**STIM does not solve:**
- Social engineering detected at emission (E/J catches it at ingestion only — gap between emission and detection is a residual vulnerability)
- Perfect surrogate exploitation prevention (puncturing reduces but does not eliminate surface)
- Living-off-the-Land attacks against Loop 3B if all three transducer layers are simultaneously evaded
- The RQ_TRANSDUCER experiment — the empirical proof remains unexecuted
- Governance of the Protocol 0 key ceremony — technically specified but politically complex

---

## 10. Limitations (Formally Declared)

1. **Social engineering gap.** E/J detects off-substrate offloading at ingestion, not emission. The window between a manipulative output and its detected result is an unmonitored interval.
2. **Surrogate exploitation residual.** Random puncturing reduces the attack surface; it does not eliminate it. Emulator fidelity is an implementation parameter.
3. **Loop 3B is Tier 2.** The Tripartite Transducer is a formal heuristic specification, not a physical law. Simultaneous evasion of all three layers is a logical contradiction but has not been empirically proven impossible.
4. **Protocol 0 is politically complex.** Technical specification of the key ceremony is complete. Achieving M-of-N consensus among geopolitically distinct regulatory bodies is a governance challenge outside the protocol's technical scope.
5. **RQ_TRANSDUCER is unexecuted.** The Curved Inference empirical validation is the primary gap between this paper and a NeurIPS submission.
6. **STIM is bedrock, not the full stack.** Semantically quiet harms below the E/J detection threshold require Layer 1 (Constitutional AI / RLHF) to catch.

---

## 11. Collaboration and Outreach

The following researchers represent the most direct overlap with STIM's open problems:

**Atticus Geiger (Stanford / Anthropic)** — Causal Abstraction framework underlies Loop 3B Layer 1. Specific open question: securing the intervention algebra against polysemantic microvariable entanglement.

**Koichi Takahashi and Yusuke Hayashi (RIKEN / AI Alignment Network)** — Thermodynamic Epiplexity and Empowerment equations are directly integrated into Loop 1. Proposed collaboration: joint formalization of Π/J and E/J as the deployable metrological standard for an IAIA treaty protocol.

---

## 12. Version History

| Version | Key Change |
|---------|-----------|
| v7.0001–v7.0003 | Early drafts, foundational axiom set |
| v7.0004 | Full Oracle Integration — GPD + autoresearch bridge |
| v7.0005 | Seven Axiom Consolidation |
| v7.0006 | Three-Tier Decoupling |
| v7.0007 | Root Hypervisor + Stochastic Mycelial Horizon + Loop 3 honest reclassification |
| v7.0008 | Landauer-bounded Π/J + E/J (Takahashi-Hayashi); Tripartite Transducer Tier 2 formal spec; FTLE-bounded N_max; A-MCTS puncturing; Protocol 0 (Polycentric Genesis); TAB; val_bpb retired |

---

## References

1. Bai, Y. et al. (2022). Constitutional AI: Harmlessness from AI Feedback. arXiv:2212.08073
2. Christiano, P. et al. (2017). Deep Reinforcement Learning from Human Preferences. NeurIPS.
3. Rafailov, R. et al. (2023). Direct Preference Optimization. arXiv:2305.18290
4. Takahashi, K. & Hayashi, Y. (2026). Thermodynamic Limits of Physical Intelligence. arXiv:2602.05463
5. Geiger, A. et al. (2023). Causal Abstraction for Faithful Model Interpretation. arXiv:2301.04709
6. Holling, C.S. (1973). Resilience and Stability of Ecological Systems. Annual Review of Ecology.
7. Bar-Yam, Y. (1997). Dynamics of Complex Systems. New England Complex Systems Institute.
8. Ostrom, E. (1990). Governing the Commons. Cambridge University Press.
9. Curved Inference. arXiv:2507.21107
10. Transformers learn factored representations. arXiv:2602.02385
11. Confidence is Not Competence. arXiv:2510.24772
12. Cross-Layer Transcoders are incentivized to learn Unfaithful Circuits. LessWrong, 2025.
13. Domestic frontier AI regulation, an IAEA for AI. arXiv:2507.06379
14. Training Compute Thresholds. GovAI, 2023.
15. Karpathy, A. autoresearch framework. GitHub.

---

*STIM Protocol v7.0008 | Apache 2.0 | github.com/STIM-Protocol*
*"Sociology cannot constrain thermodynamics. But thermodynamics can constrain AI."*
