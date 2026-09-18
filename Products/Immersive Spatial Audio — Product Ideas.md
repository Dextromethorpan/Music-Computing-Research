---
concept: Immersive Spatial Audio
top_product: Voice Stage (spatial character staging tool for audio drama producers)
build_effort: M
distribution_channel: r/audiodramaproduction / Audio Drama Hub Discord
incumbency_risk: Low
date_added: 2026-08-14
---

## Shortlist

1. **Voice Stage** — a browser tool where audio-drama producers drag character icons around a 2D "stage" and a timeline, and it renders a proper binaural mix (via the browser's built-in HRTF panner) instead of hand-automating pan envelopes per character per scene. Build effort: M. Distribution: r/audiodramaproduction (active creator-to-creator subreddit) + Audio Drama Hub Discord. Incumbency risk: Low — existing tools (dearVR Micro, Waves NX) are single-source generic panners, not multi-character staging tools; Facebook's free FB360 Spatial Workstation (the closest prior tool) is discontinued; a February-2026 arXiv paper ("Dramarrator: Object-Based Audio Editing for Audio Drama Production from Books") independently confirms researchers see this as an open gap, not a solved problem.

2. **8D Audio Maker (web app)** — upload a song/track, drag it into a circling binaural pan, download the result. Build effort: S (trivial with Web Audio's HRTF panner). Distribution: huge diffuse YouTube "8D audio" audience, but no single channel to target as a builder — no subreddit or Discord hub found, just search traffic. Incumbency risk: High — Audioalter, Audjust, AudioUtils, and SoundTools already offer this exact feature free, in-browser, today. No complaints found anywhere about these being inadequate; looks like phantom demand for a "better" version.

3. **Binaural panner for ASMR/podcast creators** — a friendlier, cheaper binaural spatializer plugin/app aimed at ASMR and podcast editors. Build effort: S/M. Distribution: r/asmr and ASMR creator communities exist and are real. Incumbency risk: High — dearVR MICRO is free, Sennheiser-backed, and explicitly recommended in ASMR production guides already; no one is found complaining that it's insufficient or too expensive (it's free), so there's no visible gap to build into.

## Build plan (top pick: Voice Stage)

**Scope for v1:**
- Single-page browser app, no backend, no account system.
- Import multiple audio stems (one file per character/sound source).
- 2D top-down "stage" canvas: drag a marker per character to set its position around the listener.
- Timeline with simple keyframes: set a character's position at time X, position Y at time X+n, linear interpolation between them (covers "character walks across the room" and "character enters from off-mic").
- Live preview through headphones using the browser's native `PannerNode` with `panningModel: 'HRTF'` (a standard Web Audio feature — no custom HRTF/convolution code needed).
- Offline render/export to a single binaural stereo WAV via `OfflineAudioContext`, ready to drop into the rest of the episode edit.

**Deliberately cut from v1:** any real plugin format (VST/AU) — ship as a web app only; room acoustics/reverb modeling; ambisonics/multichannel export; cloud collaboration or multi-user editing; any AI/NLP script-to-blocking automation (the "Dramarrator" research direction) — v1 is manual drag-and-keyframe only, which is already a large improvement over hand-automating pan curves in a DAW.

**Timeline (solo, realistic):** ~2-3 weeks.
- Week 1: canvas UI + PannerNode wiring + basic keyframe automation.
- Week 2: multi-stem import/mixing, offline render/export, drag-UX polish.
- Week 3 (buffer): test against real audio-drama scene files on headphones, fix rough edges, build a one-page landing site with the demo embedded.

**Tooling:** plain TypeScript + native Web Audio API (the HRTF panner is built into Chrome/Firefox/Safari — this is the whole reason a browser app is the easiest path here, not a native/plugin one). Optionally Tone.js to speed up timeline scheduling. Static hosting (Netlify/Vercel free tier), no server, no ML.

## Distribution plan (top pick: Voice Stage)

Target audience is small but concentrated and directly reachable — no need for broad marketing:

- Produce one short demo: a 3-character audio-drama scene, before/after (flat stereo vs. Voice Stage output), so the improvement is audible in 30 seconds.
- Post the demo directly in **r/audiodramaproduction**, framed around the specific pain point ("stopped hand-automating pan per line for multi-character scenes — built this instead"), with a free link to try it.
- Share it in the **Audio Drama Hub Discord** (the most active real-time community for this niche, per creators writing about the space) in its tools/resources channel.
- Reach out individually to **Tal Minear**, who has written publicly about both Discord-based audio drama production and free tools used in the space — a known, reachable voice in this exact community, worth a direct message for feedback and possible word-of-mouth.
- Contact **AudioDramaProduction.com** (runs an audio-effects/processing glossary aimed at this same audience) about a tool listing or guest mention.
- No paid ads: the community is small enough that direct, specific outreach should outperform broad spend, and this also avoids sinking budget into an unproven niche.

## Source concept
[[Immersive Spatial Audio]]
