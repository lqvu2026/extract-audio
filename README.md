# Extract Audio

A single-page web app that pulls the audio out of a video, entirely in your browser (nothing is uploaded).

## Files
- `index.html` – the app
- `extract-audio-icon.png` – 180x180 icon (used for the browser tab and iPhone Home Screen)

## Publish on GitHub Pages
1. Put both files in the same repo folder (the icon must sit next to index.html).
2. Commit and push, then turn on Pages (Settings → Pages → deploy from branch).
3. Wait 1–2 minutes.

## Add to iPhone Home Screen
Delete any old shortcut, quit Safari, reload the page, then Share → Add to Home Screen.

## Use
Choose a video → trim (drag the orange/mint handles on the waveform, type exact times, or tap "Set start here" / "Set end here") → optional fade in/out → set the file name → pick MP3, WAV or M4A → Extract audio → Download or Share.

Notes: MP3 encoding loads the lamejs library from a CDN, so the first use needs internet. M4A is recorded in real time, so it takes as long as the clip and is only offered where the browser supports it.
