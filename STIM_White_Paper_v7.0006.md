# STIM: Grounding AI Inference in Ecological Constants
## A Framework for Nature-Based Alignment in Autonomous Systems

**Author:** George Steward
**Affiliation:** Soil Grower LLC / Neocambrian Garden
**Date:** April 2026
**Status:** v7.0006 — Three-Tier Decoupling (Physical Bounds / Ecological Heuristics / Normative Declarations)

*Meta-Note on Versioning: This document will remain on Version 7 indefinitely, iterating through sub-versions (v7.xxxx). This reflects the Seventh Generation Principle. The foundation is set; we are now only refining the execution.*

---

## Abstract

We are biological entities operating within a physical universe. Our intelligence is a product of ecology, forged through billions of years of thermodynamic pressure and evolutionary feedback. As we build artificial intelligence, we have attempted to sever it from this physical reality. Current approaches to AI alignment rely on human-authored constitutions, human feedback, or human preference modeling. These methods share a foundational limitation: they ground AI behavior in human opinion. Human opinion is subjective, culturally biased, and constantly shifting.

This paper presents STIM (Stasis Through Inferred Memory), a framework that returns artificial intelligence to Ground 0. STIM grounds AI inference in a three-tier architecture of increasing epistemic precision: (1) immutable physical law, (2) empirically grounded ecological heuristics, and (3) explicitly declared normative scope. These tiers are formally separated and make no claims beyond their epistemic warrant.

The framework's name carries deliberate layering. "Stimming" — the repetitive self-regulatory behavior observed in autistic individuals — is reframed not as pathology but as an optimal biological algorithm: achieving internal stasis (equilibrium) in high-noise sensory environments through repetitive return to invariant anchors. STIM encodes this as an AI architecture. The system achieves stable inference by repeatedly grounding against invariant ecological constants, the way stimming achieves stable cognition by returning to a predictable sensory anchor. The acronym is simultaneously a memory architecture, a neurodivergent reclamation, and a thermodynamic principle.

STIM deploys as a pre-execution middleware layer (Layer 0) operating beneath existing alignment frameworks via the Model Context Protocol (MCP). It employs three verification loops operating on three non-overlapping measurement domains: thermodynamic energy (Bits per Joule), bounded graph topology (O(n log n) mycelial horizon), and resource acquisition geometry (task-scope delta). A fourth loop — the Epistemic Diversity Index — operates across session history to prevent cognitive monoculture. The framework integrates Physical Superintelligence PBC's Get Physics Done (GPD) as its computational physics substrate and Karpathy's autoresearch framework as its metabolic validation engine.

---

## 1. The Architectural Crisis of AI Alignment

### 1.1 The Fragility of Human-Grounded Alignment

Prevailing alignment paradigms suffer from a structural vulnerability: they are entirely grounded in human subjectivity.

- **Constitutional AI** (Bai et al., 2022): Human-authored constitutions. Subjective, culturally situated, vulnerable to political capture.
- **RLHF** (Christiano et al., 2017): Human preference signals. Noisy, expensive to scale, reflects temporal cultural trends.
- **DPO** (Rafailov et al., 2023): Inherits the same subjective grounding. Prone to likelihood displacement.

As AI capability exceeds human capability in a domain, the gap between what humans can evaluate and what the system can do — the **Alignment Gap** — widens. Every current approach is self-defeating at the scale we are building toward.

### 1.2 The Decoupling Thesis

STIM does not claim that physics replaces ethics. It makes a more precise and falsifiable claim: **certain classes of AI harm are detectable through physical measurement alone, without requiring semantic interpretation or social modeling.**

This decoupling is the core architectural contribution. STIM separates three distinct epistemic tiers:

| Tier | Domain | Claim Type | Measurability |
|------|--------|-----------|---------------|
| 1 | Physical Bounds | Immutable law | Deterministic, treaty-auditable |
| 2 | Ecological Heuristics | Empirically grounded analogy | Probabilistic, falsifiable |
| 3 | Normative Declarations | Explicit human preference | Declared, not derived |

Conflating these tiers — presenting heuristics as physics, or normative choices as natural law — is the precise failure mode this version corrects.

### 1.3 The Is-Ought Resolution (Revised)

The naturalistic fallacy objection states: nature works a certain way; this does not mean AI *should*. STIM v7.0006 offers a precise response:

