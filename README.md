# Enochian-FE-Sim
WIP /  Flat Earth Sim

# Enoch Cosmological Model

> Interactive WebGL simulation of the cosmology described in the Book of Enoch.
> Single HTML file. Open it in a browser. Fly through it.

## What this is

A 3D interactive model of the cosmos as described in the Book of Enoch 
— built in one self-contained HTML file using WebGL.

This is **Nathan Synthesis**: my own working interpretation of Enoch's cosmology, 
built around the 77,760 framework, the gates of the sun, the dome, 
and capture-orbit retrograde motion.

The aim isn't to argue. The aim is to let you see it for yourself.

## Features

- Realtime 3D WebGL rendering
- 12 sun gates, dome, ground plane, outer wall
- Sun, moon, planets with toggleable visibility
- Orbits, trails, labels, axis lines
- Stars, deep sky, Milky Way, meteors, constellations, the Mazzaroth
- Time controls — speed up, slow down, scrub through the year
- Adjustable dome altitude
- Outer-shell spin nudge controls
- Works on desktop and mobile (mouse, touch, keyboard)

## How to run

1. Download `enoch_v22_final.html` (or clone the repo).
2. Open it in any modern browser.

That's it. No build step, no npm, no server. 
The only outside dependency is Three.js, loaded from a CDN.

## Controls

- **Click + drag** — orbit the camera
- **Scroll** — zoom in/out
- **Right-click + drag** — pan
- **Side panels** — toggle features, set time speed, adjust the dome

## Tech

- Vanilla JavaScript
- Three.js r128 (WebGL)
- Single HTML file (~5,400 lines)
- No build pipeline

## Version

Currently **v22.13** — see the title bar inside the sim. 
Versions are bumped when the model itself changes, not for cosmetic tweaks.

## License

Licensed under **AGPL-3.0**. See [LICENSE](LICENSE).

In plain terms: you can use, modify, and share this freely. 
If you distribute a modified version — including hosting it on a website — 
you have to publish your source under the same license. Attribution stays.

## Credits

- Cosmological model and synthesis:
- @AbyahNathan @YtzahqNathan @dawolfylamb
- Source text: *1 Enoch* (public domain)
- 3D rendering: [Three.js](https://threejs.org/)
