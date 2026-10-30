# 🏫 Thejus Engineering College – Interactive Campus Tour

An interactive, top-down 2D virtual campus exploration web application built for **Thejus Engineering College** (Main Block · Ground Floor). 

Players can walk around the campus, explore decorated classrooms, labs, offices, and the courtyard, interact with lights, sit on chairs, and talk with dynamically named NPCs (Students, Teachers, HODs, Principal, and Staff).

![Project Preview](https://img.shields.io/badge/Platform-Web%20Browser-blue) ![License](https://img.shields.io/badge/License-MIT-green) ![Tech](https://img.shields.io/badge/Tech-HTML5%20%7C%20Canvas%20%7C%20JS-orange)

---

## ✨ Features

* 🗺️ **Accurate Floor Plan:** Traced layout representing the Main Block ground floor including classrooms, computer labs, library, canteen, administration rooms, and courtyard.
* 🚶 **Interactive Controls:** 
  * Full Keyboard support (`WASD` / Arrow keys)
  * Touchscreen support with on-screen virtual Joystick and buttons for mobile devices.
* 🧑‍🤝‍🧑 **Dynamic NPCs & Roles:** Encounter Students, Teachers, HODs, Principal, Receptionists, Canteen Staff, and Gardeners with unique dialogue speech bubbles.
* 💡 **Room Lighting & Furnishings:** Turn lights ON/OFF inside specific rooms and sit down on chairs/benches.
* 🎥 **Camera Views:** Toggle between full overview mode and follow-player mode, with interactive zooming.
* 👤 **Custom Player Name:** Personalized avatar tag setup via an interactive welcome gate.

---

## 🎮 How to Play / Controls

### Desktop (Keyboard & Mouse)
| Action | Key / Input |
| :--- | :--- |
| **Walk** | `W`, `A`, `S`, `D` or `Arrow Keys` |
| **Sit / Stand** | `E` (when near a chair) |
| **Toggle Room Light** | `I` (when inside a room) |
| **Toggle Camera View** | `V` (Overview / Follow) |
| **Zoom In / Out** | Mouse Scroll Wheel |

### Mobile / Touchscreen
* **Joystick:** Touch and drag the bottom-left controller to move around.
* **Action Buttons:** Tap **E** (Sit), **I** (Light), **V** (View), and **+ / −** (Zoom).

---

## 🚀 Live Demo

You can try the live interactive tour directly on GitHub Pages:
👉 **[https://boymown-ai.github.io/campus-tour/](https://boymown-ai.github.io/campus-tour/)** *(Replace with your repository link if different)*

---

## 🛠️ Installation & Local Setup

Since this project is built entirely using vanilla HTML5 Canvas and JavaScript, no complex installation or node packages are required!

1. **Clone the repository:**
   ```bash
   git clone https://github.com/boymown-ai/campus-tour.git
   ```
2. **Navigate to the directory:**
   ```bash
   cd campus-tour
   ```
3. **Run the project:**
   * Simply double-click `index.html` to open it in any modern web browser.
   * Or run a local development server using VS Code's *Live Server* extension.

---

## 📁 File Structure

```text
campus-tour/
│
├── index.html       # Single-file bundled app containing HTML structure, CSS styling, and JS Canvas engine
└── README.md        # Project documentation
```

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).