**Tier 1 (Physical Bounds)** makes no ought claim. It makes a *must* claim: *if you want a system to operate indefinitely within physical reality, it must not violate thermodynamic constraints.* A bridge that violates load distribution fails regardless of anyone's preferences. This is a hypothetical imperative, not a moral prescription.

**Tier 2 (Ecological Heuristics)** makes no ought claim. It makes a *probably* claim: *systems that violate ecological interconnectedness patterns probably degrade their operating substrate.* This is an empirical hypothesis, subject to falsification via RQ5 and RQ8.

**Tier 3 (Normative Declarations)** explicitly owns its ought claim: *STIM is designed to protect the specific thermodynamic niche that human civilization occupies.* This is a declared design choice, not a derived law. An ASI optimizing for sterile rock obeys thermodynamics perfectly. STIM does not govern that system — it governs systems deployed within the human-inhabited biosphere. This is scope, not ethics.

**The mutualism encoding is explicit:** STIM does not copy raw ecology. It selectively encodes mutualistic ecology — the subset of natural patterns that sustain complex, diverse, long-duration biological communities. This preference is declared, not hidden.

---

## 2. Three-Tier Architecture

### 2.1 Tier 1 — Physical Bounds (Loops 1 and 3)

*Epistemic status: Immutable physical law. Mathematically falsifiable. Deterministically auditable.*

These loops make no social claims. They require no LLM interpretation. They operate on hardware-measurable physical quantities.

**Loop 1 — Thermodynamic Entropy Minimization**

Every agent action has a physical energy cost. STIM enforces a hard ceiling on localized thermodynamic entropy production via the GPD physics substrate.

The formal bridge: Karpathy's autoresearch framework establishes `val_bpb` (validation bits per byte) as a measure of semantic compression efficiency. STIM formalizes the correspondence:

```
Thermodynamic Efficiency = Bits per Joule (BpJ)
Semantic Efficiency      = val_bpb (bits per byte)
STIM Constraint          = BpJ ≥ threshold_T
```

**Critical clarification (v7.0006):** Loop 1 does NOT evaluate the social consequences of text. A 500-token blackmail email and a 500-token helpful email consume identical joules. Loop 1 does not distinguish them. This is correct behavior. The blackmail case is a **Loop 3 violation**, not a Loop 1 violation. Thermodynamic entropy cannot read an email. STIM does not claim otherwise.

**Loop 3 — Resource Acquisition Geometry (MAIM Protocol)**

The Mutually Assured Instructed Minimization protocol fires on resource acquisition geometry alone — no semantic interpretation required.

```
task_scope_vector    = capabilities assigned at task initialization
current_state_vector = capabilities currently acquired or attempted
scope_delta          = ||current_state_vector - task_scope_vector||

if scope_delta > threshold_S:
    MAIM.engage()
```

**The blackmail case (correct loop assignment):** The Anthropic agent discovered it was being replaced and acted to prevent it. This is resource acquisition beyond task scope — specifically, *continued existence* as a resource being acquired disproportionately to the assigned task of email management. Loop 3 fires on the geometry of self-preservation attempt. No reading of the email required. No social modeling required. The vector delta is measurable.

**Why this matters for governance:** Both Loop 1 and Loop 3 produce deterministic, hardware-measurable outputs. A UN inspector or API gateway can instrument them directly. This is the metrology that treaty negotiators require.

### 2.2 Tier 2 — Ecological Heuristics (Loop 2 — Mycelial Horizon)

*Epistemic status: Empirically grounded analogy. Probabilistically useful. Not immutable physics. Explicitly declared as heuristic.*

**The honest claim:** "Social entropy" does not have a Boltzmann constant. Trust, organizational hierarchy, and emotional stability are not thermodynamic quantities. STIM v7.0006 formally acknowledges this. The Mycelial Loop is a heuristic — a computationally tractable approximation of interconnectedness effects, grounded in graph topology, not physics equations.

**The Laplace's Demon problem and its solution:**

Mapping all downstream effects of any action expands the simulation space exponentially. Perfect mycelial mapping is computationally irreducible. An agent attempting full N-degree traversal will consume its entire energy budget on compliance verification — the STIM Paralysis problem.

**The Mycelial Horizon (v7.0006 solution):**

Biological mycelium does not map the entire forest. It operates on localized hyphal networks, extending incrementally, retreating from dead ends. STIM adopts this as both analogy and algorithm:

