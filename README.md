# AM Audio Visualizer

An audio-reactive desktop wallpaper for [Lively Wallpaper](https://rocksdanister.github.io/lively/), inspired by the visual identity of Arctic Monkeys' *AM* album and the waveform in ["Do I Wanna Know?"](https://www.youtube.com/watch?v=bpOSxM0rNPM).

![AM Audio Visualizer preview](thumbnail.png)

The visualizer is built with **HTML5 Canvas** and **vanilla JavaScript**. Its waveform responds to audio input, using sine functions and Gaussian envelopes to shape the peaks and valleys.

## Installation

**Requirements:** Windows and [Lively Wallpaper](https://rocksdanister.github.io/lively/).

1. Download this repository using **Code → Download ZIP**.
2. Extract the ZIP archive.
3. Move the extracted project folder into your Lively Wallpaper library folder.
4. Rename the project folder to `hygciyc.diwn` so it matches the wallpaper ID configured in `LivelyInfo.json`.
5. In Lively Wallpaper, add or select the wallpaper and set it as your desktop background.

If Lively does not detect it automatically, use Lively's wallpaper import/add option and select the extracted project folder.

## Project files

- `index.html` — wallpaper entry point.
- `script.min.js` — canvas rendering and audio-reactive visualization.
- `LivelyInfo.json` — Lively Wallpaper metadata.
- `thumbnail.png` — static preview image.

An animated capture is available in [preview.gif](preview.gif). The GIF is large, so it is linked separately rather than loaded automatically in this README.

## License

Released under the [MIT License](LICENSE).
