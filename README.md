# 🎅 Santa Dash: Ultra Edition

A high-speed, arcade-style holiday runner built with pure HTML5 Canvas and modern CSS. Dodge festive obstacles, level up your speed, and compete for the highest score in a sleek, glassmorphism-styled environment.

**Live Demo:** [https://derrickrichard.github.io/santadash/](https://derrickrichard.github.io/santadash/)

---

## ✨ Features

-   **High-Performance Engine**: 60FPS rendering using HTML5 Canvas with dynamic particle trail effects.
-   **Glassmorphism UI**: Modern aesthetic featuring backdrop blurs, neon gradients (`#00f2ff`, `#ff2e63`), and smooth transitions.
-   **Persistent Config**: Saves your **Difficulty** (Casual, Pro, Insane) and **Graphics** settings to `localStorage` so they stay the same every time you play.
-   **Smart Sharing**: 
    -   **Mobile**: Uses the native Web Share API to open your messaging apps directly.
    -   **Desktop**: Automatically copies a formatted challenge message and link to your clipboard.
-   **Zero-Refresh Loop**: Unlike basic web games, this uses a custom `resetGame()` logic that restarts the loop instantly without reloading the page.
-   **Responsive Input**: Optimized for both Keyboard (Arrow keys) and Mobile (On-screen touch controls).
-   **Embedded Assets**: Uses a Data-URI SVG favicon, making the entire game a portable, single-file application.

---

## 🎮 How to Play

1.  **Objective**: Dodge the falling obstacles (🎄, ⛄, 🎁, 🌩️, 🧊) for as long as possible.
2.  **Move**: 
    -   **Keyboard**: Use `Left Arrow` and `Right Arrow`.
    -   **Mobile**: Tap the `◀` and `▶` buttons on the screen.
3.  **Score**: You gain points for every obstacle successfully dodged.
4.  **Level Up**: The game speed increases every 100 points.

---

## 🛠️ Technical Details

-   **Architecture**: Single-file HTML5/CSS3/JS (Vanilla).
-   **Graphics**: Canvas API with `requestAnimationFrame` for stutter-free movement.
-   **State Management**: Soft-state transitions between `menu`, `game`, `options`, and `over`.
-   **Focus Management**: Automated "Focus Blurring" to prevent the Spacebar from accidentally triggering menu buttons during gameplay.

---

## 🚀 Deployment

This project is optimized for **GitHub Pages**. To host it yourself:
1. Create a repository named `santadash`.
2. Upload the `index.html` file.
3. Enable GitHub Pages in the repository settings.

---

## 📝 License
This project is open-source and free to use for festive fun!
