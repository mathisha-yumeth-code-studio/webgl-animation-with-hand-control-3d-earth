# 🌍 WebGL 3D Earth with Real-Time Hand Gesture Control

An interactive, browser-based 3D Earth globe that you can control in real-time using hand gestures via your webcam! Powered by **Three.js**, **CesiumJS**, and **Google MediaPipe** computer vision.

![Project Banner / Preview https://mathisha-yumeth-code-studio.github.io/webgl-animation-with-hand-control-3d-earth

---

## ✨ Features

- **Real-Time Hand Tracking:** Uses your webcam and Google MediaPipe to track hand movements and gestures seamlessly in the browser.
- **Interactive 3D Globe:** Smooth WebGL rendering of the Earth built with Three.js / CesiumJS.
- **Gesture Controls:** Rotate, zoom, or interact with the globe dynamically without touching your mouse or keyboard.
- **Zero Installation for End Users:** Runs completely client-side right inside a modern web browser.

---

## 🚀 Tech Stack

- **Graphics & 3D:** [Three.js](https://threejs.org/) / [CesiumJS](https://cesium.com/) / WebGL
- **Computer Vision / AI:** [Google MediaPipe](https://mediapipe.dev/) (Hands)
- **Frontend:** HTML5, CSS3, JavaScript

---

## 📂 Project Structure

```text
webgl-animation-with-hand-control-3d-earth/
│
├── textures/           # Earth maps, bump maps, cloud layers, and space backgrounds
│   ├── earthmap.jpg
│   ├── earthbump.jpg
│   └── ...
│
├── index.html          # Main HTML entry point and UI layout
├── style.css           # Styling for the canvas and HUD elements
├── main.js             # Core logic: Three.js scene, camera, lights, and render loop
└── handTracking.js     # MediaPipe webcam integration and gesture mapping logic
