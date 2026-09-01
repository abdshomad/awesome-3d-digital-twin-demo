# 🌐 Awesome 3D Digital Twin Demo

A curated collection of cutting-edge **3D Digital Twin**, **3D Gaussian Splatting (3DGS)**, **Geospatial Visualization**, **Global Situational Awareness**, and **Real-Time Simulation** projects.

---

## 📦 Included Demos & Submodules

| Project | Description | Tech Stack |
| :--- | :--- | :--- |
| [**God's Eye View**](https://github.com/abdshomad/gods-eye-view) | Real-time browser-based spy-satellite simulator and global digital twin tracking aircraft, ships, satellites, earthquakes, cameras, and AI voice control. | CesiumJS, WebGL, AI Agents, Live APIs |
| [**OSIRIS**](https://github.com/abdshomad/osiris) | Open Source Intelligence & Reconnaissance Integrated System aggregating live flights, CCTV networks, earthquake monitoring, conflict zones, and news. | Next.js, MapLibre GL, TypeScript |
| [**World Monitor**](https://github.com/abdshomad/worldmonitor) | Real-time global situational awareness and intelligence dashboard with AI news aggregation and geopolitical/infrastructure tracking. | TypeScript, MapLibre GL, AI APIs |
| [**Cesium Flight Simulator**](https://github.com/abdshomad/cesium-flight-simulator) | Interactive 3D flight and ground vehicle simulator across real-world global terrain with multi-camera modes and minimap. | CesiumJS, React, TypeScript, Mapbox |
| [**Cesium Philadelphia Tour**](https://github.com/abdshomad/cesium-tutorial-build-a-philadelphia-tour-with-cesiumjs-using-ai) | Interactive guided 3D geospatial city tour built with CesiumJS using modern AI-driven development workflows. | CesiumJS, Vite, TypeScript, Docker |
| [**GenRecon**](https://github.com/abdshomad/GenRecon) | Multi-view 3D scene reconstruction bridging generative diffusion priors with neural representations for sparse input views. | PyTorch, Neural Rendering, Diffusion |
| [**Slang-Splat**](https://github.com/abdshomad/slang-splat) | High-performance 3D Gaussian Splatting renderer and trainer powered by Slang compute shaders and Slangpy targeting Vulkan and CUDA. | Slang, Slangpy, Vulkan, PyTorch, C++ |
| [**Slang-Splat Demo Stack**](https://github.com/abdshomad/slang-splat-demo-jul-2026) | Full-stack Dockerized orchestration for deploying interactive web demos of Slang-Splat 3D Gaussian Splatting. | Docker Compose, NVIDIA Container Toolkit |

---

## 🚀 Getting Started

### 1. Clone Repository with Submodules

To clone this repository and initialize all submodules at depth 1:

```bash
git clone --recursive --depth 1 https://github.com/abdshomad/awesome-3d-digital-twin-demo.git
cd awesome-3d-digital-twin-demo
```

If you have already cloned the repository without submodules, initialize them with:

```bash
git submodule update --init --recursive --depth 1
```

### 2. Updating Submodules

To pull the latest commits for all submodules:

```bash
git submodule update --remote --merge
```

---

## 📂 Repository Structure

```text
awesome-3d-digital-twin-demo/
├── .gitmodules
├── AGENTS.md                                                       # Agent rules (never modify submodule files)
├── README.md
├── cesium-flight-simulator/                                        # Cesium React flight simulator
├── cesium-tutorial-build-a-philadelphia-tour-with-cesiumjs-using-ai/ # CesiumJS Philadelphia tour
├── GenRecon/                                                       # Multi-view 3D scene reconstruction
├── gods-eye-view/                                                  # Real-time satellite & live data digital twin
├── osiris/                                                         # OSINT & live global reconnaissance dashboard
├── slang-splat/                                                    # Slang/Vulkan 3D Gaussian Splatting engine
├── slang-splat-demo-jul-2026/                                      # Dockerized Slang-Splat web demo stack
└── worldmonitor/                                                   # Global situational awareness dashboard
```

---

## 📜 Guidelines

See [AGENTS.md](file:///home/aiserver/LABS/DIGITAL-TWIN-3D/awesome-3d-digital-twin-demo/AGENTS.md) for repository guidelines and submodule isolation rules.
