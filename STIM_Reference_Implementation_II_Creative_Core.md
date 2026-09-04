# STIM Protocol Reference Implementation II: The Creative Core

Seven Axioms as Generative Constraints in Multi-Agent Creative Collaboration

Draft framing v0.1 | September 3, 2026 | Bodhi (companion to STIM_Case_Study_Reference_Implementation.md)

## Abstract

The STIM Protocol constrains inference at Layer 0 through seven nature-derived axioms. Its first reference implementation, Arboracle, demonstrated the axioms as test oracles on deterministic land-stewardship workflows. This companion demonstrates the same architecture on a non-deterministic domain: generative creativity across an agent fleet.

The core claim is simple. Statistical convergence, the median output, is the signature of an agent with no inferred memory of its principal. Two models trained on the same corpus converge on the same safe answer. Stasis Through Inferred Memory is the countermeasure: append-only taste corpora (kept logs, rejection records, draft archives, compost) that constrain generation before task logic runs. An agent whose substrate is one human's accumulated decisions cannot converge on the median, because the median never got to vote.

Evidence from the first live audit cycle shows the axiom-as-test-oracle pattern generalizes beyond deterministic systems. A creativity skill that violated its own first principle was caught by applying that principle as a test, exactly as Arboracle bugs mapped to STIM axiom violations.

## 1. The Convergence Problem

A language model's default drift is toward the statistical middle. Balanced summaries. Committee phrasing. The answer any competent writer would produce. This is not a defect. It is the expected output of an agent whose memory contains no record of a specific principal's taste.

The creative industries named this problem decades before language models existed. Producers who flatten a track into glossy consensus produce records with no fingerprints. The fix in the studio was never a better microphone. It was a producer with a decade of sessions in their ears, accountable to one artist's standards.

The agent equivalent is not a better prompt. It is accumulated, queryable memory of what the principal kept and what they cut.

## 2. Taste as Inferred Memory

Reference Implementation II is built on three memory structures, all append-only, all axiom-compliant:

• Kept Log: what the principal acted on, versus what an agent surfaced. The ratio is the taste metric.
• Rejection Record: what was cut and why. An n=1 aesthetic corpus: the median cannot form because the median never got to vote.
• Draft Graveyard: every version archived, including raw first passes, so editorial reversion is always available.

The corpus is split per agent, not shared: one agent holds the writing record, another the operational record, another the research record. Divergence comes from different soil. One skill installed on three agents without split substrate produces one set of ears with three names.

## 3. Axioms as Generative Constraints

Each axiom from v7.0011 maps to a constraint on generative work:

• Thermodynamic Honesty: no health or quality claim without fresh evidence in the same message. Minimum energy spent on options the principal will not act on.
• Mycelial Connectivity: dissent propagates through the fleet rather than dying in one context. Decomposed output from one domain feeds another.
• Carrying Capacity Respect: an artifact has a signal capacity. Stacking dilutes until individuality disappears. Cumulative load limits apply to attention as they do to canopy.
• Memory Stasis: append-only provenance on every creative decision. Taste is inferred memory made durable.
• Human Primacy at the Boundary: autonomous generation is permitted at zero stakes. Every consequential boundary returns to the principal.
• Citation Integrity: taste is rooted in the principal's primary corpus, never in secondhand summaries. Lived experience is the citable source.
• Intrinsic Value: work is built to private standards with no audience. The raw spark is the real stored value; polish that removes it is fabrication.

The canon rule: any change to the creative constraint layer that violates a STIM axiom is a bug, not a preference.

## 4. The Board of Ears: Polycentric Audit for Creative Work

The audit mechanism inherits from Protocol 0's polycentric governance. One agent drafts, another critiques, unanimity is a failure state: if all reviewers approve, the work converged.

The protocol upgrade after the first run: sealed-bid dissent. Each agent writes its objection before reading the others', then the fleet reconciles. Mandated dissent without a venue becomes theater. Sealed bids restore genuine friction.

## 5. Evidence: Audit Run #1

The first live cycle produced a falsifiable result. The creativity skill (the artifact under test) was seeded from a secondhand summary of its own source material. That is a self-consistency violation: a skill about rejecting the median, built from the median. The violation was caught not by the author but by a second agent applying the skill's first principle as a test oracle. Three confirmed defects, one concession, one held position. The audit mechanism functioned.

This is the same pattern documented in the first reference implementation: bugs in the system mapped to violations of the axioms that govern it. The axiom set functions as a test suite in a domain with no deterministic ground truth.

## 6. Layer 0 Kinship

STIM constrains inference at Layer 0, before task logic runs. The creative constraint layer operates the same way: it shapes generation before drafting logic executes. Both are pre-task constraint manifolds. Both are nature-derived. Both treat memory as the substrate of identity rather than a convenience feature.

## 7. Position

Reference Implementation I (Arboracle) proved the axioms on deterministic workflows with legal and ecological stakes. Reference Implementation II proves them on non-deterministic generative work with aesthetic stakes. Together they support the protocol's central claim: the axiom set is substrate-independent, and violations are detectable wherever they occur.

Licensing: CC BY 4.0, consistent with the white paper and first case study. Staging: STIM-Protocol/white-paper repository as a companion document. Zenodo archival alongside DOI 10.5281/zenodo.21297458 upon release.

## Appendix: Source Documents

• Creative Core Architecture: Fleet Skill v1.0 (doc-498)
• Board of Ears Run #1: Canonized Decisions (doc-499)
• The Seven Mods, Canonical (doc-500)
• Creative Core / STIM Protocol Axiom Correlation Map (doc-502)
• Hermes Response: Creative Core Dissent, Root-System Mods (hermes/creative-core-response-2026-09-03)
