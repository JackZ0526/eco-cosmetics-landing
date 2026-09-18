# Eco-Cosmetics — Landing Page Layout Study

An HTML/CSS reproduction of the *Brand of eco-cosmetics* Figma design, with separate desktop, tablet and mobile layouts. The focus is visual translation: typography, image placement, spacing and composition.

[Live demo](https://jackz0526.github.io/eco-cosmetics-landing/) · [My portfolio](https://www.jackzhang.ca/)

![Desktop design reference beside the browser implementation](showcase/design-vs-code-desktop.png)

## What this demonstrates

- Recreating the supplied layouts at 1440px, 768px and 320px reference widths.
- Using image and SVG assets alongside self-hosted Poppins fonts.
- Organizing the presentation into a static page and stylesheet without a framework or build process.

The comparison image records the desktop layout. Rendering can vary with viewport size, font rasterization and browser. A reproducible pixel-difference benchmark is not included, so this README does not claim an exact numerical match.

## Current scope

This is a **visual prototype**, not a working shop. Navigation labels, shopping controls and form-like elements are primarily presentation markup. Cart, checkout, message submission and backend services are not implemented.

The page uses separate layout boards and positioned elements. Integrating it into another site would require layout, semantic markup, interaction and accessibility work; it is not presented as a drop-in production component.

## Run locally

No dependency installation or build step is required. With Python 3 installed, run from the repository root:

```sh
python -m http.server 8000 --bind 127.0.0.1
```

Open [localhost:8000](http://localhost:8000). Use `python3` if that is your system's Python command. Stop the server with Ctrl+C.

## Structure

```text
index.html    Layout boards and page content
styles.css    Layout and breakpoint styling
assets/       Images and SVG graphics
fonts/        Self-hosted Poppins fonts
showcase/     Desktop design-to-browser comparison
```

## Design credit

The visual design is not my original work. The *Brand of eco-cosmetics* Figma mockup is referenced by [RomanO3GIT / Eco-cosmetics-landing](https://github.com/RomanO3GIT/Eco-cosmetics-landing). This repository is a browser reproduction study; the original design and assets retain their respective ownership and licensing terms.
