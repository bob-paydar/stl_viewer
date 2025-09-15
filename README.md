# 3D STL Viewer

A lightweight, single-file 3D STL Viewer built with **Three.js**.  
It allows you to load, inspect, and measure STL models directly in the browser — no installation required.

---

## ✨ Features

- **Windows 10 UI styling**  
  Flat gradients, Segoe UI font, ribbon-like command bar, and Win10 accent color.

- **STL Import & Reset**  
  - Open local `.stl` files via a file picker.  
  - Reset camera to fit the model.  
  - Close/remove the current file.

- **Projection & View Controls**  
  - Switch between **Perspective** and **Orthographic** projection.  
  - Quick camera presets: Top, Bottom, Front, Back, Left, Right.

- **Object Color Customization**  
  - Change the mesh color using a color picker (default is dark green).

- **Measurements**  
  - Automatically displays **Length (X)**, **Width (Y)**, and **Height (Z)**.  
  - Dimension lines and labels appear around the object.  
  - Status bar also shows L/W/H values.

- **Scene Alignment**  
  - Stage/grid lines placed at **Z = 0**.  
  - Model automatically centered in X/Y and placed with its base on Z=0.  
  - Bottom view aligns to Z=0 plane.

- **Status Bar & About Dialog**  
  - Shows model info, app status, and programmer name.  
  - “About” dialog with project info and credits.

---

## 📂 File Structure

- `stl_viewer.html` — main single-file application.  
- `README.md` — this documentation.

---

## 🚀 Usage

1. Open the `stl_viewer.html` file in any modern browser (Edge, Chrome, Firefox).
2. Click **Open STL** and select an `.stl` file.
3. Use the mouse to:
   - **Left-drag** → orbit.  
   - **Right-drag** → pan.  
   - **Scroll** → zoom.
4. Explore the menus for projection modes, view presets, and color options.

---

## 🛠️ Tech Stack

- [Three.js](https://threejs.org/) — rendering engine.  
- [STLLoader](https://threejs.org/docs/#examples/en/loaders/STLLoader) — STL parsing.  
- Vanilla HTML/CSS/JavaScript — no build tools required.

---

## 👤 Credits

Programmed by **Bob Paydar**  

---

## 📜 License

This project is distributed as-is, free for personal and educational use.
