# Birthday Card 🎂

A rich, animated birthday greeting — all in a single `index.html`, no build step.
Open `index.html` in any browser, or deploy the folder to Vercel/Netlify.

## Features
- 💌 **Envelope intro** — "tap to open" unwraps into the card
- 🎵 **Music** — a *Happy Birthday* melody synthesized in-browser (no audio file), with a mute toggle (top-right)
- ⌨️ **Typewriter** message reveal
- 🎂 **Blow-out candles** — tap the cake to blow them out and make a wish
- 🖼️ **Photo gallery** — auto-play, swipe, dots, and tap-to-enlarge lightbox (← → / Esc)
- 🎈 **Pop-able balloons** and 🎆 confetti + fireworks
- ✨ **Cursor sparkle trail**
- 🎈 Optional **age / countdown** to the next birthday

## Customize
Edit only the `CARD = { ... }` block near the top of `index.html`:
- `name`, `message`, `signature`
- `photos` — file names inside the `photos/` folder
- `bornDate` — `"YYYY-MM-DD"` to show age/countdown (leave `""` to hide)
- `music` — `true`/`false` to auto-play the melody
