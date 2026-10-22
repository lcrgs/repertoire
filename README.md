# My Repertoire

A small iPhone web app for keeping track of the songs I play on guitar:
what I know by heart, what I almost know, what I play with the tab, and what I want to learn.

- Capo, "sounds fine without capo", easy to sing, fingerpicking, language, chords and notes
- Tab and video links per song
- Song suggestions from Apple's catalog while typing a title
- Setlists, with songs picked by hand or at random
- Works offline once opened; songs are stored on the device only
- Back up / restore to a file (e.g. in iCloud Drive)

## Install on iPhone

Open the site in Safari, tap **Share → Add to Home Screen**.

## Development

Plain HTML, CSS and JavaScript with no build step. `index.html` is the whole app,
`sw.js` adds offline support. Serve the folder with any static server.
