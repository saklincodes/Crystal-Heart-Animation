# 💖 Crystal Heart 3D Animation

A mesmerizing, interactive 3D Crystal Heart WebGL experience built with **Three.js**, **GLSL Shaders**, **GSAP**, and the **Web Audio API**. Featuring audio-reactive particle dynamics, custom shaders, dynamic lighting, and responsive camera motion.

Created by **[@saklin_01](https://github.com/saklincodes)**.

---

## ✨ Features

- **💎 3D Crystal Heart Core**: High-detail 3D heart geometry loaded via GLTFLoader with customized Matcap crystal shading.
- **✨ Audio-Reactive Particle Outline**: Parametrically calculated heart curve rendered with custom GPU vertex shaders, pulsing and reacting to music frequencies in real time.
- **❄️ Floating Crystal Particles**: Ambient floating particles in 3D space with additive blending and custom fragment shaders.
- **🎵 Interactive Web Audio Experience**: Click-to-play audio visualizer integrating `THREE.AudioListener` and `THREE.AudioAnalyser`.
- **🖱️ Mouse Parallax Effect**: Smooth interactive camera parallax reacting seamlessly to cursor movement.
- **📱 Fully Responsive**: Fluid canvas scaling across mobile screens, tablets, and desktop displays.

---

## 🛠️ Tech Stack

- **Three.js** (r135) - 3D Scene, Camera, WebGLRenderer, GLTFLoader, Audio
- **GLSL Shaders** - Custom Vertex and Fragment Shaders for high-performance GPU particle physics
- **GSAP (GreenSock)** - Smooth animations and interactive camera transitions
- **HTML5 & CSS3** - Modern semantic layout, glassmorphic UI elements, and Google Fonts

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/saklincodes/Crystal-Heart-Animation.git
cd Crystal-Heart-Animation
```

### 2. Run Locally

Because this project uses ES Modules and GLTF models, it should be served via a local web server (to avoid CORS restrictions with local file systems):

#### Using VS Code Live Server:
- Open the project in VS Code.
- Right-click `index.html` and select **"Open with Live Server"**.

#### Using Node.js:
```bash
npx serve .
# or
npx http-server .
```

#### Using Python:
```bash
python -m http.server 8000
```

Open `http://localhost:8000` (or the URL provided by your local server) in your browser.

---

## 📂 Project Structure

```plaintext
Crystal-Heart-Animation/
│
├── index.html       # Main HTML markup and GLSL shaders
├── style.css        # Responsive styling and typography
├── script.js        # Three.js scene, particle shaders, audio analyser, and render loop
└── README.md        # Project documentation
```

---

## 🎮 Controls & Interactions

- **Play Music**: Click the floating music button to start the audio and trigger real-time audio-reactive particle pulses.
- **Mouse Movement**: Move your mouse across the screen to dynamically shift the perspective and view angle.

---

## 👤 Author

- **GitHub**: [@saklincodes](https://github.com/saklincodes)
- **Instagram / Socials**: `@saklin_01`

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
