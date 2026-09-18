# Niche Shortlist — Immersive Spatial Audio (2026-08-28)

Pain Points processed: 2. This is a ranked list of which ones clear the structural
gates — not a recommendation to build any of them. Go/no-go and real-world validation
are separate, human steps.

## Top tier — research-mature, commercially open, awareness/timing barrier
None. Neither processed Pain Point clears this tier.

## Worth a look — clears some gates
None.

## Low priority — technical, distribution, regulatory barrier, strong incumbency, or research still active
- [[Competing Spatial Audio Formats Render the Same Mix Differently on Every Platform]] — causal barrier is `regulatory`: the inconsistency comes from Apple, Dolby, and other platforms each controlling proprietary rendering pipelines and choosing not to standardize. No commercial or research incumbency exists because nobody outside those platforms can actually fix the rendering layer — a beginner-buildable product has no lever here, however loud and recurring the complaints (which are real and current, including a May 2026 piece with named producer Nigel Godrich).
- [[Generic HRTFs Cause Poor Sound Localization, but Individualized HRTFs Are Too Expensive to Measure at Scale]] — causal barrier is `timing` (phone-camera + ML made single-photo HRTF personalization tractable), which would normally be a promising signal, but `commercial_incumbency: strong` closes the gate: Creative Technology (Super X-Fi, patented) and Apple (Personalized Spatial Audio on AirPods/Beats since iOS 16, 2022) have both already fully productized this exact fix. The technical/timing barrier is retired, but so is the market gap.

## Notes
- Both Pain Points under this Concept were already flagged as fully investigated in prior runs of `music-computing-pain-points` (2 linked). No zero-or-low-count mismatch to flag — the Concept and Pain Point count resolved as expected.
- No Meta_Industries (Concept, Country) → Industries → Companies tuple file exists in this vault, so `transfer_case` could not be checked against that structure for either Pain Point (recorded as "no data" rather than false-negative "no").
- Neither Pain Point has a Lab in its "Labs/companies addressing this" list, so `research_incumbency` is `none` for both under this skill's scoping rule — even though external research (e.g. the AAAI 2023 AudioEar paper) touches the same HRTF problem, it isn't linked in the vault and so wasn't used to set that tag.
