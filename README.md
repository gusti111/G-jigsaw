<div align="center">

# G-JIGSAW

**Adaptive Puzzle Engine**

A browser-based image puzzle built with HTML Canvas and vanilla JavaScript.

</div>

---

## Overview

G-Jigsaw turns an image selected by the player into an interactive jigsaw puzzle. The interface is designed around a canvas workspace, configurable puzzle behavior, and compact controls that adapt to different screen sizes.

## Features

- Import a local image in PNG, JPG, or WEBP format.
- Arrange and solve puzzle pieces on an HTML Canvas workspace.
- Select a difficulty level and adjust the puzzle experience.
- Enable optional mystery, visual-hint, and random-rotation modes.
- Shuffle and reset the puzzle.
- Request a temporary visual hint.
- Use the single-piece auto-placement helper.
- Toggle the in-game audio control.
- Use mouse, touch, and responsive layouts.

Images are selected locally in the browser; the project does not require an image-upload service.

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- HTML Canvas 2D API
- Browser File API

## Run locally

The project is a self-contained static page. No Node.js dependencies or build process are required.

    git clone https://github.com/gusti111/G-jigsaw.git
    cd G-jigsaw
    python -m http.server 8000

Open http://localhost:8000.

Alternatively, open index.html directly in a modern browser.

## Project structure

    G-jigsaw/
    ├── index.html
    ├── .gitignore
    └── LICENSE

The interface, styles, and game logic are currently contained in index.html.

## Browser considerations

Use a modern browser with Canvas 2D and File API support. Puzzle performance depends on the dimensions of the selected image and the capabilities of the device.

## Project status

A self-contained browser game prototype. No user accounts, cloud image storage, cross-device progress synchronization, or server-side game service is included.

## Author

**Gusty Faqikh** · [GitHub](https://github.com/gusti111)