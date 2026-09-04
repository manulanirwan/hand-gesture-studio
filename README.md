# Hand Gesture Studio

A browser-based hand gesture and finger-counting studio built with HTML, CSS, JavaScript, MediaPipe Hands, and CDN-hosted libraries.

## Features

- Real-time webcam hand tracking with MediaPipe Hands
- Two-hand finger detection and live finger counts
- Synthetic hand simulator for testing without a camera
- Cyberpunk-style visual interface
- Normal, neon, edge, and thermal-style visual filters
- CDN edge-node visualizer
- Bitrate telemetry display
- Finger-count math challenge game
- Fullscreen and sound controls

## Live Preview

GitHub Pages deployment is configured for this repository. After the first Pages deployment completes, the site will be available at:

https://manulanirwan.github.io/hand-gesture-studio/

## Run Locally

Open the project through a local HTTP server for the best browser compatibility, especially when using the webcam.

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser and allow camera access when prompted.

## Technology

- HTML5
- CSS3
- JavaScript
- MediaPipe Hands
- Tailwind CSS CDN
- Font Awesome
- Canvas Confetti

## Browser Permissions

Camera mode requires browser camera permission and a secure context such as HTTPS or localhost. If camera access is unavailable, use the Synthetic Simulator mode.

## Project Structure

```text
hand-gesture-studio/
├── index.html
├── README.md
└── .github/
    └── workflows/
        └── pages.yml
```
