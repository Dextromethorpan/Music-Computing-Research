---
pain_point: Research Code Bit-Rots Faster Than the Papers Citing It
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

A published research tool's code often stops working within a few years because it was pinned to specific old versions of Python or its dependencies, and nobody goes back to fix it once the paper is out. This hits two groups: other researchers trying to build on or benchmark against the original work (who now have to fight dependency hell just to get a baseline running), and downstream open-source projects that quietly inherited the same broken dependency because they built on top of the original tool.

## Evidence
madmom (from CP-JKU, Austria) — a widely-used Python library for beat tracking, onset detection, and other MIR tasks — has multiple real, still-relevant GitHub issues about it being broken on modern Python: issue #502 ("Incompatible with Python 3.10 because MutableSequence was moved to collections.abc"), issues #527 and #535 (general Python 3.10+ incompatibility), issue #485 (a numpy ABI break), and older install failures like #478 and #373. The problem cascades: CP-JKU's own newer project `beat_this` has open issue #9 ("`madmom` dependency requires python<=3.9"), meaning a current CP-JKU tool is itself stuck behind its own older tool's unfixed compatibility problem.

## Surfaced in
- [[Open Source Research Tools]]

## Labs/companies addressing this
No known lab/company addressing this yet

## Niche Verification (2026-08-28)

**Causal barrier:** distribution — pinning/upgrading dependencies and patching broken imports is routine software-engineering work, not deep DSP/ML expertise, and the problem is well articulated and actively tracked in public issue trackers (not an awareness gap). The likely reason nobody has built a "fix my broken research repo" product is the same as the sibling Pain Point: the buyer (an individual researcher or small lab, often grant-funded) has no budget and no procurement channel, and each fix is fairly bespoke per repo, which discourages a scalable commercial offering.
**Clustering:** false — surfaces under only [[Open Source Research Tools]]; the only named org (CP-JKU) is a single lab in a single country (Austria).
**Incumbency:** commercial=none, research=none — the Pain Point note lists no known lab or company addressing this generally; CP-JKU itself is the victim of the pattern (its own newer tool `beat_this` is stuck behind `madmom`'s unfixed compatibility problem), not a fixer of it.
**Transfer case:** no data — no Meta_Industries (Concept, Country) tuple file exists in this vault.
**Lab transfer candidate:** no — no lab is linked as addressing this; CP-JKU is affected by it, not solving it.

### Demand evidence
- [madmom Issue #557 — "Complete patch for np.float/np.int removal in numpy>=1.24"](https://github.com/CPJKU/madmom/issues/557) (2026-02-18, GitHub, recurring-complaint) — current, unresolved-as-of-filing NumPy compatibility break affecting 11 files, continuing the exact pattern the note describes.
- [madmom Issue #553 — community request for an updated release](https://github.com/CPJKU/madmom/issues/553) (2025-06-24, GitHub, recurring-complaint) — users asking maintainers to cut a new PyPI release because the repository's fixes aren't reaching installs, i.e. explicit demand for someone to un-bit-rot the package.
- [madmom Issues #550 and #547 — installation and import failures](https://github.com/CPJKU/madmom/issues) (2025-05, GitHub, recurring-complaint) — further, more recent install/import breakage reports on top of the ones already logged in the note (#478, #373, #485).
- [PyPitfall: Dependency Chaos and Software Supply Chain Vulnerabilities in Python](https://arxiv.org/html/2507.18075v1) (2025-07, arXiv preprint, academic-mention) — recent academic study of Python dependency-chaos failure modes broadly, corroborating that this is a recognized, structural problem in the Python research/scientific ecosystem, not specific to one library.
- [CPJKU/beat_this Issue #9 — "`madmom` dependency requires python<=3.9"](https://github.com/CPJKU/beat_this/issues/9) (2025-01-29, GitHub, recurring-complaint; stale: true) — already cited in the note's own Evidence section; independently confirmed via direct fetch as closed without a real fix (workaround only), showing the cascading-dependency problem persisted past the point of an easy resolution.
