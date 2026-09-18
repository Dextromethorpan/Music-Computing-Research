---
title: The Art of VA Filter Design
org: Native Instruments
org_type: Company
country: Germany
type: paper
authors: Vadim Zavalishin
year: 2020 (rev. 2.1.2)
url: https://www.native-instruments.com/fileadmin/ni_media/downloads/pdf/VAFilterDesign_2.1.2.pdf
date_added: 2026-08-09
---

This free book, written by Native Instruments DSP engineer Vadim Zavalishin and hosted on the company's own site, is one of the most widely cited technical references in software synthesizer design. "VA" stands for virtual analog: making a piece of software (a filter, which shapes which frequencies of a sound pass through or get cut) behave like a real analog circuit — including its warmth and slight instabilities — rather than sounding "sterile" the way naive digital filters often do. The book covers the underlying math (starting from Fourier theory, a way of describing any sound as a mix of simple wave frequencies) and works up to practical, implementable designs used in real synthesizers and effects plugins. It grew out of Zavalishin's work building Reaktor's "Core" DSP engine at Native Instruments and is used as a standard teaching reference across the audio DSP community, well beyond NI's own products.

## Concepts
- [[True Analog Emulation (TAE)]]
- [[Signal Processing]]
