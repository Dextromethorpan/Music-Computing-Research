---
pain_point: MIR Genre and Tagging Models Are Trained Almost Entirely on Western Music and Underperform on Everything Else
addressed: Yes
date_first_seen: 2026-08-17
tags: [pain-points-color/brown]
causal_barrier: technical
clustering: false
commercial_incumbency: none
research_incumbency: active
transfer_case: false
lab_transfer_candidate: true
confidence: provisional
niche_verified: 2026-08-28
---

State-of-the-art music genre classification and tagging models are trained overwhelmingly on Western datasets, so they carry that bias directly into deployment: they underperform on non-Western genres with musically distinct characteristics (different scale systems, rhythmic structures, instrumentation), and the evaluation metrics used to grade them were themselves designed around Western musical conventions, so even measuring how badly a model fails on non-Western music is methodologically shaky. This isn't a niche edge case — it affects the majority of the world's recorded musical traditions.

## Evidence
A bibliometric analysis of the field's own flagship conference — "Beyond a Western Center of Music Information Retrieval," analyzing 25 years of ISMIR authorship — documents the bias at the institutional level, not just the dataset level. A separate dataset-level analysis found that across 152 papers proposing musical datasets, only 5.7% of the music included came from non-Western genres combined (South Asian, Middle Eastern, Oceanian, Central Asian, Latin American, and African music together). Cross-cultural listening experiments cited alongside this work found significant perceptual differences in genre-similarity judgments between Western and non-Western listeners, meaning classifier performance gaps reflect a genuine mismatch in what "similar genre" even means across cultures, not just a data-volume shortfall that more Western data could fix.

## Surfaced in
- [[Music Information Retrieval]]

## Labs/companies addressing this
- [[Spain/Labs/Music Technology Group (MTG)/Lab|Music Technology Group (MTG)]] — CompMusic is a large, sustained research effort specifically built around non-Western art music traditions (Hindustani, Carnatic, Turkish-makam, Arab-Andalusian, Beijing opera), directly building the kind of non-Western corpora and culturally-aware MIR tools this bias problem is missing.

## Niche Verification (2026-08-28)

**Causal barrier:** technical - a 2025 academic paper (ACL Findings/NAACL) that specifically tested adapting music-generation models to Hindustani and Turkish Makam music found "non-triviality of cross-genre adaptation" and called for foundational model redesign, not just more data; a 2025 bibliometric study also found the field's own evaluation conventions remain Western-centric, so even measuring the gap is methodologically shaky. Conservatively classified technical rather than awareness, since recent work shows the field is aware of the problem but the fix is not straightforward.
**Clustering:** false - surfaces under only one Concept ([[Music Information Retrieval]]); the one linked org (MTG) is in a single country (Spain). No independent cross-Concept or cross-Country corroboration found in this vault.
**Incumbency:** commercial=none, research=active - no companies are linked to this Pain Point. MTG's CompMusic project (ERC-funded, primarily 2011-era) produced durable datasets/tools for five specific traditions (Hindustani, Carnatic, Turkish-makam, Arab-Andalusian, Beijing opera) still used today, but current-day (2025) academic literature treats the broader non-Western-bias problem as still unresolved and calls for further foundational work - so classified `active` rather than `mature`, conservatively, given the field-wide problem clearly outruns what CompMusic covered.
**Transfer case:** no data - no Meta_Industries (Concept, Country) -> Industries -> Companies tuple file exists in this vault, so no cross-country transfer comparison could be run. Recorded as `false` with this caveat rather than a genuine negative finding.
**Lab transfer candidate:** yes - [[Spain/Labs/Music Technology Group (MTG)/Resources/CompMusic|CompMusic]] is a concrete, specific resource (purpose-built datasets and analysis tools for five named non-Western traditions) that looks directly productizable - e.g. as culturally-aware tagging/search tools for those specific traditions - rather than just thematically related to the pain point.

### Demand evidence
- [Beyond a Western Center of Music Information Retrieval: A Bibliometric Analysis of the First 25 Years of ISMIR Authorship](https://transactions.ismir.net/articles/10.5334/tismir.265) (Nov 2025, TISMIR journal, academic-mention) - finds ~85% of ISMIR papers come from developed-economy institutions and that even well-studied non-Western traditions like Arab-Andalusian music (CompMusic's own focus) have only one relevant publication, evidencing the bias is structural and ongoing.
- [Music for All: Representational Bias and Cross-Cultural Adaptability of Music Generation Models](https://aclanthology.org/2025.findings-naacl.258/) (Apr 2025, ACL Findings/NAACL, academic-mention) - finds only 5.7% of existing music dataset hours are non-Western, and shows adapting current models to Hindustani/Turkish-Makam music is technically non-trivial even with targeted fine-tuning.
- [Proper Genre recognition - Bhangra/punjabi](https://community.spotify.com/t5/Live-Ideas/Proper-Genre-recognition-Bhangra-punjabi/idi-p/7116774) (date not shown on page, Spotify Community forum, recurring-complaint) - a real end-user asking Spotify to expose Bhangra/Punjabi as a distinct browsable genre instead of lumping it under generic "International," despite the label already using the tag internally for editorial playlists. Date could not be confirmed, so treat with caution alongside the dated evidence above.
- [Create radio not working for Malayalam songs](https://community.spotify.com/t5/App-Features/Create-radio-not-working-for-Malayalam-songs/td-p/5409339) (Jul 2022, Spotify Community forum, recurring-complaint) - user reports Spotify's radio/recommendation algorithm produces irrelevant suggestions when seeded with Malayalam-language tracks. [stale - 2022, past 24 months, but still logged as history of the same underlying complaint pattern]
