# Rhythm–Pitch Continuum

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

A Max/MSP demonstration of Henry Cowell's **rhythm–pitch continuum**, created as part of the lecture on Conlon Nancarrow.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/img/rhythm-ratios-dark.svg">
  <img alt="Four ratios as paired pulse trains: 3:2 and 5:4 meet again after 2 and 4 beats; √2:1 and π:e share one downbeat and never coincide again" src="assets/img/rhythm-ratios-light.svg">
</picture>

Two hard-panned click trains with repetition rates in a ratio *r* produce rhythmic structures at approximately **2 Hz**. When accelerated into the audible range, the same frequency relationship is perceived as a musical interval, illustrating Henry Cowell's concept from *New Musical Resources* (1930).

For rational ratios, the pulse trains coincide again after a finite number of beats (e.g. **3:2**, **5:4**). Irrational ratios, such as **√2:1** and **π:e**, share only the initial downbeat and never coincide again.

**Max patch:** [`patch/demo1-rhythm-intervals.maxpat`](patch/demo1-rhythm-intervals.maxpat), built with core objects only (no version-specific features, tested in Max 9). [Max](https://cycling74.com/downloads) is free to download and runs patches without a license. Start the audio, click a ratio, drag the speed.

**Slides:** [Conlon Nancarrow, Sound (Art & Technology)](https://teaching.medienkunst-sound.de/sound_art_and_technology/conlon_nancarrow/), HfG Karlsruhe.

**License:** [CC BY 4.0](LICENSE) | © 2026 Lorenz Schwarz, HfG Karlsruhe.
