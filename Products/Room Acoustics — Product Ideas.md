---
concept: Room Acoustics
top_product: Game-Ready Room Impulse Response Packs
build_effort: S
distribution_channel: itch.io (game-assets, audio/game-audio tags) + r/GameAudio
incumbency_risk: Medium
date_added: 2026-08-14
---

## Shortlist
1. **Game-Ready Room Impulse Response Packs** — Curated, metadata-tagged real-space IR packs pre-formatted and documented for drop-in use in Unreal Convolution Reverb, Wwise Convolution Reverb, and FMOD (not just generic WAV dumps). Build effort: S. Distribution: itch.io audio/game-audio tagged marketplace (active buyer base of indie devs), r/GameAudio subreddit, Wwise/Unreal audio forums. Incumbency risk: Medium — generic IR pack sellers exist (A Sound Effect, Cupwise, 3 Sigma Audio) but none package specifically for game-engine convolution reverb workflows with per-engine import docs, so switching cost is moderate, not high.
2. **Podcaster/Streamer Room Dereverb Tool** — Software that removes room echo/reverb from voice recordings for home podcasters. Build effort: L (ML dereverb is technically hard to do well). Distribution: r/podcasting, r/audiodrama, Adobe Audition/Descript forums — real complaint threads found ("dereverb software adds nasty artifacts," "physical treatment beats software"). Incumbency risk: High — Adobe Podcast Enhance (free, AI-based) and iZotope RX De-reverb already dominate this exact need; community consensus is software solutions are inherently weak here, and the free incumbent is very strong.
3. **Room Mode / Bass Trap Placement Calculator** — Web app to calculate room modes and bass trap placement for home studios. Build effort: S. Distribution: r/audioengineering, GearSpace acoustics forum. Incumbency risk: High — at least 6-8 free calculators already exist (HOFA-Akustik, AudioCalcs, Patchify, Applied Calculator, etc.), no evidence anyone is paying for this or complaining the free tools are insufficient — likely phantom demand for a paid version.

Ranked #1: **Game-Ready Room Impulse Response Packs.** Lowest realistic build effort (record + package, no ML/DSP R&D), the only idea with a distribution channel that is both real AND has demonstrated willingness to pay (itch.io audio-tagged asset sales), and the only idea where incumbency risk is medium rather than high (a packaging/workflow gap in an otherwise served market, not "another room correction tool" or "another free calculator").

## Build plan (top pick: Game-Ready Room Impulse Response Packs)
- **v1 scope**: One pack of ~30 real-world sine-sweep-captured IRs from varied everyday spaces (stairwells, parking garage, tiled bathroom, small office, corridor, church/hall if accessible) — variety is the selling point, not exotic locations. Capture with a decent condenser mic + free sine-sweep/deconvolution tooling (e.g., Aurora plugin or REW), process to 48kHz WAV, normalize levels, tag each file with metadata (room type, approximate RT60, dimensions if known).
- **Packaging**: Ship as three format-ready folders — raw WAV (DAW/generic use), Unreal Convolution Reverb-ready asset with import readme, Wwise Convolution Reverb-ready asset with import readme. FMOD compatibility noted since it just needs WAV. This per-engine readme is the actual differentiator vs. generic IR sellers.
- **Cut from v1**: No custom plugin, no live capture service, no continuous/subscription model, no outdoor/urban expansion pack yet (save for v2 if v1 sells).
- **Timeline**: 1-2 weeks solo — a few days of location scouting/recording, 2-3 days processing/tagging, 2-3 days packaging + writing per-engine docs + store page.
- **Tooling**: Portable recorder or interface + mic already needed for this kind of work; free sweep/deconvolution software; itch.io as storefront (zero-cost, handles payments/downloads); Gumroad as a mirror.

## Distribution plan (top pick: Game-Ready Room Impulse Response Packs)
- **Primary channel**: itch.io, listed under the "audio"/"game-audio" asset tags where indie devs already browse and buy sound packs. Price competitively against existing generic IR packs ($10-$20) but lead the store page with the engine-specific readme/screenshots as the hook ("drop straight into Wwise/Unreal, no fiddling").
- **Secondary channel**: r/GameAudio — post as a genuine resource/announcement (check subreddit self-promo rules first; many audio subreddits allow one linked post if framed as a release, not spam), including a free sample IR to build trust before asking for a purchase.
- **Tertiary**: Audiokinetic Wwise Q&A and Unreal Engine audio forum threads where people ask "where do I get IRs for convolution reverb" — answer genuinely, link the pack only where relevant and allowed.
- **Weak point to watch**: no evidence yet of dedicated buyer volume specifically for game-engine-packaged IRs (only evidence is that generic IR packs sell and r/GameAudio + itch.io audio tags are active) — this is an inferred niche within a proven adjacent market, not a channel with confirmed demand for this exact packaging. Treat the first pack as a demand test, not a guaranteed win.

## Source concept
[[Room Acoustics]]
