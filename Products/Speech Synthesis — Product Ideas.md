---
concept: Speech Synthesis
top_product: Whisper-to-Voice Local Converter
build_effort: M
distribution_channel: ALS Forums / dysphonia & voice-disability patient communities
incumbency_risk: High
date_added: 2026-08-14
---

## Shortlist
1. **Whisper-to-Voice Local Converter** — a cheap, privacy-first desktop/plugin app that converts whispered or weak speech into a clear natural voice in near-real-time, for people with voice disorders (dysphonia, post-laryngectomy, ALS, vocal fatigue) who want a simple offline alternative to subscription apps. Build effort: M. Distribution: ALS Forums, dysphonia/laryngectomy patient communities, Team Gleason. Incumbency risk: High — Whispp (funded, subscription, phone-call focused) and ChatterVox (hardware amplifier) already serve this need and are trusted by an emotionally invested, safety-conscious user base; switching cost is high because users have already committed to a working solution.
2. **Gestural/chironomic real-time singing-synthesis instrument for live coders** — a MIDI/gesture-controlled vocal synth (in the spirit of Cantor Digitalis) sold as a plugin to the algorave/live-coding scene. Build effort: M. Distribution: algorave/TidalCycles community is real and active (~40 cities), but no evidence found of anyone asking for gestural vocal synthesis specifically — one source explicitly notes gestural interaction in live coding is "still in its infancy," i.e. unclaimed rather than in-demand. Incumbency risk: No incumbent found — but treated as a warning sign of phantom demand, not a green light.
3. **Productized minority/regional-language TTS voices (Basque, Galician, etc.) for local creators and small public bodies** — a commercial, easy-to-use packaging of the kind of TTS research already sitting in university labs (Aholab, GTM). Build effort: L (per-language data scarcity, model training). Distribution: No existing channel found — this audience is institutional (regional broadcasters, city councils), not a community with a forum/subreddit/Discord. Incumbency risk: Medium — Aholab and GTM already hold the relevant academic/public-sector relationships and contracts for these exact languages.

Ranked #1: **Whisper-to-Voice Local Converter.** It's the only idea backed by real, findable pain — people are actively posting in patient forums and paying for imperfect existing tools (Whispp, ChatterVox), which is stronger evidence than "a community exists" (idea #2) or "no one to ask" (idea #3). It ties idea #2 on build effort but wins on distribution-channel strength since that channel shows demonstrated buying behavior, not just presence. Its incumbency risk is genuinely high and should not be downplayed — this is a hard wedge, not a soft one.

## Build plan (top pick: Whisper-to-Voice Local Converter)
v1 scope: a Windows/Mac desktop app that reads whispered mic input and outputs a converted natural voice through a virtual audio device (so it plugs into Discord/Zoom/OBS like VB-Cable), using a single pre-set voice (either a generic natural voice or, later, the user's own banked voice). Push-to-talk activation only, local/offline processing for privacy — this is the explicit differentiator against subscription, cloud-based Whispp. Build on an existing open-source whisper/voice-conversion model rather than training from scratch (leverage published whisper-to-speech research such as the GIPSA-lab work already cited in this vault as a technical reference, adapted to an off-the-shelf voice-conversion pipeline like RVC/so-vits-svc rather than novel research).
Cut from v1: multiple voices, mobile app, cloud sync, emotional/expressive control, multi-language support. One voice, one platform, one use case.
Timeline: 3–4 weeks solo, realistic (not best-case) — most of the time goes into getting latency low enough to feel conversational and packaging the virtual-mic integration reliably across Windows/Mac, not the ML itself.
Tooling: existing open-source voice-conversion model + a thin app shell (Electron or similar) + a virtual audio driver (VB-Cable-style). No custom model training for v1.

## Distribution plan (top pick: Whisper-to-Voice Local Converter)
Primary channel: ALS Forums (message/voice banking threads) and dysphonia/laryngectomy patient communities, plus Team Gleason's resource network. This must be done carefully and transparently — these are support communities, not marketing channels, so the plan is: (1) get explicit permission from forum moderators before posting as a maker, not a stealth pitch; (2) lead with the free/cheap, offline, one-time-purchase angle as a direct contrast to Whispp's ongoing subscription — that price/privacy gap is the actual wedge, not a feature advantage; (3) reach out to a small number of speech-language pathologists (SLPs), who are the trusted gatekeepers recommending tools into these communities, rather than relying on cold posts. Honest weak point: even with a real channel, the incumbency risk is high — this only works if the local/offline/one-time-price positioning is genuinely compelling to a community that has already invested emotional and financial trust in an existing solution.

## Source concept
[[Speech Synthesis]]
