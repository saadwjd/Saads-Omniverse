# Saads-Omniverse
A high-performance, audio-reactive 3D particle system controlled by real-time hand gestures. Built with Three.js and MediaPipe.
Saad's Omniverse is an immersive digital environment that bridges the gap between human gesture and generative art. By leveraging Computer Vision, the system tracks 21 hand landmarks to translate physical movements into 3D space, allowing users to manipulate thousands of particles with god-like precision.

The system features three distinct modes of interaction:

Geometric Manipulation: Uses skeletal hand tracking to toggle between complex mathematical geometries (Sphere, Heart, and the Saturnian Ring system).

Spatial Depth & Scaling: Implements Z-axis mapping to allow users to "push" or "pull" objects through the digital void, with pinch-to-scale mechanics for volume control.

Presence-Aware Physics: Features a custom state-machine that dissolves the system into entropy (random chaos) when no user is detected, reconstituting the universe only upon a "Fist" command.

## ✨ Features
- **Gesture Recognition:** Control shapes (Sphere, Heart, Saturn) using hand tracking.
- **3D Interaction:** Move your hand in the Z-axis to control depth and use pinches to scale the universe.
- **Audio-Reactive:** Particles pulse and shift color based on live microphone frequency data.
- **Presence Detection:** The universe dissolves into chaos when you leave and reformulates when you return.

## 🛠️ Tech Stack
- **JavaScript (ES6+)**
- **Three.js** (WebGL 3D Rendering)
- **MediaPipe** (Machine Learning for Hand Tracking)
- **Web Audio API** (Real-time frequency analysis)

## 🚀 How to Run
1. Clone the repository.
2. Open `index.html` in any modern web browser.
3. Grant Camera and Microphone permissions to interact.
