# comical-sphere

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple web application that renders three animated 3D spheres, each textured with a comical image. The entire experience is contained within a single HTML file and utilizes Three.js for 3D rendering.

## Demo

https://code4fukui.github.io/comical-sphere/

## Features

- Renders three animated 3D spheres that travel along a circular path.
- Textures are sourced from `img/20240724-comical{1,2,3}.jpg`.
- Interactive camera controls for panning and zooming.
- Self-contained in a single `index.html` file with no build step required.
- Powered by [Three.js](https://threejs.org/) via the [egxr.js](https://github.com/code4fukui/egxr.js) library.

## Usage

1.  **Run the application:** Open `index.html` in a modern web browser that supports WebGL and ECMAScript modules.
2.  **Control the camera:**
    -   **Arrow Keys:** Pan the camera view (move left/right and forward/backward).
    -   **Mouse Wheel:** Zoom in and out.

## License

MIT License — see [LICENSE](LICENSE).