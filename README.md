# Pentagram Animation

A minimal, dependency-free demo that draws and animates a pentagram (five-pointed star) using only HTML, CSS and vanilla JavaScript.

![Pentagram animation screenshot](./Screenshot%202024-12-08%20001455.png)

Live preview

- Open `index.html` in your browser (double-click the file) or serve the folder with a static server:

  ```bash
  # using a lightweight server
  npx serve
  # or
  npx live-server
  ```

Highlights

- Single-file demo (`index.html`) — no build step or dependencies required.
- Smooth drawing and animation of a pentagram using Canvas/SVG/CSS (see `index.html`).
- Easy to tweak colors, timing and geometry to explore generative animation ideas.

How it works (brief)

- The demo computes the five vertices of a pentagon and connects them in the order needed to draw a pentagram.
- JavaScript drives the drawing and timing; CSS handles basic layout and any visual transitions.
- The animation loop progressively draws (or reveals) the pentagram and repeats or reverses depending on the script.

Customization

Open `index.html` and look for clearly labeled variables or constants near the top of the script. Typical parameters you can change:

- stroke color, line width and glow effects
- animation duration and easing/timing
- canvas size or scale
- whether the animation loops or plays once

If you want help making a specific change, tell me what you'd like to customize and I can suggest exact edits.

Files

- `index.html` — the complete demo and the place to edit animation parameters.
- `Screenshot 2024-12-08 001455.png` — screenshot shown above.

Usage

1. Clone or download this repository:

```bash
git clone https://github.com/BinaryVortex/Pentagram-Animation.git
cd Pentagram-Animation
```

2. Open `index.html` or run a static server as shown above.

Development

- This is intentionally small and self-contained. For larger experiments consider extracting the drawing code into a separate JS file and adding a small UI so parameters can be changed in the browser.

Contributing

- Bug reports, improvements or animation presets are welcome. Please open an issue or submit a pull request with a short description of the change.

License

- No license currently specified. If you want to allow reuse, add a LICENSE file (for example the MIT license).

Credits

- Built by BinaryVortex.
