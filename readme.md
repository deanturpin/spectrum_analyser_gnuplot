[![Build Status](https://travis-ci.org/deanturpin/spectrum_analyser_gnuplot.svg?branch=master)](https://travis-ci.org/deanturpin/spectrum_analyser_gnuplot)
[![codecov](https://codecov.io/gh/deanturpin/spectrum_analyser_gnuplot/branch/master/graph/badge.svg)](https://codecov.io/gh/deanturpin/spectrum_analyser_gnuplot)

A Fourier transform implementation using no third-party libraries. Written to
analyse the spectral response of my digeridoo. Listen to the [audio](recording.wav).

Samples recorded on my laptop with ```arecord```.
```bash
arecord -q -f S16_LE -c1 -r 8000 > recording.wav
```

# Baby grand piano
[![](piano.svg)](piano.svg)

# Didgeridoo
![](samples.svg)
[![](fourier.svg)](fourier.svg)

# Concert pitch
```
16.35	C0
17.32	C#0
18.35	D0
19.45	D#0
20.60	E0
21.83	F0
23.12	F#0
24.50	G0
25.96	G#0
27.50	A0
29.14	A#0
30.87	B0
32.70	C1
34.65	C#1
36.71	D1
38.89	D#1
41.20	E1
43.65	F1
46.25	F#1
49.00	G1
51.91	G#1
55.00	A1
58.27	A#1
61.74	B1
65.41	C2
69.30	C#2
73.42	D2
77.78	D#2
82.41	E2
87.31	F2
92.50	F#2
98.00	G2
103.83	G#2
110.00	A2
116.54	A#2
123.47	B2
130.81	C3
138.59	C#3
146.83	D3
155.56	D#3
164.81	E3
174.61	F3
185.00	F#3
196.00	G3
207.65	G#3
220.00	A3
233.08	A#3
246.94	B3
261.63	C4
277.18	C#4
293.66	D4
311.13	D#4
329.63	E4
349.23	F4
369.99	F#4
392.00	G4
415.30	G#4
440.00	A4
466.16	A#4
493.88	B4
523.25	C5
554.37	C#5
587.33	D5
622.25	D#5
659.25	E5
698.46	F5
739.99	F#5
783.99	G5
830.61	G#5
880.00	A5
932.33	A#5
987.77	B5
1046.50	C6
1108.73	C#6
1174.66	D6
1244.51	D#6
1318.51	E6
```
