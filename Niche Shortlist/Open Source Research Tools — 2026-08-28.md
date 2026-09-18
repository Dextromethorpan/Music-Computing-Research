# Niche Shortlist — Open Source Research Tools (2026-08-28)

Pain Points processed: 3. This is a ranked list of which ones clear the structural
gates — not a recommendation to build any of them. Go/no-go and real-world validation
are separate, human steps.

## Top tier — research-mature, commercially open, awareness/timing barrier
(none)

## Worth a look — clears some gates
- [[Copyleft Licensing Locks Companies Out of Otherwise-Open Research Tools]] — barrier is regulatory (licensing, not technical), so it doesn't qualify for top tier (which needs awareness/timing), but it also isn't automatically low-priority since it's neither `technical` nor `research_incumbency: active`. Commercial incumbency is weak (MTG's own paid-license workaround for one specific library), research incumbency is none. Demand evidence for AGPL-avoidance-as-a-business-problem is real but mostly stale (2019–2024 sources); the only current source is MTG's own licensing page, which documents the barrier rather than demand for a fix.
- [[Published Research Repos Only Work on the Original Author's Machine]] — barrier classified as distribution (buyer has no budget/channel, not that the fix is technically hard or unarticulated). No incumbency on either side — genuinely open, but "open" here likely means nobody's found a way to charge for it, which is the caution flag the distribution category exists to catch. All three demand-evidence sources are 24+ months old (stale).
- [[Research Code Bit-Rots Faster Than the Papers Citing It]] — same distribution reasoning as its sibling above. No incumbency either side. This one has the strongest, most current demand evidence of the three: four of five sources are recent (2025–2026 madmom GitHub issues plus a July 2025 arXiv paper on Python dependency chaos), showing this specific friction is actively recurring right now, not just historically documented.

## Low priority — technical or distribution barrier, or research still active
(none — no Pain Point under this Concept was classified `causal_barrier: technical` or `research_incumbency: active`)

## Notes

- All three linked Pain Points are single-Concept, single-Country (`clustering: false`) — none show independent corroboration from a second Concept or a second Country's org, which is a weaker signal than a clustering `true` case would be.
- This vault has no Meta_Industries `(Concept, Country) → Industries → Companies` tuple file, so `transfer_case` was recorded as `false`/no-data for all three notes rather than a real transfer check — same caveat as the prior "Immersive Spatial Audio" run.
- Two of the three Pain Points (the reproducibility and bit-rot ones) were classified `causal_barrier: distribution` rather than `technical` on the reasoning that the underlying engineering work is not deep DSP/ML-hard, but the likely buyer (individual academic researchers/grant-funded labs) has no budget or procurement channel. This is a defensible reading of the evidence, not a certainty — Luciano should weigh whether he agrees the barrier is really "no buyer" versus "genuinely hard to do well across heterogeneous codebases" before spending validation time here. Neither reads as `awareness` or `timing`, so neither reaches top tier under the skill's ranking rule regardless.
- No Pain Point here landed in "Low priority" either — none carry a `technical` barrier or an `active`-research lab still working the problem — but none reached "Top tier" since none have an `awareness`/`timing` barrier. All three sit in a genuine middle ground: real, evidenced, currently-unaddressed frictions, but with commercial/research incumbency and barrier type that don't clearly signal "primed for a beginner product" the way the skill's top-tier bar requires.
- Only 3 Pain Points exist under this Concept despite the Concept's very large "Seen in" resource list (~85 open-source tools across ~30 labs/orgs) — this count is plausible (pain points are about friction, not resource volume) but worth double-checking against `music-computing-pain-points`' own tracker if Luciano expected more surfaced problems from a concept this broad.
