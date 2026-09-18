---
pain_point: Music Production Software Remains Largely Inaccessible to Blind and Visually-Impaired Musicians
addressed: Yes
date_first_seen: 2026-08-14
tags: [pain-points-color/violet]
causal_barrier: distribution
clustering: true
commercial_incumbency: none
research_incumbency: active
transfer_case: false
lab_transfer_candidate: false
confidence: provisional
niche_verified: 2026-08-28
---

Most DAWs, plugin UIs, and music-making software are built as dense, highly visual interfaces (knobs, faders, drag-and-drop routing) with little thought given to screen-reader compatibility or non-visual navigation. This effectively locks blind and visually-impaired musicians and producers out of most of the ecosystem — not because the underlying audio tasks are inherently visual, but because almost nobody designs the interface layer to work without sight.

## Evidence
Multiple real, recurring threads on the JUCE developer forum (the framework underlying a large share of commercial plugins) document this directly: a blind musician from Paris describing the accessibility barriers of plugin UIs, screen-reader users on the "JUCE Accessibility on develop" thread discussing workarounds like routing screen-reader audio through a separate speaker just to use a DAW at all, and a totally blind UK electronic-music producer publicly asking developers to build an accessible MIDI step sequencer because none existed. Pro Tools is repeatedly cited as the rare exception — Avid specifically built VoiceOver support for blind users on macOS — which is itself evidence of how unusual real accessibility support is in this space; a parallel GitHub issue on the open-source Surge XT synth ("Use JUCE Accessibility branch to bring reasonable accessibility to Surge XT") shows developers treating this as a still-unresolved, active feature request rather than a solved problem.

## Surfaced in
- [[Human-Computer Interaction in Music]]

## Labs/companies addressing this
- [[Denmark/Labs/Sound and Music Computing & Multisensory Experience Lab (AAU Copenhagen)/Lab|Sound and Music Computing & Multisensory Experience Lab (AAU Copenhagen)]] — "MusiCane," an accessible digital instrument explicitly designed around the white cane for blind and visually-impaired musicians.
- [[Canada/Labs/Input Devices and Music Interaction Lab (IDMIL)/Lab|Input Devices and Music Interaction Lab (IDMIL)]] — "Accessible Digital Musical Instruments Through the Lens of Disability Models" directly researches accessible instrument design frameworks.

## Niche Verification (2026-08-28)

**Causal barrier:** distribution — the technical building blocks already exist (JUCE ships an Accessibility API/branch, and Avid built full VoiceOver support into Pro Tools), so this is not primarily an unsolved technical problem. What's missing is smaller plugin/DAW vendors prioritizing integration work for a niche audience they have little commercial incentive to reach — a classic distribution/adoption gap, not a research gap.
**Clustering:** true — the two linked labs (Sound and Music Computing & Multisensory Experience Lab, Denmark and IDMIL, Canada) span two countries, even though this Pain Point currently surfaces under only one Concept ([[Human-Computer Interaction in Music]]).
**Incumbency:** commercial=none, research=active
**Transfer case:** no data — no Meta_Industries (Concept, Country) -> Industries -> Companies tuple file exists in this vault to check against.
**Lab transfer candidate:** no — both linked labs' resources (MusiCane, and the Disability Models paper) address building new accessible instruments/frameworks for blind or d/Deaf musicians, not the actual described friction (screen-reader/non-visual accessibility of existing DAW and plugin UIs). Neither is a directly productizable fix for that specific gap, so this is marked as tangential rather than a lab-transfer candidate.

### Demand evidence
- [JUCE Accessibility on develop](https://forum.juce.com/t/juce-accessibility-on-develop/45142) (2021-2022, JUCE developer forum, recurring-complaint, stale) — plugin developers and screen-reader users discussing how to bring accessibility support into JUCE-based plugin UIs, including workarounds like routing screen-reader audio through a separate output.
- [Reaching out to developers regarding accessible MIDI sequencer app for blind musicians](https://forum.loopypro.com/discussion/47719/reaching-out-to-developers-regarding-accessable-midi-seequencer-app-for-blind-musicians) (November 2021, Loopy Pro forum, explicit-willingness-to-pay/single-complaint, stale) — a totally blind UK electronic-music producer directly asking developers to build an accessible MIDI step sequencer app because none exists.
- [Use JUCE Accessibility branch to bring reasonable accessibility to Surge XT 1.0](https://github.com/surge-synthesizer/surge/issues/4616) (opened May 2021, closed, GitHub, existing-failed-attempt turned partial-success, stale) — tracks the open-source Surge XT synth's effort to adopt JUCE's accessibility branch; Surge XT has since shipped a dedicated accessibility feature set (see https://surge-synthesizer.github.io/accessibility/), showing at least one free/open-source product has proven the fix is buildable, while most commercial plugin vendors still have not followed.
- Note on external context (not used to set the formal incumbency tags above, which follow this Pain Point note's own linked-orgs list): a 2025 assistive-technology listicle (braillemusicandmore.com) claims a "fully voice-operated" DAW called "SoundSpeak Studio" exists, but a targeted search found no independent trace of this product — it appears to be unreliable/fabricated content and was excluded from the evidence list above rather than cited as real demand or incumbency.
