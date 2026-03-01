# KYMATIX // Obsidian Ultra
**Where Audio Meets Atmospheric Geometry**
Kymatix is a high-end, browser-based generative art engine that transforms raw audio data into complex, symmetric "paper-cut" fractals. Built with a focus on Obsidian minimalism and high-performance signal processing, it bridges the gap between digital sound and physical geometry.
## 🌑 The Obsidian Philosophy
*"Most visualizers just move to the beat. Kymatix lives inside it."*
Inspired by the intricate depth of traditional paper-cutting art, Kymatix uses CSS glassmorphism and multi-layered canvas shadows to simulate physical depth. Every line drawn is a direct result of a Fast Fourier Transform (FFT) analysis, mapping frequency bins to a a 12-point hexagonal matrix.
## ✨ Key Features
- **Obsidian UI Engine:** A "smart" edge-sensing interface that fades into the shadows during playback to keep the focus on the art.
- **Cymatic Geometry:** 12-layer symmetry logic that mimics organic snowflake patterns and mandala structures.
- **Mouse-Gravity Displacement:** Interactive 2D matrix manipulation that allows the art to "lean" toward the user's cursor in real-time.
- **Snapshot Extract:** A native high-res capture engine to export generative frames as PNG wallpapers.
- **Independent Audio Control:** A standard-compliant Pause/Resume system that manages the AudioContext state to prevent hardware drift.
## 🛠 Tech Stack & Logic
| Component | Technology | Role |
| :--- | :--- | :--- |
| **Engine** | Vanilla JavaScript | Core logic and coordinate math |
| **Processing** | Web Audio API | Real-time FFT frequency analysis |
| **Rendering** | HTML5 Canvas | High-performance 2D fractal drawing |
| **Styling** | CSS3 (Obsidian Glass) | Backdrop filters and neon "bloom" effects |
| **Typography** | Syne (Google Fonts) | Designer-centric variable typeface |
## 🧠 Geometric Logic
To maintain "human-like" code and high readability, the rendering engine follows a strict Transformation Stack:
1. **Analyze:** Capture `Uint8Array` of frequency data.
2. **Translate:** Shift the canvas origin to the center.
3. **Rotate:** Apply a `0.0015` incremental rotation constant.
4. **Displace:** Apply mouse-coordinates to the matrix for "gravity."
5. **Iterate:** Draw 12 symmetrical layers of geometry based on bass and treble intensity.
## 🚀 Getting Started
1. Clone the repository.
2. Open `index.html` in a modern browser (Brave, Chrome, or Firefox recommended).
3. Click **Initialize Audio** and upload any `.mp3` or `.wav` file.
4. Move your mouse to the edges to reveal the control hub.
