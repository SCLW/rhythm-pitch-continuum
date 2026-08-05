# Rhythm–Pitch Continuum

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Demonstration 1 from the lecture **Conlon Nancarrow** — *Sound (Art & Technology)*, HfG Karlsruhe.

Two click trains at rates *f* and *f·r*. At 2 Hz the ratio *r* is a polyrhythm you can count; accelerated into the audible range, the same two trains fuse into two pitches, and *r* becomes the musical interval. One number, one continuum — after Henry Cowell, *New Musical Resources* (1930), pp. 50–51, and the road into Nancarrow's tempo canons.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/img/rhythm-ratios-dark.svg">
  <img alt="Four ratios shown as paired pulse trains: 3:2 and 5:4 meet again after 2 and 4 beats; √2:1 and π:e share one downbeat and never meet again" src="assets/img/rhythm-ratios-light.svg">
</picture>

*Coincidence dots mark the two trains striking together. The just ratios come home every q beats; the irrational ones come arbitrarily close, forever, and never arrive.*

## The patch

`patch/demo1-rhythm-intervals.maxpat`

Requires [Max](https://cycling74.com/downloads) 8 or later — **Max is free to download, and patches run without a license** (only saving requires one). Core objects only, no externals.

1. Start the audio (speaker icon).
2. Click a ratio.
3. Drag **base frequency / speed** — at 2 Hz you hear two click trains; above ~30 Hz they fuse into two pitches.

Selecting a ratio restarts both trains on a shared downbeat. The **meeting lamp** blinks whenever the trains genuinely strike together — and stays dark, by construction, after an irrational choice: one flash at the downbeat, then never again. The readouts show the calculated second frequency, both click periods, and the reciprocal 1/r.

## The ratios

Seven just intervals, ordered by how soon the trains meet again — perfect fifth 3:2 (every 2 beats), perfect fourth 4:3, major sixth 5:3, major third 5:4 (Study No. 14, tempi 88:110), minor third 6:5, major second 9:8, major seventh 15:8 — and the constants of Nancarrow's late canons: **√2**, the equal-tempered tritone (Study No. 33), and **π/e** (Study No. 40a, Gann's "Canon e/π" — the reciprocal display shows his 0.8653 when selected), with **e** and **π** individually: each alone is just a wide interval; it is their *ratio* that becomes the canon.

## The figure

`assets/img/rhythm-ratios-{light,dark}.svg` — the illustration from the lecture slides, with Schibsted Grotesk embedded; the light/dark pair follows the repository's color scheme automatically.

## Literature

- Henry Cowell, *New Musical Resources*, New York 1930 (the rhythm–pitch identity: pp. 50–51).
- Kyle Gann, *The Music of Conlon Nancarrow*, Cambridge University Press 1995 (Study No. 40, "Canon e/π": p. 200).

## Links

- Course and slides: [teaching.medienkunst-sound.de](https://teaching.medienkunst-sound.de/)

## License

[Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) — © 2026 Lorenz Schwarz, HfG Karlsruhe. Attribution required for all reuse; see [LICENSE](LICENSE).
