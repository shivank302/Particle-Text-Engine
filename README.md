✨ Particle Text — 3D Interactive Particle Engine

A high-performance, real-time 3D particle system that morphs 10,000 particles between an animated sphere and crisp text formations. Built with vanilla JavaScript and the HTML5 Canvas API — zero dependencies, single file, instant deploy.

🌐 Live Demo: https://shivank302.github.io/Particle-Text-Engine/

🎬 Overview

Particle Text renders a dynamic, rotating 3D globe made of colorful particles. As you type into the input field, the particles smoothly transition from the sphere into the shape of your text — letter by letter, in real time. Move your cursor over the formed text to scatter the particles with a repulsion force, and double-click anywhere to return to the globe.

The entire engine runs at 60 FPS using Float32Array typed arrays for all particle data, ensuring zero garbage collection pauses even with 10,000 active particles.

🚀 Features
Feature	Description
10,000 Particles	Ultra-high density rendering for sharp, legible text formation
True 3D Engine	Full 3D coordinate system with perspective projection (FOV-based camera)
Real-Time Typing	Particles morph into text as you type — no submit button needed
Fibonacci Sphere	Default idle state uses golden-angle distribution for an organic, uniform globe
Circular Motion	Sphere particles rotate and float with orbital wobble for a living, breathing effect
Cursor Repulsion	Move your mouse over formed text to push particles away with physics-based force
Multi-Line Wrapping	Long phrases automatically wrap into multiple lines with adaptive font scaling
Responsive Design	Sphere and text scale dynamically based on screen dimensions
Retina Support	Full devicePixelRatio awareness for crisp rendering on HiDPI displays
Zero Dependencies	Single HTML file — no frameworks, no build tools, no npm
---

## 🏗️ How It Works


Input Text → Offscreen Canvas → Pixel Sampling → Target Mapping → Physics Engine → 3D Projection → Canvas Rendering


Core idea:
- Text is drawn offscreen
- Pixel data is converted into coordinates
- Each particle gets a target position
- Physics engine animates motion smoothly

---

## ⚙️ Technical Highlights

- `Float32Array` used for high-performance particle storage  
- Spring-based physics simulation  
- Perspective projection (FOV camera system)  
- Fibonacci sphere distribution for natural motion  
- Optimized render loop for 60 FPS stability  

---
🎮 Usage & Controls
Keyboard
Action	Effect
Type text	Particles morph into text
Clear input	Return to sphere
Mouse
Action	Effect
Hover text	Repel particles
Move away	Return particles
Double-click	Reset sphere

---
🏗️ Technical Architecture

Input Text → Off-screen Canvas → Pixel Sampling → Target Positions → Physics Simulation → Perspective Projection → Canvas Draw

---
📁 Project Structure
particletext/
├── index.html
└── Readme.md

---
🌐 Browser Support
Chrome 90+ ✅
Firefox 88+ ✅
Safari 15+ ✅
Edge 90+ ✅
Mobile ⚠️ (reduce particles for smooth performance)

---

## ⚡ Performance Tip

- 10,000 particles → Desktop recommended  
- 5,000 particles → Smooth on most devices  
- 20,000+ → experimental mode  

---

## 📌 Tech Stack

- JavaScript (Vanilla)
- HTML5 Canvas
- Physics Simulation
- 3D Mathematics
- Typed Arrays

---

## 📄 License

MIT License — free to use, modify, and share.

---

## 🚀 Author

Built with passion for interactive graphics and high-performance web animat

