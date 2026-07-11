# Clay Studio

A polished local 3D browser pottery-making game built with HTML, CSS, JavaScript, and Three.js.

## Run locally

Because the project uses ES modules, run it through a local static server:

```bash
cd /Users/moonshot/clay-studio
python3 -m http.server 5173
```

Then open:

```text
http://localhost:5173
```

The app imports Three.js from the official npm CDN in `index.html`, so the first load needs network access unless you vendor Three.js locally and update the import map.

## Controls

- Drag directly on the clay to shape it.
- Horizontal drag widens or narrows the active area.
- Upward drag pulls the form taller.
- Downward drag compresses the form.
- Drag outside the clay to orbit the camera.
- Mouse wheel zooms.
- Use the toolbar for shape, smooth, pinch, expand, compress, and cut-rim tools.

## Features

- Rotationally symmetric pottery mesh made from adjustable horizontal vertex rings.
- Smooth deformation with nearby-ring interpolation and radius constraints.
- Drying, firing, painting, glazing, display, gallery, scoring, screenshot export, photo mode, fullscreen, pause/settings, and localStorage saves.
- Procedural Web Audio pottery wheel, clay touch, kiln ambience, and calm background tones.

No copyrighted assets, logos, sounds, code, or artwork from existing games are included.
