# Piano Power! 🎹 - Child-Friendly Piano Learning

A fun, single-file kids piano trainer perfect for GitHub Pages deployment! Features a beautiful 3-page child-friendly interface with engaging animations.

## ✨ Features

- **🎤 Microphone pitch detection** or **🎹 USB/MIDI keyboards**
- **👶 Child-friendly 3-page interface**:
  1. **Welcome page**: Simple greeting and name input
  2. **Song selection**: Big colorful song buttons with smaller options
  3. **Game interface**: Interactive piano with star animation
- **🎵 Two difficulty modes**: Easy (single octave) and Strict (multi-octave)
- **🌈 Color-coded piano keys** (C=Red, D=Orange, E=Yellow, F=Green, G=Light Blue, A=Navy, B=Purple)
- **⭐ Enhanced star animation** with platform jumping and twinkling effects
- **🎼 Built-in songs**: *Twinkle Twinkle Little Star*, *Mary Had a Little Lamb*
- **📁 MIDI file upload** support (upload your own songs!)
- **⏱️ Session timing** with best/last time tracking

## 🚀 Quick Start

1. **Create a repo** and add `index.html` (this single file contains everything!)
2. **Enable GitHub Pages**: Settings → Pages → Branch: `main` → `/root`
3. **Open your Pages URL** — that's it! 🎉

## 🎯 How to Use

1. **Enter your name** on the welcome page
2. **Choose your input method** (microphone or MIDI keyboard) and difficulty
3. **Select a song** with the big colorful buttons
4. **Follow the prompts** and watch the star jump up platforms as you play!

## 🎮 Game Features

- **Fun feedback messages** with encouraging emojis
- **Platform-jumping star animation** that progresses through the song
- **Color-coded note timeline** showing upcoming notes
- **Child-friendly fonts and styling** with the Fredoka font family
- **Responsive design** that works on tablets and desktops

## 💡 Tips

- **Strict mode** shows octave numbers and enforces precise octave matching
- **Easy mode** focuses on note names without octave requirements  
- **Microphone mode** works best in quiet environments
- **MIDI mode** works best in Chrome/Edge browsers
- **No data persistence** - everything resets on page reload for privacy

## 🎼 Adding More Songs

You can modify the `SONGS` object in `index.html` to add your own note sequences using step+octave notation (e.g., `E4`, `F#3`). Uploaded MIDI files work great too!

## 🛠️ Technical Notes

- **Single HTML file** - no build process required
- **Web MIDI API** for keyboard support
- **Web Audio API** for microphone pitch detection
- **Pure CSS animations** for smooth star movement
- **No external dependencies** except font loading