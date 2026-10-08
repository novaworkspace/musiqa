# Work Radio

Generative music for focus, synthesized live in the browser with the Web Audio API. Nothing is pre-recorded, so it never repeats.

Nine stations: White noise, Café, Nature, Lo-fi, Deep house, Intense, Jungle, Drum & bass, Hip-hop. Each "track" is a new variation with its own tempo, key and instruments; track length is adjustable from 2 to 7 minutes. Per-station character sliders and an instrument mixer are saved in the browser.

## Install on a phone

Open the GitHub Pages URL, then:

- **iPhone (Safari):** Share → Add to Home Screen.
- **Android (Chrome):** menu → Install app (or Add to Home screen).

Playback works with the screen off and responds to the system media controls (play/pause, next track, previous station).

## Files

- `index.html` — the whole app
- `manifest.webmanifest`, `icons/` — install metadata
- `sw.js` — offline cache

No build step: any static host works.
