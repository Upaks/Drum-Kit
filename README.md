# Drum Kit 🥁

Interactive browser-based drum kit built with vanilla HTML, CSS, and JavaScript. Tap the on-screen pads or press matching keyboard keys to trigger high-quality drum samples with instant feedback.

## Features
- **Keyboard + Click Support** – play drums with either mouse/touch or mapped keys.
- **Audio Samples** – realistic `.wav` files stored in the `sounds/` directory.
- **Visual Feedback** – pads animate on hit to show exactly which drum fired.
- **Zero Dependencies** – plain ES6 JavaScript, great for learning DOM events and audio APIs.

## Project Structure
- `index.html` – markup for the drum pads and instructions.
- `styles.css` – responsive layout plus hit animations.
- `index.js` – event listeners, audio triggering, and active-state handling.
- `sounds/` – audio assets for each drum.
- `images/` – optional graphics or icons used in the UI.

## Getting Started
```bash
git clone https://github.com/<your-user>/Drum-Kit.git
cd Drum-Kit
```
Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari).

## How to Play
- Click a pad or press its corresponding key (e.g., `W`, `A`, `S`, etc.).
- Each pad plays its sample and flashes to confirm the input.
- Combine hits to create your own beats.

## Customization Ideas
- Swap in your own `.wav` files inside `sounds/`.
- Add recording / playback using the Web Audio API.
- Create mobile-friendly UI tweaks or dark/light themes.

## Contributing
Issues and pull requests are welcome. Ideas include metronomes, visualizers, multi-track recording, or accessibility improvements.
