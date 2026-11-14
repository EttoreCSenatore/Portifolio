# Ettore Senatore · Portfolio

Personal portfolio: https://ettorecsenatore.github.io/Portifolio/

A single-page, dependency-free site (plain HTML, CSS and a little JavaScript). It has automatic light and dark themes, is responsive down to phone width, and needs no build step.

## Structure

```text
index.html        Page content (About, Projects, Experience, Contact)
css/style.css     Design tokens, layout and themes
js/main.js        Theme toggle and active-section highlighting
assets/           Portrait, VARLab logo, favicon
```

## Run locally

```bash
python3 -m http.server 5500
```

Then open http://localhost:5500.

## Deploy

GitHub Pages serves the `main` branch from the repository root. Merging to `main` publishes the site.

## Adding a project

Copy an `<article class="card">` block in `index.html` under `#projects` and edit its text, tags and links.
