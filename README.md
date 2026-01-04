# 🚗 Drive Mad – Browser-Based Car Physics Game

**Drive Mad** is a browser-based **physics-driven car game** where players must carefully control a vehicle to pass challenging obstacles and complete levels.
Each level tests balance, timing, and precision rather than speed.

The game is fully implemented in a **single HTML file (10,000+ lines)** and runs using **WebAssembly (WASM)** for high-performance gameplay directly in the browser.

---

## 🎮 Play the Game (Live)

👉 **Play Now:**
🔗 [https://codepen.io/jaxkingofpugs-1/pen/JoYagwr](https://codepen.io/jaxkingofpugs-1/pen/JoYagwr)

*(No installation required — runs instantly in the browser)*

---

## 🧠 Game Objective

* Drive the car safely across obstacles
* Maintain balance and control
* Reach the finish point of each level
* Unlock and progress to harder levels

Failure to maintain balance or incorrect timing results in restarting the level.

---

## ✨ Key Features

* 🚘 Physics-based vehicle movement
* 🧩 Progressive level difficulty
* ⚡ High-performance WebAssembly engine
* 🖥️ Runs fully in the browser
* 🎮 Keyboard & touch input support
* 🔊 Integrated audio effects
* 🔄 Instant level restart and progression
* 📄 Single-file HTML implementation

---

## 🛠️ Technologies Used

| Category | Technology               |
| -------- | ------------------------ |
| Language | HTML5, JavaScript        |
| Engine   | WebAssembly (WASM)       |
| Graphics | WebGL                    |
| Audio    | Web Audio API            |
| Runtime  | Emscripten               |
| Input    | Keyboard / Touch         |
| Hosting  | CodePen / Static Hosting |

---

## ▶️ Running the Game Locally

Because this project uses **WebAssembly**, it must be served via an HTTP server.

### Option 1: Python HTTP Server

```bash
python -m http.server 8000
```

Open in browser:

```
http://localhost:8000
```

⚠️ Opening the HTML file directly (`file://`) will **not work** due to browser security restrictions.

---

## 🎮 Controls

| Action           | Key       |
| ---------------- | --------- |
| Accelerate       | `↑` / `W` |
| Brake / Reverse  | `↓` / `S` |
| Balance Forward  | `→`       |
| Balance Backward | `←`       |
| Restart Level    | `R`       |
| Fullscreen       | `F`       |

*(Controls may vary depending on device and browser)*

---

## 🧩 Level System

* Levels unlock **only after successful completion**
* Difficulty increases progressively
* Physics sensitivity and obstacle complexity increase with levels
* Game state and progression are internally managed by the WASM engine

---

## ⚙️ Performance & Compatibility

* Optimized for **Chrome, Edge, Firefox**
* Best experience on desktop
* Mobile browsers supported
* Uses GPU acceleration via WebGL

---

## 🚀 Deployment

The game can be hosted on any **static hosting platform**, including:

* GitHub Pages
* Netlify
* Vercel
* CodePen (currently used)

No backend or database is required.

---

## 📜 License

This project is intended for **educational, learning, and demonstration purposes**.
Refer to the `LICENSE` file for usage terms.

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome.

* Fork the repository
* Create a new branch
* Submit a pull request

---

## ⭐ Support

If you found this project useful or fun:

* ⭐ Star the repository
* 🎮 Share the game link
* 🧠 Use it for learning WebAssembly or browser game development
