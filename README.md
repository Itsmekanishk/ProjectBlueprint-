# Reactive Particle Ring (Three.js)

An interactive, full-screen **particle ring** built with **Three.js**. Move your mouse over the ring to repel particles; they smoothly return to their original orbit while the whole system slowly rotates.

## Features

- **Reactive particles**: hover-driven repulsion + smooth “return to origin”
- **Full-screen canvas** with a minimal overlay UI
- **No build step**: runs as a single `index.html`
- **CDN-based Three.js** (no local dependencies)

## Demo

- **Live demo**: Deploy with GitHub Pages (see [Deploy](#deploy-github-pages)).

## Getting started

### Option A: Open the file directly

Open `index.html` in your browser.

> Note: Some browsers may restrict certain assets when opened via `file://`. If anything looks off, use Option B.

### Option B: Run a local web server (recommended)

From the project folder:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080` in your browser.

## Controls

- **Mouse move**: repels nearby particles (creates a “hole” / tunnel effect)

## Customize

You can tweak the visuals by editing values in `index.html`, for example:

- `particleCount`
- `radius` and `spread` (ring size/thickness)
- `repulsionRadius`, `repulsionStrength`, `returnSpeed`
- `particlesMesh.rotation.z` (orbit speed)

## Project structure

```text
.
├── index.html   # HTML + CSS + Three.js script
└── README.md
```

## Built with

- **Three.js** (loaded via CDN)

## Deploy (GitHub Pages)

1. Push this repo to GitHub
2. In GitHub, go to **Settings → Pages**
3. Under **Build and deployment**, choose:
   - **Source**: “Deploy from a branch”
   - **Branch**: your default branch (e.g. `main`) and `/ (root)`
4. Save — after a minute, your site will be available at your Pages URL

## License

No license file is included yet. If you plan to share publicly, consider adding a `LICENSE` (MIT is a common choice for small demos).

