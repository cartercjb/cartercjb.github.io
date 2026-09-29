# AGENTS.md

## Cursor Cloud specific instructions

This is a static GitHub Pages site (`cartercjb.github.io`) with no build system, package manager, or dependencies. The repo contains only plain HTML/CSS/JS files.

### Running the dev server

Serve the site locally with Python's built-in HTTP server:

```
python3 -m http.server 8080
```

Then open `http://localhost:8080/index.html` or `http://localhost:8080/nav_horizontal.html` in a browser.

### Key files

- `index.html` — Landing page ("Hello World").
- `nav_horizontal.html` — Horizontal navigation bar widget (uses Font Awesome and Google Fonts via CDN).

### Notes

- There are no lint, test, or build steps — the site is purely static HTML.
- External CDN resources (Font Awesome 6.2.0, Google Fonts Lato) are loaded at runtime in `nav_horizontal.html`; pages still render without internet but icons/fonts will be missing.
