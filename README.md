# Hula Loop

Hula Loop is a browser-based tool for making seamless loops from audio and music clips, including multichannel files. It runs entirely on your device: nothing is uploaded.

**[Try Hula Loop in your browser](https://matiasharju.github.io/hulaloop/loop.html)**

## Key features
- **In and out points** on a zoomable waveform, set by dragging or with keyboard shortcuts
- **Seam crossfade** of adjustable length, either shortening the loop or keeping its length
- **Exact target length**: set a length such as 6:00 and slide the window along the source. If the target is longer than the source, the loop is repeated with the same seams
- **Loudness normalisation** to a target LUFS or peak level
- **Tempo**: from a beat count or tap tempo, optionally embedded in the exported file
- **Optional pitch-preserving stretch** to an exact target BPM
- **Export to WAV** (keeps the source's sample rate and bit depth, including multichannel/polywav) **or MP3** (320 kbps, mono or stereo, with a gapless header)
- English and Finnish interface, light and dark theme, and buttons for touch screens

## Supported files
MP3, WAV, M4A, AAC, OGG and FLAC, plus the audio track of MP4 and MOV files. What can be decoded depends on your browser.

## License
GPL-3.0-or-later, see [LICENSE](LICENSE). MP3 encoding uses LAME (via lamejs); third-party licences are listed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
