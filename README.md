# 🎾 ATHARVA AI BALL CATCH

A premium, interactive browser-based physics game controlled entirely by your webcam and AI hand tracking. Built with a futuristic AAA glassmorphism UI, neon visuals, and highly optimized JavaScript.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Build](https://img.shields.io/badge/build-passing-brightgreen.svg)
![Tech Stack](https://img.shields.io/badge/tech-HTML5%20%7C%20Canvas%20%7C%20MediaPipe-bc13fe)

## ✨ Features

* **Neural Hand Tracking:** Uses Google's MediaPipe Tasks Vision to accurately track your index finger in real-time.
* **No Controllers Needed:** Your hand is the controller. Simply wave your hand in front of your webcam to move the paddle.
* **High-Performance Rendering:** 
  * Consistent 60 FPS target.
  * Custom Object Pooling for particles and trails to prevent Garbage Collection stutters.
  * Pre-rendered cached Canvas assets for glow effects.
* **Premium Game Feel:** Features screen shake, slow-motion impact frames on milestones, dynamic hit sparks, motion blur trails, and adaptive camera input smoothing.
* **Futuristic UI:** Implements a modern glassmorphism HUD with neon cyan, purple, and blue aesthetics.
* **Zero Dependencies:** No backend, no Node.js, no Python, and no external frameworks. Everything is bundled into a single `index.html` file.

## 🚀 How to Play

1. Allow **Camera Permissions** when prompted by your browser.
2. Step back and hold your hand up to the camera.
3. Once the AI locks onto your hand, point your **Index Finger**.
4. Move your finger left and right to control the neon paddle.
5. Keep the ball from falling off the bottom of the screen! 
6. *Hint: The ball speeds up as your score increases.*

## 🛠️ Tech Stack

* **HTML5 & CSS3** (Variables, Flexbox, Animations)
* **Vanilla JavaScript (ES6)** (Classes, Object Pooling, Game Loop)
* **HTML5 `<canvas>` API** (Physics rendering, compositing, particle systems)
* **MediaPipe Tasks Vision API** (WASM-accelerated AI hand landmark detection)

## 💻 Running Locally

Because this project uses the webcam (which requires a secure context), you cannot simply double-click the `index.html` file in some modern browsers due to `file://` protocol security restrictions. 

To run it locally:
1. Clone this repository or download the `index.html` file.
2. Open the folder in your code editor (e.g., VS Code).
3. Run a local server. If using VS Code, install the **Live Server** extension and click "Go Live".
4. The game will open in your browser at `http://localhost:5500`.

## 🌍 Deployment

This game is 100% static and client-side, making deployment incredibly easy. You can host it for free on any static hosting provider:

* **GitHub Pages:** Go to your repository settings > Pages > Deploy from `main` branch.
* **Vercel / Netlify:** Drag and drop the project folder directly into their web dashboard, or link your GitHub repository. 

*Note: Ensure your deployed site uses HTTPS, as browsers require secure origins to access user webcams.*

## 👨‍💻 Author

**Made by Atharva**
* Follow on socials: [@futurewithatharva](https://instagram.com/futurewithatharva)

---
*If you like this project, please consider leaving a ⭐ on the repository!*
