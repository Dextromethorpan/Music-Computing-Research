---
pain_point: Streaming Platforms Use ML Recommendation Systems to Quietly Replace Human Artists with Cheaper Stock Music
addressed: No
date_first_seen: 2026-08-14
tags: [pain-points-color/green]
causal_barrier: distribution
clustering: false
commercial_incumbency: none
research_incumbency: none
transfer_case: false
lab_transfer_candidate: false
confidence: provisional
niche_verified: 2026-08-28
---

Machine-learning-driven mood/genre playlists (ambient, focus, chill, lounge-type categories) are a major discovery channel for listeners and a real royalty stream for artists. But because most of a streaming service's royalty budget goes to major-label catalogs, there's a direct financial incentive to fill algorithmically-curated playlists with cheap, non-royalty-bearing "production music" from library-music companies instead of real artists — without disclosing the substitution to listeners. Working musicians who'd otherwise be discovered through these playlists lose real streams and income to functionally anonymous stock tracks optimized to sound like them.

## Evidence
Music writer Liz Pelly's investigation "The Ghosts in the Machine" (Harper's Magazine, published based on reporting escalating through 2024) documented Spotify's internal "Perfect Fit Content" (PFC) program, running since 2017, which partners with production-music companies like Sweden's Epidemic Sound to fill algorithmic playlists at far lower royalty cost than paying real artists. Music writer David Turner's independent analytics showed Spotify's "Ambient Chill" playlist had its named artists — Brian Eno, Bibio, Jon Hopkins — quietly replaced with PFC tracks. By 2023, a dedicated internal team was reported to be monitoring over 150 playlists (including "Deep Focus," "Bossa Nova Dinner," "Cocktail Jazz," "Morning Stretch") that had become nearly entirely PFC-filled. Spotify current or former employees are reported to have corroborated the financial motivation directly to journalists.

## Surfaced in
- [[Machine Learning for Music]]

## Labs/companies addressing this
No known lab/company addressing this yet

## Niche Verification (2026-08-28)

**Causal barrier:** distribution — the evidence shows this is not a hard technical problem (production-music substitution is a straightforward business/curation decision) and it is not merely unnoticed (extensively reported since 2024-2025); the actual blocker for a beginner-buildable fix is that the affected buyer (individual working musicians losing playlist placement) has no channel to organize around or pay for a solution, and the platform holding the distribution chokepoint (Spotify) has no incentive to change it. Classified as distribution rather than regulatory since no evidence of a certification/licensing block was found, and rather than technical since nothing here is a hard engineering problem.
**Clustering:** false — Surfaced in only links to [[Machine Learning for Music]]; no other Concept or Country independently corroborates this pain point, and no orgs are formally linked.
**Incumbency:** commercial=none, research=none — the Pain Point note lists no known lab or company addressing this (Spotify and Epidemic Sound are the parties causing the problem, not fixing it).
**Transfer case:** no data — vault has no Meta_Industries (Concept, Country) -> Industries -> Companies tuple file to check against.
**Lab transfer candidate:** no — no lab is linked to this pain point.

### Demand evidence
- [The Ghosts in the Machine](https://harpers.org/archive/2025/01/the-ghosts-in-the-machine-liz-pelly-spotify-musicians/) (2025-01, trade press/Harper's Magazine, recurring-complaint) — Liz Pelly's investigation documenting Spotify's "Perfect Fit Content" program partnering with production-music companies like Epidemic Sound to fill algorithmic playlists at lower royalty cost than real artists.
- [Are We Losing the Artist to Spotify?](https://www.34st.com/article/2025/10/spotify-profitable-fit-content-controversy-helsing-ai) (2025-10-17, trade press/34th Street Magazine, recurring-complaint) — reports PFC "ghost artists" displacing named artists from playlists like Deep Focus (4.5M subscribers); quotes Massive Attack condemning the practice and notes bands (Deerhoof, King Gizzard, Hotline TNT) pulling catalogs from Spotify in protest, but also notes most listeners keep using the platform regardless.
- [While Spotify Starves Real Artists, AI "Music" Thrives on the Platform](https://leafandcore.com/2025/09/19/while-spotify-starves-real-artists-ai-music-thrives-on-the-platform/) (2025-09-19, trade press/Leaf&Core, recurring-complaint) — independent coverage corroborating the same PFC substitution dynamic roughly eight months after the original Harper's piece, indicating the story has legs rather than being a one-off.
