# Valentine's Day Game

A retro pixel-art Valentine's Day game. A cute pixel character runs forward while the player taps to jump and collect hearts. After 5 seconds, it asks "Will you be my Valentine?" with a giant YES button and a tiny NO button that runs away when you try to click it.

## How It Works

1. **Start Screen** - Tap to start the game
2. **Gameplay (5 seconds)** - Tap anywhere to jump and collect hearts
3. **Valentine's Question** - Shows heart count, then asks the big question
   - YES button is huge and pulsing
   - NO button dodges every tap and shrinks until you give up

## Tech

- Single `index.html` file, no dependencies, no build step
- Vanilla HTML/CSS/JavaScript with Canvas rendering
- Web Audio API tuned for low-latency mobile playback
- Retro synth-style SFX generated in code
- Background music loaded from `bgm.wav` with generated fallback
- Sound is on by default with a retro speaker icon toggle (top-right)
- Mobile-responsive with full touch support
- Retro pixel art style using `Press Start 2P`
- Subtle maker credit in scene: `crafted with love by Jayanth Putta`

## Deploy

Drop this repo on [Vercel](https://vercel.com) with zero configuration.

You can also open `index.html` directly in a browser.

## Run Locally

```bash
python3 -m http.server 8080 --bind 0.0.0.0
```

Then open [http://localhost:8080](http://localhost:8080).

For mobile testing on the same Wi-Fi:

```bash
ipconfig getifaddr en0
```

Then open `http://<your-ip>:8080` on your phone.

Note: `GET /_vercel/insights/script.js 404` is expected in local logs when not hosted on Vercel.

## Copyright

Copyright (c) 2026 Jayanth Putta. All rights reserved.
