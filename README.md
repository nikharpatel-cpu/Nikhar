# Modi’s Vote Run

A playful, unofficial parody arcade game by Nikhar. Collect fictional ballot tokens, avoid roadblocks, and survive faster rounds. No accounts, analytics, backend, or paid dependencies. The high score stays in your browser.

## Play locally

Open `index.html`, or run `python3 -m http.server 8080` in this folder and visit http://localhost:8080.

Use left/right arrows, swipe, or the on-screen buttons to change lanes. Press P or Escape to pause. You have three lives. Each 20-second round increases speed, up to a playable cap. Sound is optional.

## Publish on GitHub Pages

1. Create a repository named `Nikhar` and upload these files at its root.
2. Open Settings → Pages.
3. Choose “Deploy from a branch”, then `main` and `/ (root)`, and save.
4. GitHub will display the published URL after deployment.

All game artwork is drawn in code. Google Fonts are optional; system fonts work offline. The game is unofficial and not affiliated with any politician or political party. Votes are game points, not real votes.

When sound is enabled, ballot pickups say “lawden bhojyam” in an ordinary browser synthetic voice. Voice availability and pronunciation depend on the device. Pickups during an active phrase do not queue extra speech; mute, pause, and game over cancel speech. No voice imitation is used.
