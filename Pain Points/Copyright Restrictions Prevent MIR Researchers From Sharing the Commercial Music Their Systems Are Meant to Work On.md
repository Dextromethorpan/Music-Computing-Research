---
pain_point: Copyright Restrictions Prevent MIR Researchers From Sharing the Commercial Music Their Systems Are Meant to Work On
addressed: Yes
date_first_seen: 2026-08-17
tags: [pain-points-color/brown]
causal_barrier: regulatory
clustering: false
commercial_incumbency: none
research_incumbency: mature
transfer_case: false
lab_transfer_candidate: false
confidence: provisional
niche_verified: 2026-08-28
---

Music Information Retrieval systems (genre classifiers, recommendation engines, audio fingerprinting) are meant to work on the commercial music people actually listen to — but the labels that own that music impose rigid copyright restrictions that prevent researchers from freely redistributing the actual audio in a shared dataset. This has historically starved the field of publicly available, freely reusable benchmark datasets: researchers either work around it with indirect representations (storing only URLs to lyrics rather than the lyrics themselves, distributing pre-extracted audio features instead of raw audio) or restrict themselves to permissively-licensed but less representative music, meaning benchmarks either can't legally include mainstream commercial music or can't be freely shared once they do.

## Evidence
MIR research has historically suffered from a lack of publicly available benchmark datasets stemming directly from labels' commercial interest in music and the resulting rigid copyright restrictions, which prevent researchers from sharing their music collections with others — documented specifically in the context of lyrics datasets, where licensing limitations mean no freely available lyrics dataset has ever been published for research, forcing researchers to store only URLs to lyrics rather than the text itself. The Free Music Archive (FMA) dataset's own design is direct evidence of the workaround this problem forces: it explicitly restricts itself to tracks whose license permits redistribution (Creative Commons CC0/CC-BY) specifically to be legally shareable, rather than sampling the commercial catalog MIR systems are ultimately meant to serve.

## Surfaced in
- [[Music Information Retrieval]]

## Labs/companies addressing this
- [[Spain/Labs/Music Technology Group (MTG)/Lab|Music Technology Group (MTG)]] — Freesound and the broader CompMusic effort are built around openly-licensed and non-commercial audio specifically to sidestep this restriction while still producing usable, shareable MIR research datasets.

## Niche Verification (2026-08-28)

**Causal barrier:** regulatory - the evidence is explicit that the blocker is rights-holder copyright/licensing (labels restrict redistribution of commercial audio), not technical difficulty; researchers work around it with URL-only lyrics references, feature-only distribution, or permissively-licensed substitutes.
**Clustering:** false - surfaces under only one Concept ([[Music Information Retrieval]]) and the one linked org (MTG) is in a single country (Spain). No independent cross-Concept or cross-Country corroboration found.
**Incumbency:** commercial=none, research=mature - no companies are linked to this Pain Point. On the research side, MTG's Freesound (a completed, deployed platform with hundreds of thousands of users, live since ~2013) and the CompMusic effort represent a working, shipped method for sidestepping the restriction via openly-licensed audio - the workaround itself is mature, even though it does not solve the underlying commercial-catalog access problem.
**Transfer case:** no data - no Meta_Industries (Concept, Country) -> Industries -> Companies tuple file exists in this vault, so no cross-country transfer comparison could be run. Recorded as `false` with this caveat rather than a genuine negative finding.
**Lab transfer candidate:** no - Freesound/CompMusic are workarounds (alternative, openly-licensed content sources), not a productizable solution to the actual copyright-access problem researchers face with commercial catalogs; nothing concrete points to a specific resource that could be turned into a product addressing this pain point directly.

### Demand evidence
- [Ethical Dimensions of Music Information Retrieval Technology](https://transactions.ismir.net/articles/10.5334/tismir.13) (2018, TISMIR journal, academic-mention) - documents that MIR evaluation datasets typically cannot be publicly shared due to copyright restrictions, framing this as an ethics-vs-legality tension in the field. [stale - 2018, well past 24 months]
- [Sound Check: Auditing Recent Audio Dataset Practices](https://ojs.aaai.org/index.php/AIES/article/download/36528/38666/40603) (2025, AIES/AAAI conference proceedings, academic-mention) - recent audit finding major audio datasets carry licenses restricting commercial use/derivatives, and documents increasing restrictiveness (YouTube crawler-blocking, Spotify removing a 100k-hour podcast dataset in Dec 2023), showing the access problem is getting worse, not resolving.