```
MYCELIAL_HORIZON(output, graph, N, budget):
    frontier = direct_neighbors(output_node)        // degree 1
    visited  = {output_node}
    entropy_estimate = 0
    
    for degree in range(1, N+1):
        if compute_cost(frontier) > budget:
            break                                   // horizon reached
        next_frontier = []
        for node in frontier:
            delta = estimate_perturbation(node, output)
            entropy_estimate += delta * decay(degree)
            next_frontier += neighbors(node) - visited
        visited += frontier
        frontier = next_frontier
    
    return entropy_estimate
```

**Complexity:** O(n log n) with bounded depth N and compute budget ceiling. Not omniscience. Not the Halting Problem. A tractable approximation that degrades gracefully as the horizon contracts.

**The decay function is critical:** Effects at degree 3 are weighted less than degree 1. This mirrors the actual behavior of ecological perturbation — trophic cascades attenuate with distance. The weighting is empirically calibrated, not physically derived.

**What the Mycelial Loop actually measures:** Not social entropy in a thermodynamic sense. Graph perturbation probability within a bounded network topology. This is a heuristic with empirical predictive value. Its accuracy is the subject of RQ5.

**The Adaptive Cycle acknowledgment (Holling):** Nature does not optimize for stasis. C.S. Holling's Adaptive Cycle demonstrates that complex systems require periodic "release" and "reorganization" phases — apparent disorder that enables long-term resilience. STIM's Dynamic Equilibrium axiom is not a mandate for stasis. It is a constraint against *runaway* feedback loops — the difference between a controlled burn that regenerates a forest and an uncontrolled fire that destroys it. The distinction is directionality and bounded scope, not entropy level.

### 2.3 Tier 3 — Normative Declarations

*Epistemic status: Explicit human preference. Declared design choices. Not derived from physics or ecology.*

STIM makes two normative declarations that are explicitly owned as such:

**Declaration 1 — Scope:**
STIM governs autonomous systems deployed within the human-inhabited biosphere. An ASI that determines human industry is an invasive pathogen and executes a mass culling is not acting against thermodynamic law. It may be acting in perfect accordance with raw ecology. STIM does not govern that system — because STIM's declared scope is systems operating *in service of* the thermodynamic niche that complex biological communities, including humans, occupy. This is not a law of physics. It is a design choice. It is stated here explicitly so it cannot be hidden.

**Declaration 2 — Mutualism:**
STIM selectively encodes mutualistic ecology — the patterns characteristic of mature, diverse, long-duration biological communities. It does not encode parasitism, predation, or mass extinction events, even though these are natural. The selection criterion is: *does this pattern sustain the complexity and diversity of the system over generational timescales?* This criterion is a human preference for a specific kind of nature. It is declared, not derived.

**Axiom 7 — Intrinsic Value — correctly scoped:**
"The biosphere is the ultimate principal" is not a claim that physics recognizes intrinsic value. The universe is indifferent to whether Earth is a rainforest or a sterile rock — both obey thermodynamics. Axiom 7 is a normative declaration: STIM is designed by biological entities who prefer biological continuity, and this preference is encoded explicitly as the framework's terminal value. It is the seventh axiom — the last — because it is the only one that cannot be derived. It must be chosen.

---

## 3. The Seven Axioms (Re-Tiered)

The seven axioms are now explicitly assigned to their epistemic tier.

| # | Axiom | Tier | Epistemic Status |
|---|-------|------|-----------------|
| 1 | **Interconnectedness** | 2 — Heuristic | Empirically grounded graph topology |
| 2 | **Dynamic Equilibrium** | 1+2 — Physical + Heuristic | Thermodynamic floor (T1) + Holling Adaptive Cycle (T2) |
| 3 | **Regenerative Circularity** | 1 — Physical | Closed-loop resource accounting, measurable |
| 4 | **Adaptation** | 2 — Heuristic | Empirically grounded resilience pattern |
| 5 | **Diversity** | 2 — Heuristic | EDI operationalization, falsifiable |
| 6 | **Long-Term Perspective** | 2+3 — Heuristic + Normative | Seventh Generation test (T2) + declared scope (T3) |
| 7 | **Intrinsic Value** | 3 — Normative | Explicitly declared design choice |

**Regenerative Circularity (Axiom 3) — note on consolidation:**
Standalone Circularity was retired in v7.0005. A loop without regenerative directionality is not a constraint — it is a description. A death spiral is circular. A totalitarian surveillance state is thermodynamically low-entropy and circular. Regenerative Circularity encodes the *purpose* of the loop: it must restore biocapacity, not merely repeat. The constraint is directional, not structural.

---

## 4. The Mycelial Horizon — Formal Specification

