# The Neck — Fretboard Trainer

> A quick pick-up game for memorizing the notes on the guitar fretboard.

Part of a four-app practice system. This is the game you play during downtime to lock in the neck.

## How it plays
- **Two modes:**
  - **Name the note** — a dot lights up on the neck; tap its name from four choices.
  - **Find the note** — you're given a note and a string; tap the right fret.
- **Seven levels** that build the way the neck anchors: Low E → A → string pairs → all naturals → all notes + sharps
- **Sprint mode** — a 60-second score chase (wrong answers cost 3 seconds), or flip it off for a calm 20-question round
- Tracks **score, streak, and best per level**; optional **note-pitch playback** for ear training
- End screen shows a **Review list of exactly which notes you missed**
- Works **offline**; scores saved on your device

## Live app
https://plo512.github.io/the-neck/  *(update this link if your repo has a different name)*

## Install on your phone (Android / Chrome)
1. Open the live link in **Chrome** (a normal tab).
2. Tap **⋮ menu → Install app** (or the in-app **Install this app** button).
3. It lands on your home screen. Tap once to unlock sound.

## Updating
Upload a new `index.html` over the old one and commit — the installed app updates itself.

## Tech
Single-file HTML/CSS/JS progressive web app (PWA). No build step or dependencies. Note math is standard-tuning based; offline via a service worker; scores stored in `localStorage`.

## Files
`index.html` · `manifest.json` · `sw.js` · `icon-192.png` · `icon-512.png` · `apple-touch-icon.png`

## The full set
- **The Hour** — session timer
- **The Plan** — daily guide + full reference
- **The Neck** — fretboard note memorization game (this app)
- **The Language** — phrasing, CAGED, and the Nashville Number System
