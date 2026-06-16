# ⏱️ Time Master Challenge

A complete, high-fidelity, professional browser-based game designed to test and hone a player's internal chronometer and reaction speeds. Built completely from scratch with raw, modern ES6+ vanilla JavaScript, CSS3, and HTML5. 

**Zero frameworks. Zero libraries. Zero external assets.** Everything—including the interactive performance graphs, system styling, and audio synthesis engine—is contained within a single production-ready optimization file.

---

## 🕹️ Live Demo
👉 **[Play Time Master Challenge Live Here!](https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/)**
*(Note: Replace this link with your actual GitHub Pages URL!)*

---

## 🚀 Key Features

*   **High-Precision Mechanical Timing:** Employs hardware-level timestamp queries rendering at a stable sub-millisecond execution fidelity.
*   **Procedural Web Audio API Soundscapes:** Bypasses asset latency by dynamically generating all user interface tones, success arpeggios, and game clicks via raw code audio oscillators.
*   **Dynamic Canvas Analytics Charting:** Incorporates an internal HTML5 Canvas engine mapping historical performance metrics, tracking accuracy vectors over your last 15 operational runs.
*   **Modular Glassmorphism Theme Architecture:** Implements standard responsive modern visual effects featuring dark neon aesthetics alongside a multi-theme cycle suite (Cyberpunk, Matrix, default Classic-Glow).
*   **Persistent LocalStorage Indexing:** Persists user achievement logs, win-streaks, average error deviations, and historical tracking metrics flawlessly across tab reloads.

---

├── 🧠 Game Engine          -> Core runtime manager orchestrating state variables loop.
├── ⏱️ Timer Manager       -> High-fidelity window.requestAnimationFrame timing processor.
├── 📊 Score Manager       -> Advanced mathematical evaluation accuracy matrix.
├── 🏆 Achievement Manager -> Validation checkpoint pipeline parsing progression benchmarks.
├── 💾 Storage Manager     -> Encapsulated LocalStorage memory state manager layer.
├── 🎨 UI / Theme Switcher -> Dynamic DOM mapper & client CSS properties toggle layer.
└── 🔊 Audio Manager       -> Real-time synthesizer binding custom browser AudioContext nodes.

---

### 🔬 Core Precision Calculations

To bypass standard CPU throttle latency common with traditional `setInterval` clocks, the core engine samples exact hardware cycle differentials.

The absolute percentage accuracy calculation matrix maps linearly relative to the targeted duration:

$$\text{difference} = | \text{targetTime} - \text{stoppedTime} |$$

$$\text{accuracy} = \max\left(0, \left(1 - \frac{\text{difference}}{\text{targetTime}}\right) \times 100\right)$$

---

## 📊 Evaluation Metrics Matrix

| Deviation Window (Seconds) | Rank Badge Evaluation | Visual Identity Indicator |
| :--- | :--- | :--- |
| **0.00s – 0.05s** | `PERFECT` ⭐⭐⭐⭐⭐ | Neon Emerald Glow |
| **0.05s – 0.10s** | `AMAZING` ⭐⭐⭐⭐ | Hyper Cyber Cyan |
| **0.10s – 0.20s** | `GREAT` ⭐⭐⭐ | Electric Blue |
| **0.20s – 0.50s** | `GOOD` ⭐⭐ | Warm Amber |
| **0.50s – 1.00s** | `OK` ⭐ | Crimson Alert |
| **Above 1.00s** | `MISS` ❌ | Solid Crimson |

---

## 🔓 Unlockable Achievements

The internal achievement pipeline monitors runtime parameters continuously to flag and persist milestones into your structural local player index:
*   **First Win:** Complete any operational cycle within a standard `0.50` second error threshold.
*   **5 Perfect Scores:** Maintain pristine structural timing by lodging 5 absolute `PERFECT` runs.
*   **10 Game Streak:** Maintain a continuous sequence of success over a 10-round stretch without registering a single `MISS`.
*   **Time Master:** Successfully resolve operational target configurations inside the high-velocity `1 - 60s` **Insane Mode**.
*   **Precision King:** Hit extreme timeline precision matching benchmarks crossing a **> 99.8%** threshold.

---

## 🛠️ Development & Local Environment Deployment

Since the game requires absolutely no external dependencies or bundle compilers, managing development runs locally is perfectly straightforward.

1. Clone this repository locally to your computer:
```bash
   git clone [https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git](https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git)

2. Navigate directly to the directory and run it inside your browser framework:

cd YOUR-REPOSITORY-NAME
   open index.html

📄 License
This repository is distributed and maintained under the permissive MIT License. Check out the accompanying LICENSE document file inside the root repository directory for additional details.

## ⚙️ Technical Blueprint Architecture

The codebase is engineered strictly around clean, decoupled, structural object-oriented modules separating distinct domain responsibilities:
