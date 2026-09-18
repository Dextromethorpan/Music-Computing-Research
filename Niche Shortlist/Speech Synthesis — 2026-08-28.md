# Niche Shortlist — Speech Synthesis (2026-08-28)

Pain Points processed: 2. This is a ranked list of which ones clear the structural
gates — not a recommendation to build any of them. Go/no-go and real-world validation
are separate, human steps.

## Top tier — research-mature, commercially open, awareness/timing barrier
(none)

## Worth a look — clears some gates
- [[Text-to-Speech Quality Collapses for Any Language Outside the Top 20-30 Best-Resourced Ones]] — research_incumbency is `mature` (Aholab has a working, unproductized TTS stack for Basque, a concrete lab-transfer candidate) and commercial_incumbency is `none`, but causal_barrier is `technical` (per-language data scarcity + real ML/DSP expertise needed), so per the skill's ranking rule a technical barrier keeps it out of top tier regardless of how open the research/commercial gates look. Worth a look specifically for the lab-transfer angle (AhoMyTTS/Basque databases), not as an easy beginner build.

## Low priority — technical or distribution barrier, or research still active
- [[Voice Cloning Has Crossed the Threshold Where Scam Calls Are Indistinguishable From a Real Loved One]] — causal_barrier is `technical` (reliable real-time clone detection or carrier-level call authentication is genuinely hard engineering, not just an awareness gap), and both commercial_incumbency and research_incumbency are `none` per the Pain Point's own linked-orgs list (which is empty). No clustering (single concept, no linked orgs/countries). Demand evidence is strong and recurring, but the structural gate on causal barrier keeps this low priority.

## Notes
- Of the three Pain Point notes whose text mentions "Speech Synthesis," only two actually carry a `[[Speech Synthesis]]` link under `## Surfaced in`. The third — [[Neural Networks for Audio's Pain Point: Neural Voice Cloning Enables Unauthorized Use of a Performer's Voice]] (file: "Neural Voice Cloning Enables Unauthorized Use of a Performer's Voice.md") — surfaces under `[[Neural Networks for Audio]]` instead; it only matched the text search because its linked-orgs list mentions "Aalto University - Speech Synthesis Research Group." It was correctly excluded from this run and was left untouched (it already carries its own `niche_verified: 2026-08-28` from a separate run against its actual concept).
- Neither processed Pain Point reached top tier this round — the Speech Synthesis concept currently has no Pain Point combining `research_incumbency: mature` (or strong clustering) with an `awareness`/`timing` barrier. The TTS-low-resource-language Pain Point is the closer of the two: its blocker is real (data + engineering cost per language), but the Aholab Basque work is a concrete, linkable existing method that a beginner-adjacent builder could study or extend rather than invent from scratch — worth flagging to Luciano as the more promising of the two for a closer look, even though it doesn't clear the top-tier bar as defined.
- The scam-call Pain Point has some of the strongest, most recent, most independently-corroborated demand evidence found in this run (multiple unrelated 2026 publishers converging on the same "no real fix, only a family safe-word" advice) — but per the causal-barrier rule this alone cannot lift it out of low priority; a real technical fix here would need call-analysis infrastructure or telecom-level integration, out of scope for an easy beginner build.
