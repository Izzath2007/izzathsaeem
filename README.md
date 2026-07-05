# Particle Interaction Lab

An interactive particle playground built with plain HTML, CSS, and JavaScript. Move your pointer over the canvas to push or attract particles, click to create a burst, and adjust the sliders to change the simulation in real time.

## How to make it work

You do not need to install packages or run a build step. The project is a single static `index.html` file.

### Option 1: Open the file directly

1. Download or clone this repository.
2. Double-click `index.html`.
3. Use your mouse or trackpad on the canvas:
   - Move the pointer to interact with particles.
   - Click the canvas to create a burst.
   - Use the sliders to change particle count, connection distance, and pointer force.
   - Press **Switch to Attract** to change the pointer mode.

### Option 2: Run a local server

From the project folder, run:

```bash
python3 -m http.server 8000
```

Then open this URL in your browser:

```text
http://localhost:8000
```

Stop the server with `Ctrl+C` when you are done.

## Files

- `index.html` — the complete app, including styles, markup, and canvas simulation JavaScript.
