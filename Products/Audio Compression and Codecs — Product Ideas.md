---
concept: Audio Compression and Codecs
top_product: Streaming Codec Preview
build_effort: M
distribution_channel: r/WeAreTheMusicMakers, r/edmproduction, Gearspace mastering forum
incumbency_risk: Medium
date_added: 2026-08-14
---

## Shortlist
1. **Streaming Codec Preview** — a client-side tool that lets producers hear (and see, via spectrogram) exactly how their track will sound after SoundCloud/Spotify/YouTube transcode + loudness normalization, before they upload. Build effort: M. Distribution: r/WeAreTheMusicMakers, r/edmproduction, Gearspace forum (thread "Soundcloud Conversion (absolutely brutal!)" shows years of live complaints). Incumbency risk: Medium — iZotope Ozone Advanced ships a "Codec Preview" feature, but it's buried inside a ~$250+ full mastering suite most bedroom producers don't own; no lightweight standalone tool found.
2. **Fake-Lossless / Transcode Authenticity Checker** — spectral-cutoff analysis tool that flags MP3-to-FLAC transcodes and fake hi-res files. Build effort: S (well-documented FFT-cutoff technique, many open reference implementations). Distribution: r/DataHoarder, Hydrogenaudio forums. Incumbency risk: High — market is already saturated with free tools (flaccheck, Fabl, Spectro, Brizm, FakeFLac, TuneLab all found in one search); hard to differentiate or charge for something the community already gets free.
3. **Batch Audio Asset Compressor for Indie Game Devs** — a tool to pick optimal codec/bitrate per platform for game audio assets and shrink build size. Build effort: S–M. Distribution: r/gamedev, itch.io tools page exist as channels, but search turned up only generic "why compression matters" content, no live complaint threads — weak evidence of real pain. Incumbency risk: Medium — Unity, Godot, and Unreal already handle per-platform audio compression natively in their import settings, so the gap this fills is unclear (leans toward phantom demand).

## Build plan (top pick: Streaming Codec Preview)
**v1 scope:** A single-page, fully client-side web app (no server upload — this doubles as the privacy pitch to producers wary of leaking unreleased masters). User drops in a WAV/AIFF. The app runs it through ffmpeg.wasm with three preset transcode chains — SoundCloud (AAC 128k with -14 LUFS normalization), Spotify (Ogg Vorbis ~160k, -14 LUFS), YouTube (Opus 128k, -14 LUFS) — and offers an A/B toggle between original and "after upload" versions, plus a simple before/after spectrogram (wavesurfer.js or a small canvas FFT) so the user can see exactly where high end gets cut.

**Deliberately cut from v1:** no batch processing, no VST/plugin version, no mastering suggestions or auto-fix — diagnostic only, not corrective. No Apple Music/Tidal profiles at launch (add later if demand shows up).

**Tech:** ffmpeg.wasm (encode/decode round-trip, runs entirely in-browser — simplest path since it avoids building/hosting a backend and sidesteps the "will you touch my unreleased track" trust problem), a static site host (e.g., GitHub Pages/Netlify, free tier), wavesurfer.js for the waveform/spectrogram view.

**Timeline:** roughly 1.5–2 weeks solo — few days for the ffmpeg.wasm transcode pipeline and LUFS normalization via ffmpeg's loudnorm filter, a few days for the A/B player UI, remaining time for spectrogram polish and testing across the three presets.

## Distribution plan (top pick: Streaming Codec Preview)
Target the exact place the pain is already being aired, not a generic audience. Post directly into the Gearspace thread "Soundcloud Conversion (absolutely brutal!)" and similar mastering-forum threads with a working link and a concrete before/after audio clip (same 10-second loop, original vs. simulated SoundCloud AAC) so people can hear the difference in one click. Cross-post to r/WeAreTheMusicMakers and r/edmproduction with a framing like "I got tired of finding out my track sounds thin on SoundCloud only after uploading, so I built a tool that previews it before you do — runs entirely in your browser, nothing gets uploaded." Lean on the privacy angle (client-side, no server upload) as the differentiator against the Ozone Advanced feature, since that's the concrete reason someone without a $250 mastering suite would reach for this instead. Follow up in r/mixingmastering once there's a working demo link to point to.

## Source concept
[[Audio Compression and Codecs]]
