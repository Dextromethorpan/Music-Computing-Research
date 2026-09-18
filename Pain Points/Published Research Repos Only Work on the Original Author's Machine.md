---
pain_point: Published Research Repos Only Work on the Original Author's Machine
addressed: No
date_first_seen: 2026-08-14
tags: [pain-points-color/blue]
causal_barrier: distribution
clustering: false
commercial_incumbency: none
research_incumbency: none
transfer_case: false
lab_transfer_candidate: false
confidence: provisional
niche_verified: 2026-08-28
---

"Code available on GitHub" doesn't mean the code is actually usable by anyone else. A recurring failure mode in academic research code is that it was only ever run and tested on the original author's own laptop or lab server: file paths are hardcoded to that machine, dependency versions aren't pinned so a fresh install pulls incompatible newer packages, some files referenced by the code were simply never uploaded, and documentation — if any exists — assumes the reader already knows the internal structure of the project. Anyone else trying to reproduce the paper's results or extend the work has to reverse-engineer the setup from scratch.

## Evidence
A widely-shared blog post, "Academics: You're Doing Open Source Wrong," lays out this exact pattern as endemic to academic code: missing files the researcher forgot to upload, hardcoded file paths to the researcher's own machine, missing documentation, and unpinned Python dependency versions — and notes that on the rare occasions a research repo is properly packaged, both the repo and the paper it accompanies get dramatically more attention and reuse, implying most aren't. The existence of a dedicated, hand-curated GitHub list, `faroit/reproducible-audio-research` (maintained by an established MIR researcher specifically to track which audio-research papers have code that actually works), is itself evidence that this is a real, recurring problem in this field rather than a generic complaint about open source overall — a curated "does it actually work" list wouldn't need to exist otherwise.

## Surfaced in
- [[Open Source Research Tools]]

## Labs/companies addressing this
No known lab/company addressing this yet

## Niche Verification (2026-08-28)

**Causal barrier:** distribution — building reproducibility tooling (env capture, dependency pinning helpers, doc scaffolding) is not deep DSP/ML-hard, and the problem is already clearly articulated (a widely-shared blog post plus a hand-curated tracking list both name it precisely), which rules out awareness. What's actually missing is a paying buyer: individual academic researchers have no budget and no procurement channel for this kind of tool, so nobody has built a standalone product around it even though the underlying engineering is tractable.
**Clustering:** false — surfaces under only [[Open Source Research Tools]]; no linked orgs at all, so no cross-Country signal either.
**Incumbency:** commercial=none, research=none — the Pain Point note lists no known lab or company addressing this.
**Transfer case:** no data — no Meta_Industries (Concept, Country) tuple file exists in this vault.
**Lab transfer candidate:** no — no lab is linked to this Pain Point, so there is no specific resource to point to.

### Demand evidence
- [Academics: You're Doing Open Source Wrong](https://chanind.github.io/2023/06/04/academics-open-source-research-code-python-tips.html) (2023-06-04, personal blog, recurring-complaint; stale: true) — the same source cited in the note's own Evidence section; independently confirms the failure pattern (hardcoded paths, missing files, unpinned deps) is treated as endemic and widely recognized among ML/research practitioners.
- [faroit/reproducible-audio-research](https://github.com/faroit/reproducible-audio-research) (ongoing, GitHub, existing-failed-attempt) — a hand-curated list maintained by an established MIR researcher specifically to track which audio-research papers have code that actually runs; its continued existence is itself evidence the underlying problem has no systemic fix, only manual triage. No single technical or distribution failure reason is stated for why no product has replaced this list, so none is asserted here.
- [GitHub is an effective platform for collaborative and reproducible laboratory research](https://arxiv.org/html/2408.09344v1) (2024-08, arXiv preprint, academic-mention; stale: true) — academic treatment of the same reproducibility gap in a research-lab context, corroborating it as a recognized, discussed problem rather than a one-off complaint.
