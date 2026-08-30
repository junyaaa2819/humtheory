# HumTheory

> Hear. Analyze. Understand. Create.

[Website](https://humtheory.net) · [Latest Release](https://github.com/junyaaa2819/humtheory/releases/tag/latest)

HumTheory is a desktop music analysis and composition tool for musicians who want to turn sounds and musical ideas into something they can actually work with.

Hum a melody. Play a chord. Drop in a song. HumTheory helps turn that into notes, chords, keys, scales, progressions, and MIDI.

**HumTheory 0.1b is currently in beta.** Some features are still being worked on, and analysis results can be inaccurate depending on the audio.

---

## What is HumTheory?

HumTheory is built around a simple idea:

```text
HEAR
  ↓
ANALYZE
  ↓
UNDERSTAND
  ↓
CREATE
  ↓
EXPORT
```

Use it to:

- turn humming or singing into MIDI
- detect musical notes in real time
- identify chords and keys
- analyze songs and chord progressions
- generate chord progressions
- experiment with melodies and harmony
- explore music theory
- visualize music on a piano roll
- work with guitar chords and tabs
- play notes and chords with a virtual piano
- export MIDI
- import MIDI on Windows

The goal isn't to replace a DAW.

It's to help get from "i have this sound in my head" to "ok, now i can actually work with it."

---

## Features

### Hum to MIDI

Hum or sing into your microphone and HumTheory tracks the pitch in real time.

It can display:

- detected note
- octave
- frequency
- cents deviation
- confidence
- tuning information

Detected notes can be turned into MIDI and displayed on the piano roll.

Pitch smoothing and confidence handling help prevent small pitch fluctuations from constantly creating new notes.

### Chord & Key Analysis

Analyze notes and identify likely chords and keys.

HumTheory can work with a range of chord types and can provide alternative interpretations when the result is ambiguous.

Analysis results are treated as estimates rather than guaranteed answers.

### Song Analysis

Import:

- MP3
- WAV
- FLAC
- M4A

Depending on the build and analysis available, HumTheory can estimate:

- BPM
- tempo
- key
- chords
- chord progression
- song sections
- rhythmic information

### Piano Roll

View melodies, generated progressions, and MIDI data in a piano-roll interface.

### Virtual Piano

Play notes and chords directly inside HumTheory and use the piano to visualize detected notes, chord tones, and scales.

### Guitar & Tabs

Work with guitar-oriented versions of musical ideas, including chord shapes, fretboard positions, playable voicings, and tablature.

### Progression Generator

Generate chord progressions around parameters such as:

- key
- scale
- genre
- mood
- complexity

### Music Theory

HumTheory's theory tools are designed as practical references rather than a course system.

Explore:

- notes
- intervals
- scales
- modes
- chords
- chord construction
- inversions
- key relationships
- Roman numeral analysis
- diatonic harmony
- compatible scales
- common progressions

### Circle of Fifths

Use the Circle of Fifths to explore keys and their relationships, including major scales, relative minors, diatonic chords, Roman numerals, compatible modes, and common progressions.

### MIDI

HumTheory supports MIDI workflows including:

- MIDI import
- MIDI export
- MIDI playback
- piano-roll visualization
- generated MIDI from melodies and progressions

---

## Platform Support

### Windows

HumTheory 0.1b is available for Windows.

The Windows version is actively being developed, and some parts of the UI still need polish.

### macOS

HumTheory is also available for macOS.

Some functionality currently differs between the Windows and macOS builds while feature parity continues to improve.

---

## Beta

HumTheory 0.1b is an early public beta.

Things can break, detections can be wrong, and some features are still being refined.

Music analysis is inherently imperfect. Noisy microphones, dense mixes, unusual tunings, and ambiguous chords can all affect results.

---

## Known Issues

See [KNOWN_ISSUES.md](KNOWN_ISSUES.md) for the current list of known problems.

The main issues in 0.1b are:

- note detection can be inconsistent on both macOS and Windows
- the Windows UI can still feel choppy in places
- Windows and macOS do not currently have complete feature parity

---

## Screenshots

Screenshots will be expanded as HumTheory continues to develop.

For the current product showcase, visit:

[HumTheory](https://humtheory.net)

---

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for release history.

---

## Roadmap

Current priorities include:

- improve note detection on macOS and Windows
- improve Windows UI performance
- improve Windows/macOS feature parity
- improve chord recognition
- improve song analysis
- improve piano-roll workflows
- expand guitar tools
- improve MIDI workflows
- add more screenshots and product documentation
- continue UI and performance polish

Longer-term ideas may include melody generation, automatic accompaniment, vocal harmonization, stem analysis, arrangement suggestions, and plugin integrations.

These are not part of the current 0.1b focus.

---

## Privacy

HumTheory is designed as a local desktop application.

Audio processing is performed locally rather than uploading microphone recordings or songs to a cloud service.

No account is required to use the application.

---

## Development

HumTheory is being developed as a modular music-analysis application.

The major systems are separated into areas such as:

```text
Audio
Pitch Detection
Chord Detection
Song Analysis
Music Theory
MIDI
Guitar
Projects
UI
```

The goal is to keep the analysis systems independent from the interface so individual systems can be improved or replaced without rebuilding the entire application around them.

---

## Getting HumTheory

[Visit the HumTheory website](https://humtheory.net)

[Download the latest release](https://github.com/junyaaa2819/humtheory/releases/tag/latest)

---

## Project Status

**Current release: 0.1b Beta**

HumTheory is actively being developed.

The current priority is improving reliability, cleaning up the Windows experience, expanding feature parity, and turning the existing tools into one cohesive music workstation.

---

## License

License information will be added when the project's licensing terms are finalized.

---

<p align="center">
  <strong>HumTheory</strong><br>
  Hear. Analyze. Understand. Create.
</p>
