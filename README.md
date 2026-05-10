# 🐕 Interactive 3D Dogstudio Clone

A high-performance, immersive web experience built with **React**, **Three.js (React Three Fiber)**, and **GSAP**. This project explores the intersection of 3D graphics and narrative web design, featuring interactive model transitions and scroll-driven animations.
 
<p align="center">
  <img src="https://github.com/user-attachments/assets/34e0cb1a-cfa4-4d3b-8cce-2ca2d9bf72cc" width="800" alt="Dogstudio Clone Preview">
</p>

## 🚀 Live Demo
[Check it out here]:https://react-dogstudio-clone.vercel.app/

## 🛠️ Tech Stack
- **Frontend:** React.js
- **3D Engine:** [React Three Fiber](https://r3f.docs.pmnd.rs/) (Three.js wrapper for React)
- **3D Utilities:** [Drei](https://github.com/pmndrs/drei)
- **Animation:** [GSAP (GreenSock Animation Platform)](https://gsap.com/) with ScrollTrigger
- **Styling:** CSS / SCSS (Nested)

## ✨ Key Features

### 1. Interactive Matcap Transitions
Used a custom shader implementation via `onBeforeCompile` to blend between multiple **Matcap textures**. The dog model transitions its material based on hover states of the project list, providing instant visual feedback.

### 2. Scroll-Driven Storytelling
Leveraged **GSAP ScrollTrigger** to synchronize the 3D scene with the DOM.
- **Dynamic Camera Positioning:** The dog moves on the Z and X axes to create depth as the user scrolls.
- **Scrubbed Animations:** Every 3D transformation is mapped to the scroll bar for a smooth, tactile feel.

### 3. Optimized 3D Assets
- **GLTF/GLB Models:** Used Draco compression for fast asset delivery.
- **Texture Management:** Optimized normal maps and Matcaps to ensure a high frame rate (60FPS) even on mobile devices.

## 📦 Installation

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/your-username/React-Dogstudio-Clone.git](https://github.com/your-username/React-Dogstudio-Clone.git)
   ```
2. **Install dependencies:**

```bash
npm install
```
Run the development server:
```bash
npm run dev
```

## 🧠 What I Learned
- Managing the lifecycle of 3D objects within the React component tree.
- Injecting custom GLSL code into standard Three.js materials.
- Coordinating complex GSAP timelines with fixed 3D backgrounds and scrolling HTML content.

## 🤝 Credits
- Inspiration: [Dogstudio](https://dogstudio.co/)

---
Developed with ❤️ by Saloni
