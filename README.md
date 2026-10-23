# BloomLoop

A relaxing, touch-first, generative mandala drawing playground.

## v0.1

- Draw with touch, pen, or mouse
- 2 to 24 mirrored symmetry sectors
- Six brush colors and adjustable stroke size
- Undo, redo, and clear
- Automatic browser-local saving
- Export 2048 × 2048 PNG artwork

## Run locally

Open `index.html` in any modern browser. No installation or build required.

## Publish for phone testing

For GitHub Pages, open **Settings → Pages** in this repository, then choose **Deploy from a branch**, branch **main**, folder **/(root)**, and save.

The published URL, after GitHub finishes deploying, should be `https://dstancomb3.github.io/BloomLoop/`.

For private repositories, GitHub Pages availability depends on the account plan and repository permissions. Alternatively host `index.html` via Cloudflare Pages or another static site host.

## Design principles

- Art gets most of the screen.
- No account, timers, streaks, or required network calls.
- Keep rendering deterministic and affordable.
- Test real finger gestures on Android before expanding scope.

## Known v0.1 limits

- Changing symmetry applies to new strokes, not previous ones.
- Browser-local saves remain on the same device/browser and can be erased with site data.
- Clearing resets the current artwork after confirmation.
- No installation manifest or cloud sync yet.
- No automated browser tests yet.
