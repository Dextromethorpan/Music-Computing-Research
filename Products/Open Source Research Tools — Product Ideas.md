---
concept: Open Source Research Tools
top_product: PD Doctor (Pure Data externals installer/repair tool)
build_effort: S
distribution_channel: PD Patch Repo forum (forum.pdpatchrepo.info)
incumbency_risk: Low
date_added: 2026-08-14
---

## Shortlist
1. **PD Doctor** — a small diagnostic/repair GUI for Pure Data that scans a user's install, finds why an external won't load (wrong path, architecture mismatch, broken Deken download, missing sub-folder registration), and fixes it in one click. Build effort: S. Distribution: PD Patch Repo forum (forum.pdpatchrepo.info). Incumbency risk: Low — Deken (Pd's built-in package manager, free, bundled since Pd 0.47) is the closest thing to an incumbent, but multi-year forum threads ("could not create external," "extremely frustrating," path confusion) show it still leaves users stuck; a repair tool complements rather than replaces it, so switching cost is close to zero.

2. **UVR-style stem separation desktop app built on Basic Pitch/Demucs/madmom** — a polished GUI wrapper around the open-source models cited in this concept (Basic Pitch, madmom) for vocal/stem isolation and note transcription. Build effort: M-L (cross-platform packaging, GPU/ONNX bundling, model licensing). Distribution: broad but crowded — r/WeAreTheMusicMakers, r/edmproduction style audiences exist but are already saturated by name-brand tools. Incumbency risk: High — Ultimate Vocal Remover (UVR) is itself free, open-source, runs Demucs/MDX-Net locally, and is already the community-trusted default; Moises (70M+ users), LALAL.AI, and RipX DAW cover the paid tier. No gap here — this is the textbook "incumbent already solved it for free" case.

3. **MIR open-source tools directory/newsletter** (curating things like Essentia, madmom, Marsyas, jMIR, etc. for researchers/developers) — Build effort: S. Distribution: No existing channel found beyond ISMIR's own resource pages and academic mailing lists, which already catalog this exact material for free and don't skew toward paying audiences. Incumbency risk: None found, but absence of any commercial incumbent here reads as absence of demand, not opportunity — nobody in the searches was found complaining about a lack of a directory. Treated as likely phantom demand.

## Build plan (top pick: PD Doctor)
**v1 scope:** a standalone diagnostic tool (not a Pd patch, so it can run and repair Pd even when Pd itself is misconfigured) that:
- Detects OS, Pd version/flavor (vanilla vs Purr Data vs Plugdata), and architecture (x86/arm).
- Scans the externals/search-path folders Deken installs into, flags mismatched-architecture binaries, missing sub-folder path registration, and broken/partial Deken downloads.
- One-click fixes for the top 3-4 recurring forum complaints (add missing search paths, re-register sub-folders, redownload a corrupted package via Deken's own index, reset permissions).
- Plain-English report of what's wrong even when it can't auto-fix, so it doubles as a triage tool people can screenshot into forum posts.

**Deliberately cut from v1:** GUI theming beyond functional, Linux distro-specific packaging edge cases, support for hand-built/non-Deken externals, any attempt to replace Deken's install flow itself.

**Timeline:** 3-5 days solo. This is a filesystem/path-inspection script with a thin UI, not a new audio engine — the domain knowledge (from the forum threads) is the hard part and it's already gathered.

**Tooling:** Python + Tkinter (or a plain Tcl/Tk script, matching Pd's own GUI toolkit so it feels native and stays a single small executable) — no need for Electron/web-stack overhead for a tool this scoped. Package with PyInstaller for Win/Mac/Linux single-file binaries.

## Distribution plan (top pick: PD Doctor)
Post a working build directly in the PD Patch Repo forum (forum.pdpatchrepo.info), specifically as a reply/new thread in the "installing externals" problem threads already found (e.g. "Can't install external libraries," "Unable to install externals on Windows 10," "installing external libraries") — these are exact, dated instances of the target user hitting the exact problem the tool solves, so the pitch is "here's a tool that fixes the thing you just described" rather than a cold post. Cross-post once to the Pd mailing list (lists.puredata.info) and the Facebook "Pure Data" group with a short screen recording of a broken install being diagnosed and fixed in under a minute. Free to start (community goodwill first, since this is a hobbyist forum, not a buyer's market) — monetization, if any, is a "buy me a coffee" or a $5-10 "Pro" version bundling deeper diagnostics for Plugdata/embedded Pd users; do not expect meaningful recurring revenue from this channel, the audience is small and largely non-commercial.

## Source concept
[[Open Source Research Tools]]
