# Niche Shortlist — Signal Processing (2026-08-28)

Pain Points processed: 2. This is a ranked list of which ones clear the structural
gates — not a recommendation to build any of them. Go/no-go and real-world validation
are separate, human steps.

## Top tier - research-mature, commercially open, awareness/timing barrier
(none)

## Worth a look - clears some gates
(none)

## Low priority - technical or distribution barrier, or research still active
- [[Digitally Emulating Nonlinear Analog Circuits Introduces Aliasing That Oversampling Alone Cannot Cheaply Fix]] — causal_barrier=technical and research_incumbency=active (an active DSP research sub-field, ADAA methods, is still being refined in 2024 conference papers); per the ranking rule, technical barrier and active research both force low priority regardless of the empty commercial side.
- [[Real-Time Audio Forces an Unavoidable Trade-off Between Low Latency and Glitch-Free Playback]] — causal_barrier=technical (an inherent OS-scheduling/physical trade-off, not an awareness or timing gap); no lab or company is even logged against it in the vault, but that reflects the barrier's nature, not an open niche.

## Notes
- Only 2 Pain Points in the vault currently surface under [[Signal Processing]] (confirmed via its `## Surfaced in` wikilink, not just text mentions) - Signal Processing is a broad, foundational concept name that could plausibly have more once `music-computing-pain-points` runs further passes on it. A third candidate ("Text-to-Speech Quality Collapses for Any Language Outside the Top 20-30 Best-Resourced Ones") mentions "Signal Processing Laboratory" only as part of an org name (Aholab Signal Processing Laboratory) and is actually surfaced under [[Speech Synthesis]], not this concept - it was correctly excluded.
- No Meta_Industries (Concept, Country) -> Industries -> Companies tuple file exists anywhere in this vault, so `transfer_case` could not be evaluated for either Pain Point and was recorded as false with that caveat rather than guessed.
- Both Pain Points landed in Low priority for the same structural reason: the friction each describes (aliasing math, real-time buffer physics) is foundational DSP theory/engineering, not a productization gap - a result worth flagging to Luciano as an honest signal that "Signal Processing" itself is likely too foundational a concept to yield beginner-buildable niches directly; narrower downstream concepts (e.g. specific plug-in categories, specific hardware niches) may be more fruitful.
- Other agents are concurrently running this same skill on other Concepts in this vault (evidenced by other dated shortlist files already present in this folder); this run did not touch any Pain Point notes outside the two listed above.
