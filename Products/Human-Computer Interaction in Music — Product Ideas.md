---
concept: Human-Computer Interaction in Music
top_product: OneKnob — Macro Control Devices for Ableton Live
build_effort: S
distribution_channel: r/ableton + Ableton Forum "M4L Device Store" + Gumroad/maxforlive.com marketplace
incumbency_risk: Medium
date_added: 2026-08-14
---

## Shortlist
1. **OneKnob — Macro Control Devices for Ableton Live** — A pack of Max for Live devices that collapse complex effect/synth parameter chains (reverb+delay "space", distortion+saturation "grit", filter+resonance "sweep") into single intuitive macro knobs for non-technical producers. Build effort: S. Distribution: r/ableton, Ableton Forum "M4L Device Store" thread, Gumroad/maxforlive.com (existing sellers like akihiko-matsumoto prove the channel converts). Incumbency risk: Medium — several solo devs already sell M4L device packs on Gumroad, but the market is fragmented and buyers routinely purchase from multiple small sellers, so switching cost is Low.
2. **Accessible JUCE UI Component Kit** — A drop-in library of screen-reader- and keyboard-navigation-compliant JUCE widgets (sliders, knobs, tables) for plugin developers, addressing real, recurring complaints on the JUCE forum (sliders not following screen-reader focus, apps unnavigable when a screen reader is active, no Linux accessibility support). Build effort: M. Distribution: JUCE forum (active accessibility threads with genuine developer pain, e.g. "Accessibility (screen reader) follows tabKey KeyboardFocus - but not for Sliders"). Incumbency risk: None found — no dedicated accessible-JUCE-components product turned up; this looks like a real, underserved gap rather than phantom demand, but the buyer pool (plugin devs, not end users) is small.
3. **In-DAW Session Notes / Collab Annotation Plugin** — A lightweight plugin for capturing mix notes, lyrics, and decisions inside the DAW during remote collaboration sessions. Build effort: M. Distribution: no channel search turned up a dedicated community beyond general production forums (weak). Incumbency risk: High — "Session Notes AU" already exists on the App Store doing almost exactly this, plus Notetracks and DAW-native marker/notes features cover the same need. Ranked last: real incumbent, unclear differentiation, no evidence anyone is actively complaining about the current options.

## Build plan (top pick: OneKnob — Macro Control Devices for Ableton Live)
v1 scope: 5-6 Max for Live devices, each wrapping 2-3 stock/common Live effects behind one primary macro knob plus 1-2 secondary trim knobs (kept hidden by default to preserve simplicity). Categories: "Space" (reverb+delay), "Grit" (saturation+distortion), "Sweep" (filter+resonance+LFO rate), "Glue" (multiband compression macro), "Width" (stereo widening+chorus). Cut from v1: custom DSP, cross-DAW support (Live-only), mobile/hardware control surface integration — all deferred to a possible v2 if v1 sells.
Tooling: Max for Live (bundled with Live Suite/Standard+M4L), Max patching for the macro-mapping logic and simple UI skinning, no external DSP coding needed since it's parameter-mapping over existing devices. Packaging: .amxd files distributed as a zip, plus a short demo video per device.
Realistic timeline: 2-3 weeks solo — roughly 2-3 days per device for mapping, testing ranges, and UI polish, plus a few days for packaging, product page, and demo video.

## Distribution plan (top pick: OneKnob — Macro Control Devices for Ableton Live)
Primary channel: Gumroad storefront, modeled directly on existing solo sellers (e.g. akihiko-matsumoto's Ableton device shop) who already prove this exact format converts to real purchases.
Launch sequence: (1) post a demo video and free single device ("Space" macro) to r/ableton and the Ableton Forum M4L Device Store thread to build initial goodwill and mailing list signups; (2) list the full pack on Gumroad and on maxforlive.com's community marketplace where buyers already browse for exactly this kind of tool; (3) follow up with a short comparison/workflow video showing the macro knob replacing a multi-parameter chase, aimed at producers who complain about "too many knobs" — a framing search turned up echoed in M4L community discussion threads.
Weak point to flag honestly: the channel is real but crowded — success depends on standing out among many small M4L device sellers rather than on channel scarcity, so the free single-device giveaway is the main lever for cutting through.

## Source concept
[[Human-Computer Interaction in Music]]
