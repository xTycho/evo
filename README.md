# Evo

What's flying above you right now. A live globe of satellites, their passes over your location, and upcoming rocket launches, in a minimal amber HUD style.

Open it at https://xtycho.github.io/evo/

- Orbits come live from [CelesTrak](https://celestrak.org) and are propagated in the browser with [satellite.js](https://github.com/shashwatak/satellite-js) (SGP4).
- Launches come from [The Space Devs](https://thespacedevs.com) Launch Library 2.
- If either source is unreachable, the page falls back to the snapshot built into `index.html`.

Single static file, no build step. Three.js r128 for the globe.
