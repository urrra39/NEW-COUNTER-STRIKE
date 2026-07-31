# NEW COUNTER STRIKE

I've been into Counter-Strike since I was a kid. That love for the game is why I built **NEW COUNTER STRIKE** — a browser FPS inspired by classic de_dust, focused on Bombsite A, Long A, Catwalk, and The Pit.

Making this was not easy. There were a lot of late nights, broken builds, and moments where I almost quit. Discipline and determination kept me going. I tried as hard as I could to make it feel realistic: the map, the movement, the gun feel, the lighting, and the overall atmosphere.

This project is a single-file WebGL game. No installers. No accounts. Open it and play.

---

## Features

- Classic-style **de_dust** layout (Bombsite A · Long A · Catwalk · Pit)
- First-person shooter controls with ADS, reload, crouch, walk, and jump
- AK-focused combat with hip / ADS view
- HE grenades
- Enemy waves / bots
- In-game radar + full map (`M`)
- Sensitivity, FOV, volume, quality, and difficulty settings
- Runs fully in the browser (Three.js)

---

## How to play (easiest)

### Option 1 — Open the HTML file

1. Download this repository (Code → **Download ZIP**), or clone it.
2. Open `index.html` (or `NEW_COUNTER_STRIKE.html`) in **Chrome**, **Edge**, or **Firefox**.
3. Click **DEPLOY**.
4. Click the game screen once so the mouse locks.
5. If something looks cached / old, press **Ctrl + F5**.

### Option 2 — Clone with git

```bash
git clone https://github.com/urrra39/NEW-COUNTER-STRIKE.git
cd NEW-COUNTER-STRIKE
```

Then open `index.html` in your browser.

> Tip: a normal double-click is enough for this game. You do **not** need Node.js, npm, Python, or a local server.

---

## Controls

| Key | Action |
|---|---|
| `W` `A` `S` `D` | Move |
| `Space` | Jump |
| `Shift` | Walk |
| `Ctrl` | Crouch |
| `LMB` | Fire |
| `RMB` | Aim (ADS) |
| `R` | Reload |
| `G` | Throw HE grenade |
| `1` / `Q` | Weapon / previous weapon |
| `M` | Full map |
| `Esc` | Pause |
| `X` | Unstick if you get stuck |

---

## Settings

On the main menu you can change:

- **SENS** — mouse sensitivity
- **FOV** — field of view
- **VOLUME** — sound level
- **QUALITY** — LOW / MEDIUM / HIGH
- **DIFFICULTY** — EASY / NORMAL / EXPERT

---

## Files in this repo

| File | What it is |
|---|---|
| `index.html` | Full game (open this) |
| `NEW_COUNTER_STRIKE.html` | Same full game, alternate filename |
| `README.md` | This guide |
| `LICENSE` | MIT |

The whole game is inside the HTML file (graphics, map, audio logic, UI). Internet is needed the first time so **Three.js** can load from CDN.

---

## Requirements

- A modern browser (Chrome / Edge / Firefox recommended)
- Internet connection (for Three.js CDN)
- Mouse + keyboard

---

## Troubleshooting

- **Black screen / won't start** — check your internet, then refresh with **Ctrl + F5**
- **Mouse not locked** — click the game window once after DEPLOY
- **Old version still showing** — hard refresh (**Ctrl + F5**) or reopen the file
- **Low FPS** — set Quality to **LOW** or **MEDIUM**

---

## Why I made this

Counter-Strike shaped how I think about shooters — the maps, the aim, the pressure, the style. I wanted to build my own version of that feeling and put it in a place anyone can open in a browser.

It wasn't a smooth process. I rebuilt pieces of the map, the weapon view, the stairs, the UI, and the feel over and over. Every time something broke, I fixed it and kept going. That discipline is the real reason this exists.

If you play it, thank you. If you enjoy it even a little, that means a lot.

---

## License

MIT — see [LICENSE](LICENSE).
