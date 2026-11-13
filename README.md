# Vinay Mahadev — Actor Portfolio

A one-screen, cinematic portfolio for actor **Vinay Mahadev** (Hyderabad · Telugu, Hindi & English).

- **Hero** — portrait under blue rim light, a giant `MAHADEV` wordmark behind him, handwritten "vinay", a swinging lanyard *Actor Card* and a floating 3D cinema camera.
- **The dive** — scroll, swipe, press ↓ or click the camera: the camera flies in, turns around and its monitor powers on.
- **The reel** — five cases play on the camera monitor with a live viewfinder (REC, timecode, scene/take): Showreel, Saripodhaa Sanivaaram, Sitaraman, The Range, Nandi Award.
- **Filmography** and **Cast Vinay** sheets carry the full credits, theatre, awards, stats and contact links.

Deep links: `#work`, `#case-1` … `#case-5`, `#films`, `#cast`.

## Stack

Static site: a single `index.html` with inline CSS and JS, no framework and no build step. Images live in `assets/img/` (extracted from the actor's profile PDF). Fonts are Inter Tight, Caveat Brush and Anton from Google Fonts.

## Run locally

Open `index.html` in a browser, or serve the folder:

```sh
npx serve .
```

## Deploy

Deployed on Vercel as a static site (no build command, output directory `.`).
