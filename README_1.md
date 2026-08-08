# The Language — Phrasing · CAGED · Numbers

> A pocket teacher for the three ideas that turn correct notes into music: phrasing, the CAGED system, and the Nashville Number System.

Part of a four-app practice system. This is the theory brain — *what* to play, *where*, and *how*.

## What's inside
- **Overview** — the spine of the app: Numbers = *what chords*, CAGED = *where on the neck*, Phrasing = *how to say it*
- **Phrasing** — nine principles (space, question & answer, motif development, targeting chord tones, tension & release, bends & vibrato, the singing test), each with a "Try this" drill
- **CAGED** — the five shapes drawn as chord diagrams with roots highlighted, how they move and link in C-A-G-E-D order, and how they connect to the pentatonic boxes
- **Numbers** — an interactive **key translator**: pick any major or minor key and see all seven diatonic chords plus common progressions spelled out (flip to Minor for the 1-♭6-♭7 metal staple)
- **Circle** — an interactive **circle of fifths**: tap any key to light up its 1, 4, and 5 (with the relative minor on the inner ring) and see how the number system maps onto the wheel
- Works **offline**

## Live app
https://plo512.github.io/the-language/  *(update this link if your repo has a different name)*

## Install on your phone (Android / Chrome)
1. Open the live link in **Chrome** (a normal tab).
2. Tap **⋮ menu → Install app** (or the in-app **Install** button).
3. It lands on your home screen and launches full-screen.

## Updating
Upload a new `index.html` over the old one and commit — the installed app updates itself.

## Tech
Single-file HTML/CSS/JS progressive web app (PWA). No build step or dependencies. The Nashville translator computes correct scale spellings and chord qualities for every supported key; offline via a service worker.

## Files
`index.html` · `manifest.json` · `sw.js` · `icon-192.png` · `icon-512.png` · `apple-touch-icon.png`

## The full set
- **The Hour** — session timer
- **The Plan** — daily guide + full reference
- **The Neck** — fretboard note memorization game
- **The Language** — phrasing, CAGED, and the Nashville Number System (this app)
