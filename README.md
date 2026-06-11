# Boxlings

**Tiny lives in tiny boxes.** A single-file browser life-sim: little stick folk who live in connected boxes. Drag boxes together and watch them visit, play, scrap, fall in love, have babies, get jobs and promotions, play a mini-game, and more — all running on their own.

Original work. No assets or code from any other product; everything (art, animation, audio, simulation) is generated procedurally in vanilla JavaScript.

## Play it

Just open `index.html` in any modern browser. No build, no server, no dependencies. Your world auto-saves to your browser's local storage.

### Controls

- **A** — add a box · drag a box to move it · adjacent boxes connect automatically
- **Double-click** a character — Follow mode (camera tracks them, with a live diary)
- **V** — attract / tour mode · **Space** — pause · **.** — step · **N** — day/night · **M** — mute
- **Ctrl/Cmd+S** — save · **Ctrl/Cmd+O** — load · **?** — help

## Install as an app (offline)

Boxlings is a PWA, so it can be installed to your home screen / desktop and run offline — **but install + offline only work when the files are served over `http(s)`**, not when opened directly as `file://`. Opening `index.html` straight from disk still works perfectly; you just don't get the installable/offline layer.

Quick ways to serve it over https:

- **GitHub Pages** — push this folder to a repo and enable Pages (Settings → Pages → Branch: `main` / root). Served at `https://<user>.github.io/<repo>/`.
- **Netlify Drop** — drag the folder onto <https://app.netlify.com/drop>.
- **Local** — `npx serve` in this folder (localhost counts as a secure origin).

## Files

- `index.html` — the entire app
- `manifest.webmanifest`, `sw.js`, `icon.svg` — PWA install + offline shell
