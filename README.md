# Valentine's Day Game

A retro pixel-art Valentine's Day game. A cute pixel character runs forward while the player taps to jump and collect hearts. After 5 seconds, it asks "Will you be my Valentine?" with a giant YES button and a tiny NO button that runs away when you try to click it.

## How It Works

1. **Start Screen** — Tap to start the game
2. **Gameplay (5 seconds)** — Tap anywhere to jump and collect hearts
3. **Valentine's Question** — Shows heart count, then asks the big question
   - YES button is huge and pulsing
   - NO button dodges every tap and shrinks until you give up

## Tech

- Single `index.html` file — no dependencies, no build step
- Vanilla HTML/CSS/JavaScript with Canvas rendering
- 8-bit sound effects and background music via Web Audio API
- Mobile-responsive with full touch support
- Retro pixel art style using "Press Start 2P" font

## Deploy

Drop this repo on [Vercel](https://vercel.com) — zero configuration needed.

Or just open `index.html` in any browser.

## Run Locally

```
python3 -m http.server 8080
```

Then open http://localhost:8080
