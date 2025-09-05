
# PianoPal (no-build)

A single-file kids piano trainer you can deploy on GitHub Pages. Supports:

- Microphone pitch detection **or** USB/MIDI keyboards
- **Easy** (one octave C4–B4) and **Strict** (multi‑octave C1–B7) difficulty
- Color-coded keys (C=Red, D=Orange, E=Yellow, F=Green, G=Light Blue, A=Navy, B=Purple)
- Big note timeline, star‑jump animation, friendly feedback
- Built‑in songs: *Twinkle Twinkle Little Star*, *Mary Had a Little Lamb*
- Load your own **MIDI** or **MusicXML** (MuseScore → *File → Export*)
- Optional **audio samples** playback for correct notes (`/samples/C1.mp3`…`B7.mp3`, sharps like `F#3.mp3` supported)
- **Auto‑play guide** note toggle (plays the target note sample before each prompt)
- Session **Best/Last** time tracker (resets on page reload)

## Quick start

1. Create a repo and add:
   - `index.html` (this file)
   - Optionally a `samples/` folder with your note files, named like `C4.mp3`, `F#3.ogg`, `Bb2.wav`.
2. Enable GitHub Pages: **Settings → Pages → Branch: `main` → `/root`**.
3. Open the Pages URL — done.

## Usage tips

- **Strict mode** expands the on-screen keyboard to the song’s octave range and enforces octave‑correct input, telling kids “try again lower/higher” when off by an octave.
- **Mic vs MIDI**: Web MIDI works best in Chrome/Edge. Mic requires permission.
- **No persistence**: Nothing is stored after reload; timing stats are per‑session only.
- **MuseScore**: export as **MIDI** or **MusicXML**; `.mscz` is not read directly.

## Add more songs

You can modify the `SONGS` object in `index.html` to add your sequences using step+octave (e.g., `E4`, `F#3`). Uploaded files can contain accidentals; the trainer currently focuses on white-key prompts, but samples will play whichever step/octave you provide for guide playback.
