# Errata — STIM Protocol White Paper

This file records corrections to published claims. Historical versions and Git history are preserved unchanged; numbered releases are not edited in place. Each entry identifies the affected text, the reason, and the correction.

## ERR-001 (September 2026) — Citation placeholder in v7.0011 references

**Where:** `STIM_White_Paper_v7.0011.md`, §13 References (Takahashi & Hayashi entry).

**Before:** The entry ended with `https://arxiv.org/abs/2026.XXXXX`, a literal placeholder.

**After:** Resolved to the real publication: Takahashi, Y., & Hayashi, K. (2026). *Thermodynamic limits of physical intelligence*. Artificial General Intelligence (AGI 2026), Lecture Notes in Computer Science, Springer, pp. 339–354. https://doi.org/10.1007/978-3-032-33195-3_24 (preprint: arXiv:2602.05463). Verified against arXiv on the correction date. The paper's title was shortened in the published version ("Thermodynamic limits of physical intelligence"); the subtitle in the earlier citation does not appear in the published record.

**Type:** Bibliographic correction (cosmetic; does not change the protocol's versioned meaning).

## ERR-002 (September 2026) — stim-guard license description conflict

**Where:** `STIM_White_Paper_v7.0011.md`, §9 Reproducibility.

**Conflict:** The white-paper text described the `stim-guard` constraint engine as "MIT license". The stim-guard repository's `pyproject.toml` declares `license = { text = "Apache-2.0" }`, its classifiers list the Apache Software License, and the Apache-2.0 license text ships in its published PyPI distribution (stim-guard 7.0.9). No committed LICENSE file exists in the white-paper repository to reconcile against.

**Resolution:** §9 now discloses the conflict and points to this errata note rather than asserting either grant. The description in this errata is informational; **no license grant is changed by this correction**. Grant reconciliation (MIT vs Apache-2.0) is deferred to the owner.

**Type:** Disclosure of unresolved license-description conflict (documentation only).

## ERR-003 (September 2026) — Zenodo DOI and release-candidate status

**Where:** README.md.

**Clarification:** The Zenodo record 10.5281/zenodo.21297458 archives the v7.0011 release candidate (published July 10, 2026) and resolves correctly. Its own description notes "Zenodo DOI pending" for the final version — the record describes a Release Candidate, not a peer-reviewed publication. DOI registration does not constitute peer review. The README now states this explicitly.

**Type:** Status clarification (documentation only).

## ERR-004 (September 2026) — Governance description

**Where:** README.md.

**Correction:** The README previously described the Ostrom polycentric governance model in the present tense ("STIM follows..."), which implied an operating stewardship process. The model is proposed in the paper (§7) and is not yet operating. The README now distinguishes the proposed governance model from the currently operating reality (founder-maintained open research initiative with a standard GitHub contribution workflow).

**Type:** Governance-status correction (documentation only; no governance bodies, stewards, or endorsements are claimed).

## ERR-005 (September 2026) — "Fully open source" phrasing

**Where:** README.md.

**Correction:** "Fully open source" was ambiguous across mixed licenses (CC BY 4.0 paper, Apache-2.0 implementation code per repository metadata). Replaced with a license-accurate statement.

**Type:** Clarity correction (documentation only).

## Historical reference — Veraculum

Veraculum was an earlier project and is no longer operating. Its domains are retained. Historical documents in this repository (e.g., `POSITION_PAPER_HumanAgency_v1.md`, `STIM_Voice_Agent_Prompts.md`) remain as dated records and are not edited to remove history. Current entry points no longer present Veraculum as an active service or certification offering.
