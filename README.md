# 🚗 Highway Car Racing Game (OpenGL)

A visually enhanced **Highway Car Racing Game** built using **C++ and OpenGL (GLUT)**.  
The game features hard-mode traffic, side-moving enemy cars, smooth animations, and a classic arcade-style racing experience.

---

## 🎮 Features
- 🚘 Player-controlled car with smooth movement
- 🚗 Multiple enemy cars with **hard mode AI**
- ↔️ Side-moving (zig-zag) traffic for increased difficulty
- ❤️ Lives system
- 🧮 Score & best score tracking
- 🌃 Scrolling road with buildings and night environment
- 🎨 Simple 3D-style visuals using 2D OpenGL primitives
- ⚡ Smooth gameplay (~60 FPS)

---

## 🕹️ Controls

| Key | Action |
|----|-------|
| ⬅️ Left Arrow / **A** | Move Left |
| ➡️ Right Arrow / **D** | Move Right |
| **ENTER** | Start / Restart Game |
| **ESC** | Exit Game |

---

## 🛠️ Technologies Used
- **C++**
- **OpenGL**
- **GLUT / FreeGLUT**

---

## 📦 Requirements
Make sure the following are installed on your system:

- C++ Compiler (GCC / MinGW / MSVC)
- OpenGL
- GLUT or FreeGLUT

---

## ▶️ How to Compile & Run

### 🔹 On Linux / macOS
```bash
g++ main.cpp -o game -lglut -lGL -lGLU
./game