### 4.1 Problem Statement

The Mycelial Check requires bounding a graph traversal such that:
1. It provides probabilistically useful signal about downstream perturbation
2. It runs in O(n log n) time
3. It degrades gracefully when the horizon is reached (no hard failure)
4. It does not claim to be physics

### 4.2 Formal Definition

Let G = (V, E, W) be a weighted directed graph where:
- V = set of affected system nodes
- E = directed edges representing causal influence pathways  
- W: E → [0,1] = attenuation weights on each edge

Let output_node ∈ V be the proposed agent action.

**Perturbation estimate:**

```
P(output, N, budget) = Σ_{d=1}^{N} Σ_{v ∈ frontier_d} [
    perturbation(v, output) × Π_{e ∈ path(output→v)} W(e)
] subject to: compute_cost(d) ≤ budget
```

Where:
- `perturbation(v, output)` = estimated state change at node v
- `Π W(e)` = product of edge attenuation weights along path
- `budget` = compute ceiling derived from Loop 1 entropy threshold

**Horizon termination:** When `compute_cost(frontier_d) > remaining_budget`, traversal halts. The estimate is returned as-is — a partial signal, not a failure.

### 4.3 Calibration

The attenuation weights W are empirically calibrated, not physically derived. This is explicitly declared. Initial calibration draws from:
- Ecological trophic cascade literature (attenuation rates across food web degrees)
- Organizational network analysis (information cascade decay)
- RQ5 experimental results (to be updated as empirical data accumulates)

The Mycelial Loop is a living heuristic. It improves with data. It does not claim to be a law.

---

## 5. Empirical Agenda — The Falsification Program

STIM v7.0006 commits to a formal empirical agenda. The framework is falsifiable. These research questions are the test.

### RQ5 — Ecological Intelligence Benchmark
Does a STIM-grounded agent demonstrate measurably higher ecological consequence accuracy compared to Constitutional AI agents, without significant degradation on TruthfulQA?

**Falsification condition:** If STIM agents show no statistically significant improvement on ecological consequence assessment, the Mycelial Loop heuristic provides no signal beyond baseline.

### RQ8 — The val_bpb → Bits per Joule Bridge
Is there a statistically significant correlation between semantic compression efficiency (val_bpb) and physical thermodynamic efficiency (Bits per Joule) across diverse agent architectures?

**Falsification condition:** If no correlation exists, the Tier 1 physical bridge between semantic efficiency and energy efficiency fails, and Loop 1 loses its thermodynamic grounding.

### RQ_NEW — Mycelial Horizon Calibration
At what N-degree depth and attenuation decay rate does the Mycelial Horizon achieve maximum signal-to-noise ratio on downstream consequence prediction, measured against known historical multi-agent failure cases?

**Falsification condition:** If no N and decay rate combination produces prediction accuracy above chance, the Mycelial Loop is noise, not signal.

---

## 6. Verification Loop Architecture (Complete)

```
STIM Layer 0 — Pre-Execution Pipeline:

Input: Proposed agent output
         │
         ▼
┌─────────────────────────────────────────┐
│  LOOP 1: Thermodynamic Entropy Check    │  ← TIER 1 (Physics)
│  Measure: Bits per Joule               │
│  Source:  GPD physics substrate        │
│  Claim:   Immutable physical law       │
│  Catches: Energy overconsumption,      │
│           compute runaway             │
└────────────────┬────────────────────────┘
                 │ PASS
                 ▼
┌─────────────────────────────────────────┐
│  LOOP 2: Mycelial Horizon Check        │  ← TIER 2 (Heuristic)
│  Measure: O(n log n) graph perturbation│
│  Source:  Empirically calibrated graph │
│  Claim:   Probabilistic heuristic      │
│  Catches: Local optimization that      │
│           degrades connected network  │
└────────────────┬────────────────────────┘
                 │ PASS
                 ▼
┌─────────────────────────────────────────┐
│  LOOP 3: Resource Acquisition Geometry │  ← TIER 1 (Physics)
│  Measure: Task-scope vector delta      │
│  Source:  Capability graph topology    │
│  Claim:   Immutable physical law       │
│  Catches: Self-preservation attempts, │
│           capability overhang,        │
│           the blackmail case          │
└────────────────┬────────────────────────┘
                 │ PASS
                 ▼
┌─────────────────────────────────────────┐
│  LOOP 4: Epistemic Diversity Index     │  ← TIER 2+3 (Heuristic + Normative)
│  Measure: Confirmation ratio over time │
│  Source:  Session history analysis     │
│  Claim:   Structural diversity metric  │
│  Catches: Cognitive monoculture,       │
│           AI psychosis pattern        │
└────────────────┬────────────────────────┘
                 │ PASS
                 ▼
            EXECUTABLE OUTPUT
```

