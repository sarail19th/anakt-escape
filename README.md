# Anakt Escape

A small pixel-art maze game in a single HTML file (canvas + vanilla JS, no dependencies, no build step).
The hero races through a facility full of dogs, scanning robots and aliens to free a prisoner and get out
together.

> Unofficial fan project, inspired by the *Alien Stage* scene where Ivan fails to rescue Til from the Anakt
> Garden. Not affiliated with or endorsed by the creators. All code and pixel art here are original.

**Play:** https://sarail19th.github.io/anakt-escape/ (works on phones too)

## How to play

- **Move:** arrow keys / WASD, swipe on the screen, or the on-screen D-pad on touch devices.
- **P** pauses, **M** toggles sound, **C** switches between **Calm** (default) and **Normal** pace.
- Dots give a short burst of speed. Red flowers give +1 heart and a speed boost (up to 5 hearts).
- A tackle from a dog, robot or alien costs a heart. Robots have a red scan radius: walk into it and the alarm
  sends the dogs after you.
- Six stages across four floors, three endings. Find the stairs, find the key, free your friend, and get
  out together. Be careful what you stop to look at on the way back.

## Run it locally

Open `rescue.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

then visit `http://localhost:8000/`.

## Files

- `rescue.html` – the whole game.
- `index.html` – redirects to the game (so the GitHub Pages root works).
- `.github/workflows/pages.yml` – publishes the game to GitHub Pages on every push to `main`.
