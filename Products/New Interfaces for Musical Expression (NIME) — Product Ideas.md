---
concept: New Interfaces for Musical Expression (NIME)
top_product: Custom Controller Firmware & Patch Toolkit
build_effort: S
distribution_channel: r/synthdiy, lines (llllllll.co), Bela forum
incumbency_risk: Medium
date_added: 2026-08-14
---

## Shortlist
1. **Custom Controller Firmware & Patch Toolkit** — a curated, tested bundle of Arduino/Teensy firmware templates + matching Pd/Max patches for turning sensors (pressure, ribbon, capacitive touch) into expressive MIDI controllers, with the calibration/smoothing code that scattered free tutorials skip. Build effort: S. Distribution: r/synthdiy, lines (llllllll.co), Bela forum — all real, active hobbyist communities confirmed by search. Incumbency risk: Medium — plenty of free GitHub libraries (tttapa/MIDI_controller, teensyMIDItoolkit) and tutorials (DJ TechTools, Instructables) already serve this need; no curated paid product found, but people may balk at paying when free (if scattered/lower-quality) options exist.
2. **No-code sensor-to-MIDI/OSC mapping app** — a modern, easier alternative to Bome MIDI Translator Pro for mapping custom sensor rigs to MIDI/OSC. Build effort: L (cross-platform app, device drivers, GUI). Distribution: same forums (r/synthdiy, Bela forum, lines). Incumbency risk: High — Bome MIDI Translator Pro is entrenched and commercial, plus free alternatives exist (MIDI-OX, Mididash, libmapper). No evidence found of people complaining about a gap here — likely phantom demand.
3. **Tangible/tabletop DIY instrument kit** (reacTable-style) — a hobbyist kit (fiducial markers + camera + software) for building a tabletop tangible instrument. Build effort: L (hardware sourcing, computer-vision setup, physical kit logistics). Distribution: No existing hobbyist-market channel found — Tangible Music Lab and NIME papers are academic, not a buyer community. Incumbency risk: High — reacTIVision (the underlying tracking software) is already free and open-source, and reacTable itself is a commercial product; phantom demand risk is high since no one was found complaining about a gap.

## Build plan (top pick: Custom Controller Firmware & Patch Toolkit)
v1 scope: three fully-documented example builds — (1) breath/pressure controller for continuous CC and aftertouch, (2) light/ribbon sensor for pitch-bend-style continuous control, (3) capacitive touch pad for velocity-sensitive triggering. Each ships as an Arduino/Teensy sketch, a matching Pd patch and a matching Max patch, a wiring diagram, and the calibration/jitter-smoothing code that most free tutorials leave out (this is the specific gap: raw analog sensor tutorials exist everywhere, but working hysteresis/smoothing code that avoids "expression fights back" jitter is scarce). Sold as a single PDF + code-repo bundle via Gumroad, $15–25.

Cut from v1: no companion mobile/desktop app, no video course, no physical hardware kit or shipping (pure digital product to avoid inventory and manufacturing risk).

Tooling: GitHub repo for code, a single Gumroad product page, one demo video per build posted to YouTube. No custom site needed.

Timeline: 1–2 weeks solo — most of the technique is already known/tested from existing open-source examples; the work is curating, testing the smoothing/calibration layer end-to-end, and writing it up cleanly.

## Distribution plan (top pick: Custom Controller Firmware & Patch Toolkit)
Lead with genuine build content, not an ad. Post a real build log (e.g., the breath controller) as a normal contribution to r/synthdiy and to the Bela forum, where the calibration/smoothing pain point is a known recurring struggle; link to the full toolkit only in the writeup, not as a headline pitch. Do the same as a thread in lines (llllllll.co) under the relevant controllers/hardware category. Post the accompanying demo videos to YouTube tagged into the existing synth-DIY video niche (DJ TechTools, Instructables-style search terms) so they surface next to the free tutorials people already watch.

Honest weak point: these are enthusiast communities that strongly favor free/open resources and are quick to bristle at self-promotion — conversion is likely to be lower than a typical niche audience because the median member expects to build this themselves for free. The toolkit has to visibly save real time (working smoothing code, tested wiring) to justify a purchase rather than just being "a paywall on stuff already on GitHub."

## Source concept
[[New Interfaces for Musical Expression (NIME)]]