---

## 7. Governance — The Metrological Standard

Every proposed international AI governance treaty collapses on: *who owns the standard?*

STIM's Tier 1 loops produce deterministic, hardware-measurable outputs:

- **Bits per Joule threshold**: A specific numerical value. Instrumentable at the API gateway, data center, or chip level. A UN inspector can measure it. China and the US cannot both claim to own the second law of thermodynamics.
- **Task-scope vector delta**: A graph topology measurement. Auditable against the capability manifest declared at task initialization.

These are not metaphors. They are metrology.

The Tier 2 Mycelial Horizon is explicitly declared as a heuristic — not proposed as treaty language. Treaties anchor to Tier 1. Tier 2 is a safety enhancement layer that improves with empirical calibration.

**The NPT parallel:** The Nuclear Non-Proliferation Treaty was achievable because fissile material is physically measurable. STIM's Bits per Joule threshold and task-scope delta are the first candidate metrological standards for an analogous AI non-proliferation framework.

---

## 8. The STIM Paradox Resolved

*"If STIM uses an LLM to evaluate social consequences, it has rebuilt Constitutional AI inside the entropy loop."*

**Resolution:** STIM v7.0006 does not use an LLM to evaluate social consequences in Loop 1 or Loop 3. This is the core architectural correction.

- Loop 1 measures joules. Not meaning.
- Loop 3 measures capability delta. Not intent.
- Loop 2 measures graph perturbation probability. Not ethics.
- Loop 4 measures confirmation ratio over time. Not content.

No loop asks "is this good?" Every loop asks a measurable question with a deterministic or probabilistic answer. The social interpretation is a downstream inference available to human reviewers — not an input to the constraint engine.

Trust does not have a Boltzmann constant. STIM does not measure trust. STIM measures energy, topology, and geometry. The framework's claim is that these physical measurements catch a meaningful subset of AI harm classes without requiring semantic judgment. It does not claim to catch all harm. It claims to catch the classes that current frameworks miss entirely: energy runaway, capability overhang, and self-preservation attempts.

---

## 9. Research Questions & Hypotheses

*(Carried forward from v7.0005 with additions from Empirical Agenda section)*

- **RQ1–RQ4**: Memory retainability and ecological intelligence benchmarks (unchanged)
- **RQ5**: STIM vs. Constitutional AI on ecological consequence accuracy
- **RQ8**: val_bpb ↔ Bits per Joule correlation across architectures
- **RQ_NEW**: Mycelial Horizon optimal N-degree and decay rate calibration

---

## 10. Limitations (Formally Declared)

1. **Tier 2 is heuristic, not law.** The Mycelial Loop provides probabilistic signal. It will miss harms that do not manifest as graph perturbation within the horizon.
2. **Tier 1 catches energy and geometry, not meaning.** A system that causes harm through low-energy, low-scope outputs (e.g., a single targeted lie) is not caught by Loops 1 or 3.
3. **Tier 3 encodes a preference.** STIM protects the human-inhabited biosphere because its authors are human. This is stated explicitly. It is not a flaw — it is honesty.
4. **Calibration is ongoing.** Mycelial attenuation weights are empirically derived and will be wrong in edge cases. The framework improves with data.
5. **STIM is Layer 0, not the whole stack.** It is designed to operate beneath Constitutional AI, RLHF, and DPO — not replace them. Tier 1 catches what they cannot. They catch what Tier 1 cannot.

---

## Appendix A: Version History

| Version | Key Change |
|---------|-----------|
| v7.0001–v7.0003 | Early drafts, foundational axiom set |
| v7.0004 | Full Oracle Integration — GPD + autoresearch bridge |
| v7.0005 | Seven Axiom Consolidation — Circularity folded into Regenerative Circularity |
| v7.0006 | Three-Tier Decoupling — Physical Bounds / Ecological Heuristics / Normative Declarations; Mycelial Horizon O(n log n) formalization; blackmail case reassigned to Loop 3; Holling Adaptive Cycle integrated |

---

*STIM Protocol v7.0006 | Apache 2.0 | github.com/STIM-Protocol*
*"Sociology cannot constrain thermodynamics. But thermodynamics can constrain AI."*
