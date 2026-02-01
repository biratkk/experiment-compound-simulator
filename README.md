# Molecule Environment - WebGL Visualization

[![Assisted with Claude Code](https://img.shields.io/badge/Assisted%20with-Claude%20Code-6366f1?logo=anthropic&logoColor=white)](https://claude.ai/code)

Interactive 3D molecular simulation using Three.js with real-time physics.

## Features

- **12 molecule types**: H₂O, CO₂, O₂, N₂, H₂, CH₄, NH₃, H₂SO₄, HCl, NaCl, C₂H₆, C₂H₄
- **Physics simulation**: Coulomb forces, Lennard-Jones potential, cohesion, viscosity
- **Adjustable parameters**: Temperature (0-4000K), gravity (Moon/Earth/Jupiter), container dimensions
- **10 presets**: Boiling Water, Lava Lamp, Centrifuge, Condensation, Zero Gravity, and more

## Usage

Open `h2o.html` in a browser. Use the left panel to add/remove molecules and adjust settings. Drag to rotate, scroll to zoom.

## Dependencies

- [Three.js r128](https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js) (loaded via CDN)
