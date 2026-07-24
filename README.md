# Reactive Particle Ring (Three.js)

An interactive, full-screen **particle ring** built with **Three.js**. Move your mouse over the ring to repel particles; they smoothly return to their original orbit while the whole system slowly rotates.

🌐 **Live Website**: [https://itsmekanishk.github.io/ProjectBlueprint-/](https://itsmekanishk.github.io/ProjectBlueprint-/)

## Features

- **Reactive particles**: hover-driven repulsion + smooth “return to origin”
- **Full-screen canvas** with a minimal overlay UI
- **No build step**: runs as a single `index.html`
- **CDN-based Three.js** (no local dependencies)

## Demo

- **Live demo**: Check out the live website hosted on GitHub Pages here: [https://itsmekanishk.github.io/ProjectBlueprint-/](https://itsmekanishk.github.io/ProjectBlueprint-/)

## Getting started

### Option A: Open the file directly

Open `index.html` in your browser.

> Note: Some browsers may restrict certain assets when opened via `file://`. If anything looks off, use Option B.

### Option B: Run a local web server (recommended)

From the project folder:

```bash
python3 -m http.server 8080
