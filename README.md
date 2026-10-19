# ProCAD — Professional CAD Software

<p align="center">
  <img src="assets/procad-banner.png" alt="ProCAD Banner" width="100%">
</p>

<h3 align="center">Professional 2D & 3D Computer-Aided Design</h3>

<p align="center">
  A powerful browser-based CAD application inspired by Autodesk AutoCAD.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-Web-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/JavaScript-ES6-yellow?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge">
</p>

---

## Overview

**ProCAD** is a modern, browser-based Computer-Aided Design application designed for architectural, mechanical, and technical drawing.

It aims to provide a professional CAD workspace with precision drawing tools, object editing, layers, dimensions, command-line operations, and 3D modeling capabilities.

The project is inspired by professional CAD workflows while maintaining its own identity and interface.

## Features

### 2D Drawing
- Line and Polyline
- Circle and Arc
- Rectangle and Polygon
- Ellipse and Spline
- Text and Annotations
- Hatch and Fill
- Precision Coordinates

### Editing Tools
- Move and Copy
- Rotate and Mirror
- Scale and Stretch
- Trim and Extend
- Offset
- Fillet and Chamfer
- Undo and Redo
- Object Selection

### Layer Management
- Create and Delete Layers
- Layer Colors
- Visibility Controls
- Lock and Unlock
- Line Types and Weights

### Command Line
AutoCAD-inspired command interface.

Supported command targets include:

```text
LINE
PLINE
CIRCLE
RECTANG
ARC
MOVE
COPY
ROTATE
MIRROR
SCALE
OFFSET
TRIM
EXTEND
ERASE
UNDO
REDO
ZOOM
PAN
DIST
AREA
LAYER
SAVE
OPEN
```

### 3D Modeling
- 3D Primitives
- Box, Sphere and Cylinder
- Extrusion
- 3D Transformations
- Perspective and Orthographic Views
- Orbit and Camera Controls
- Shaded and Wireframe Modes

### File Support
- DXF Import / Export
- SVG Import / Export
- PNG Export
- PDF Export
- JSON Project Files

*File compatibility depends on the implemented import/export modules.*

## Interface

<p align="center">
  <img src="assets/procad-screenshot.png" alt="ProCAD Workspace" width="90%">
</p>

## Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application Structure |
| CSS3 | Interface Design |
| JavaScript / TypeScript | Application Logic |
| React | User Interface |
| Three.js | 3D Graphics |
| Canvas / SVG | 2D Rendering |

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/ProCAD.git
```

Enter the project directory:

```bash
cd ProCAD
```

Install dependencies:

```bash
npm install
```

Start development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

## Project Structure

```text
ProCAD/
├── public/
├── src/
│   ├── components/
│   ├── canvas/
│   ├── geometry/
│   ├── commands/
│   ├── layers/
│   ├── editor/
│   ├── 3d/
│   ├── export/
│   └── App.jsx
├── assets/
├── package.json
├── README.md
└── index.html
```

*The actual folder structure may differ depending on the implementation.*

## Roadmap

- [x] Project concept and architecture
- [ ] Professional CAD interface
- [ ] 2D Drawing Engine
- [ ] Editing Tools
- [ ] Layer Manager
- [ ] Command Line
- [ ] Dimensions and Annotations
- [ ] DXF Import / Export
- [ ] PDF and PNG Export
- [ ] 3D Modeling Engine
- [ ] Advanced Geometry Operations
- [ ] Performance Optimization

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| ESC | Cancel Command |
| CTRL + Z | Undo |
| CTRL + Y | Redo |
| CTRL + S | Save |
| CTRL + O | Open |
| Delete | Delete Selected Objects |
| Mouse Wheel | Zoom |
| Middle Mouse | Pan |

*Shortcuts are subject to implementation.*

## Contributing

Contributions, bug reports, feature suggestions, and improvements are welcome.

1. Fork this repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a Pull Request.

## License

This project is intended to use the MIT License. Add a `LICENSE` file to the repository to formally apply it.

## Credits

Created by **DrDonut DZ 999**.

Inspired by professional CAD software and engineering design workflows.

---

<p align="center">
  <b>ProCAD — Design Without Limits.</b>
</p>

<p align="center">
  Made for creators, engineers, architects, and designers.
</p>
