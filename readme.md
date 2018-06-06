[![Build Status](https://travis-ci.org/deanturpin/spectrum_analyser_gnuplot.svg?branch=master)](https://travis-ci.org/deanturpin/spectrum_analyser_gnuplot)
[![codecov](https://codecov.io/gh/deanturpin/spectrum_analyser_gnuplot/branch/master/graph/badge.svg)](https://codecov.io/gh/deanturpin/spectrum_analyser_gnuplot)

A Fourier transform implementation using no third-party libraries. Written to
analyse the spectral response of my digeridoo. Listen to the [audio](recording.wav).

Samples recorded on my laptop with ```arecord```.
```bash
arecord -q -f S16_LE -c1 -r 8000 > recording.wav
```

See the [pitch details](pitch.md).

---

Wed  6 Jun 18:17:03 BST 2018
# didgeridoo_big_tony.wav
Listen to the [audio](wav/didgeridoo_big_tony.wav).
[![](didgeridoo_big_tony.svg)](didgeridoo_big_tony.svg)
# major7.wav
Listen to the [audio](wav/major7.wav).
[![](major7.svg)](major7.svg)
# major_chord.wav
Listen to the [audio](wav/major_chord.wav).
[![](major_chord.svg)](major_chord.svg)
