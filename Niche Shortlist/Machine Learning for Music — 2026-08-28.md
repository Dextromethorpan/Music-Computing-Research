# Niche Shortlist — Machine Learning for Music (2026-08-28)

Pain Points processed: 3. This is a ranked list of which ones clear the structural
gates — not a recommendation to build any of them. Go/no-go and real-world validation
are separate, human steps.

## Top tier — research-mature, commercially open, awareness/timing barrier
- [[Widely-Used Genre Classification Benchmarks Are Known to Be Flawed, Yet Still Used to Validate New Models]] — causal_barrier=awareness (flaws were known and published for over a decade, yet the field kept using GTZAN as-is: 45% of 560 surveyed MGR papers 2013-2022 per a 2025 follow-up survey), research_incumbency=mature (Sturm's fault-filtered splits and their reproductions on GitHub already retired the hard part — identifying and filtering the bad examples), commercial_incumbency=none, clustering=true (Germany + Spain labs independently corroborate), non-stale 2025 demand evidence present.

## Worth a look — clears some gates
- [[Streaming Platforms Use ML Recommendation Systems to Quietly Replace Human Artists with Cheaper Stock Music]] — commercial and research incumbency both none, and demand evidence is unusually strong and recent (three separate 2025 trade-press pieces, artist boycotts). But causal_barrier=distribution: the affected party (individual musicians losing playlist placement) has no obvious channel to organize around or pay for a fix, and the platform holding the chokepoint (Spotify) has no incentive to change — so "no competitors" here likely reflects "no reachable buyer," not "wide open."

## Low priority — technical or distribution barrier, or research still active
- [[AI Mastering Tools Produce a Generic, One-Size-Fits-All Sound That Struggles Outside Electronic Music]] — causal_barrier=technical: the genre-flattening effect is attributed to the black-box model architecture itself, not to a gap in awareness or a recent enabling shift. No incumbency on either side, but the barrier itself is the disqualifier per the skill's ranking logic.

## Notes

- The top-tier item is a genuine structural niche match on paper, but flag for Luciano: the "research-mature, unproductized" gap here is a dataset/evaluation-methodology fix consumed almost entirely by other researchers, not a distinct commercial buyer — worth sanity-checking against real willingness-to-pay before spending validation time, since the demand evidence found is entirely academic-mention type (no forum, GitHub-issue, or ProductHunt signal of a paying user for a "fixed benchmark" product).
- The "Streaming Platforms... PFC" pain point has the loudest, most recent public demand signal of the three (Harper's, 34th Street, Leaf&Core, artist boycotts through late 2025) but structurally is the hardest to build a beginner product against — any fix competes directly with Spotify's own curation, which is a distribution problem, not a technical one.
- transfer_case is "no data" for all three (per the vault's known gap: no Meta_Industries tuple file exists yet) rather than a real false — don't read the `false` value as a checked-and-negative result.
- All three Pain Points overlap with [[AI Music Generation]] and [[Neural Networks for Audio]] as expected; only the GTZAN pain point showed genuine cross-Country clustering (Germany + Spain) at the org level.
