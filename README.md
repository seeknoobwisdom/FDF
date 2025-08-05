# 📈 FdF – Wireframe Map Renderer

`FDF` is a graphical 3D wireframe renderer built with **C** and **MiniLibX**, part of the **42 Abu Dhabi Core Curriculum**.  
It reads a 2D height map file and renders it as a 3D isometric or parallel projection with keyboard navigation and zoom.

![Language](https://img.shields.io/badge/C-100%25-blue)
![Graphics](https://img.shields.io/badge/Graphics-MiniLibX-orange)
![Status](https://img.shields.io/badge/Project-Finished-success)

---

## 🧩 About

`FDF` is a simple wireframe renderer that transforms **2D height maps** into **3D projections**.  
It teaches you how to:

- Read and parse map data
- Use **basic 3D math** (rotation, scaling, projection)
- Work with **MiniLibX** (a minimal graphical library provided by 42)
- Handle **keyboard inputs**, image buffers, and window rendering

---

## 🚀 Features

- ✅ Reads height maps from `.fdf` files
- ✅ Supports **isometric** and **parallel** projection
- ✅ Zoom, pan, rotate (X/Y/Z), reset
- ✅ Smooth real-time rendering with MiniLibX
- ✅ Color gradients (bonus)
- ✅ Interactive keyboard controls

---

consider fixing the memory leaks ;)

## 🛠 Installation

> 🧠 You need to have **MiniLibX** and **X11** or **macOS** installed

```bash
git clone https://github.com/seeknoobwisdom/fdf.git
cd fdf
make
