# ⏳ ChronoWeave: Hands-First Spatial Time Puzzle

> **Meta VR Start Developer Competition 2026 Entry** — Built for the **Gaming** Track (New Experience Division).

![ChronoWeave Banner](https://img.shields.io/badge/Meta%20VR%20Start-2026-blue?style=for-the-badge)
![WebXR](https://img.shields.io/badge/WebXR-Immersive%20Web%20SDK-orange?style=for-the-badge)
![Three.js](https://img.shields.io/badge/Three.js-Spatial%20Engine-green?style=for-the-badge)

**ChronoWeave** is a hands-first, seated spatial diorama and time-manipulation puzzle designed for Meta VR Glasses and Meta Quest devices. Conduct time with your bare hands: pinch to scrub history backward and forward, and anchor broken infrastructure outside of time in glowing gold.

---

## 🎮 Core Mechanics
* **Bimanual Time Scrubbing:** Grab the glowing temporal ribbon with your right hand and slide left/right to weave time.
* **Temporal Anchoring (Time-Locking):** Reach into the miniature diorama with your left hand and pinch bridge shards to freeze them outside of normal time.
* **Controller-Free UI:** Summon spatial wrist menus with a flat palm gesture or poke interactive holographic buttons.
* **Ergonomic Seated Design:** Fully optimized for a 2-foot seated radius (*Airplane Seat Test*).

---

## 🛠️ Tech Stack
* **Framework:** Meta Immersive Web SDK (`@iwsdk/core`)
* **Rendering Engine:** Three.js[cite: 5, 8] & WebXR API
* **Audio:** Procedural Web Audio API Spatial Synthesizer
* **State Management:** Custom Ring-Buffer ECS Shard History

---

## 🚀 Local Development Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/chronoweave.git](https://github.com/YOUR_USERNAME/chronoweave.git)
   cd chronoweave
