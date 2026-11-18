# NEON SIEGE 12.0 — Classic Optics

NEON SIEGE is a self-contained first-person sci-fi browser game with five themed worlds, grapple movement, robot waves, 3D scenery, twelve unlockable energy blasters, and an experimental peer-to-peer friend duel.

## What's new in Version 12

The unusual cyan scope overlay has been replaced with a more conventional FPS aiming view:

- **Precision blasters** (Horizon Needle, the original precision rifle, Zenith Prism, and Comet Driver) use a classic **circular magnified scope**, a black surrounding mask, subtle metal rim, and a thin crosshair.
- **All other blasters** use a compact, centered **red-dot sight** with a raised first-person weapon model.
- Zoom now transitions smoothly when you hold and release the right mouse button.
- The main crosshair is hidden when using a sight, avoiding double reticles.
- Existing world visibility/depth testing, maps, weapons, enemy waves, and grapple movement are preserved.

## Play

Open `index.html` in Chrome or Edge, select a map, and begin the game. Click in the game for mouse capture.

| Control | Action |
| --- | --- |
| WASD | Walk / strafe |
| Mouse | Look around |
| Right mouse (hold) | Aim through scope or red-dot sight |
| Left mouse | Fire |
| Mouse wheel / number keys | Switch unlocked blasters |
| Q / E | Grapple |
| Shift | Sprint |
| Space | Jump |
| Ctrl | Slide |
| C | Dash |
| F | Interact / climb |
| R | Reload |
| Esc | Pause |

## GitHub Pages

Upload the files in this folder into a public GitHub repository, with `index.html` at the root. Then open **Settings → Pages** and choose **Deploy from a branch**, `main`, `/ (root)`. Commit future updates to `index.html` to publish new versions. The PNG previews are optional screenshots; the game needs no external libraries.

## Notes

- Weapon unlocks and menu settings are stored locally in your browser.
- Direct online 1v1 is experimental and has not been verified across different devices or networks.
- The scope is game artwork, not a simulation of a real optical device.
