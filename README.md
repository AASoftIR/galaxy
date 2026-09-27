# Stellar Nexus — Interactive 3D Universe Explorer

Explore the cosmos directly in your browser with this single-page, WebGL-powered stellar observatory. Navigate through galaxies, stars, nebulae, planets, and more with real astronomical data.

## Features

- **Interactive 3D Scene**: Navigate a procedurally generated Milky Way, Andromeda, Triangulum, Whirlpool, and Pinwheel galaxies.
- **Real Astronomical Data**: 16+ celestial objects with accurate names, types, distances, masses, and descriptions.
- **Immersive UI**: Sci-fi holographic HUD with navigation controls, info panels, and tooltips.
- **Dynamic Effects**: Volcanic particle systems, nebula clouds, atmospheric glows, and a shader-based accretion disk for Sagittarius A*.
- **Audio Ambience**: Generative space drone via Web Audio API when toggled on.
- **Camera Controls**: Orbit, pan, zoom, reset, and smooth cinematic transitions.
- **Orbit Mode**: Toggle between free rotation and auto-locked orbit around selected objects.
- **Keyboard Shortcuts**: Spacebar for orbit mode, Escape to reset view.

## How to Navigate

| Control | Action |
|---------|--------|
| **Drag** | Orbit / rotate the view |
| **Right-drag** | Pan through space |
| **Scroll** | Zoom in/out (hyperspace mode) |
| **Click** | Inspect a celestial object |
| **Shift + Click** | Toggle constellation lines |
| **Space** | Toggle orbit mode |
| **Escape** | Reset view |

## Quick Start

```bash
# Install dependencies (optional, for dev tooling)
npm install

# Start local dev server
npm start
# Then open http://localhost:8080

# Or open directly
open index.html
```

## Deployment

GitHub Pages is configured from the root. Visit:
**https://aasoftir.github.io/galaxy/**

## Tech Stack

- **Three.js** r128 — 3D WebGL rendering
- **OrbitControls** — Interactive camera navigation
- **Custom Shaders** — Accretion disk & atmospheric glow effects
- **Web Audio API** — Generative ambient soundscapes

## Data Sources

Astronomical data compiled from publicly available scientific sources:
- NASA/IPAC Extragalactic Database (NED)
- SIMBAD Astronomical Database
- Event Horizon Telescope (Sgr A*)
- European Space Agency (ESA) archives

## License

MIT — Feel free to fork, modify, and explore.
