# 3D Shapes Playground — Three.js Proof of Concept

An interactive proof of concept exploring 3D rendering in the browser with **React Three Fiber**, **Three.js**, and **MUI**. The app renders multiple 3D shapes on a canvas, lets users create and rotate them, and exposes controls to customize each shape's dimensions and axis in real time.

> Built as a self-directed learning project to gain hands-on experience with WebGL-based 3D rendering and interactive UI controls — a foundation for using Three.js in production frontend work.

## Features

- 🔺 Render multiple 3D shapes on an HTML canvas, built declaratively with React Three Fiber on top of Three.js
- 🔄 Real-time rotation of individual shapes
- 📋 A shapes table (MUI X Data Grid) listing every shape a user creates, along with its name and properties
- 🎛️ Custom controls to adjust shape dimensions and rotation axis per shape
- 🎨 UI built with MUI (Material UI) components on top of React

## Tech Stack

| Layer         | Technology |
|---------------|------------|
| 3D Rendering  | [Three.js](https://threejs.org/) via [React Three Fiber](https://github.com/pmndrs/react-three-fiber) |
| Framework     | [React 18](https://react.dev/) (Create React App / react-scripts) |
| UI Components | [MUI (Material UI) v6](https://mui.com/) |
| Data Table    | [MUI X Data Grid](https://mui.com/x/react-data-grid/) |
| Styling Engine| [Emotion](https://emotion.sh/) |
| Testing       | React Testing Library, Jest DOM |

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)
- npm (comes bundled with Node.js)

### Installation

```bash
git clone https://github.com/madhuridethe21/3D-images-three.js-personal-poc.git
cd 3D-images-three.js-personal-poc
npm install
```

### Run in development mode

```bash
npm start
```

Runs the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser. The page reloads automatically on changes, and lint warnings/errors appear in the console.

### Run tests

```bash
npm test
```

Launches the test runner in interactive watch mode using React Testing Library and Jest DOM.

### Build for production

```bash
npm run build
```

Bundles the app in production mode and outputs an optimized, minified build to the `build/` folder, with fingerprinted filenames — ready to deploy.

## Usage

1. Launch the app and select a shape type to add it to the canvas.
2. Give the shape a name — it appears in the shapes data grid alongside its properties.
3. Use the provided controls to adjust the shape's dimensions and rotation axis.
4. Watch the shape update and rotate on the canvas in real time.

## Project Goals

This project was built to:

- Get hands-on with Three.js fundamentals — scenes, meshes, geometries, and animation loops
- Practice wiring 3D rendering into a declarative React component tree using React Three Fiber
- Build reusable, controlled MUI components (including a data grid) for manipulating 3D state

## Roadmap / Ideas for Extension

- [ ] Add more shape types (torus, cone, custom geometries)
- [ ] Persist shapes to local storage
- [ ] Add lighting and material controls
- [ ] Integrate GSAP for more advanced animation sequencing

## Author

**Madhuri Dethe**
[GitHub](https://github.com/madhuridethe21)
