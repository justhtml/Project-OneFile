# Project-OneFile

A collection of **single-file HTML programs**.

Each program is **exactly ONE `.html` file** that runs independently by opening it in a browser.
There are no build steps, no installers, and no shared code between programs.

---

## How to Run
1. Open this repository
2. Navigate to any folder under `apps/`
3. Download a `.html` file
4. Open it in your browser (double-click)

Works offline by default, unless a program explicitly uses online assets.

---

## Core Rule
**ONE program = ONE file**

- Each `.html` file is a complete program
- HTML only
- CSS must be inside `<style>`
- JavaScript must be inside `<script>`
- Programs must run by simply opening the file

---

## Folder Structure
apps/
├─ game/ # board games, chess variants, gomoku, etc.
├─ minecraft/ # minecraft-inspired experiments
├─ simulation/ # physics, math, fluid, and visual simulations
├─ program/ # small interactive programs
├─ tools/ # utilities, viewers, trainers

Folders are **only for organization**.  
Each file inside them is still an independent program.

---

## Programs

Each program below is a **single, independent HTML file**.
Open the file in a browser to run it.

---

### 🎮 Game

- **3 Player Gomoku**  
  A three-player variant of Gomoku that is very fair for evey player.

- **4 Player Chess**  
  A four-player chess implementation with an expanded board and turn system.

- **Chaturaji**  
  An ancient four-player Indian chess variant featuring alliance mechanics.

- **Chess Side by Side**  
  Two chess boards displayed simultaneously for comparison or analysis. Two-player.

- **Go**  
  A playable implementation of the board game Go in a single HTML file.

- **Gomoku (Dual Boards)**  
  Gomoku played on two boards at once.  Two simultaneous two-player Gomoku games (4 players total).

- **Horde Chess (Side by Side)**  
  A Horde Chess variant displayed across multiple boards. Two-player.

- **Infinite Chess**  
  A chess experiment with an unbounded or dynamically expanding board.

- **Janggi**  
  An implementation of Korean chess (Janggi).

- **Chess Variants (WIP Collection)**  
  A work-in-progress collection of experimental chess variants.

- **Quoridor**  
  A playable implementation of the strategy board game Quoridor.

- **Raumschach (3D Chess)**  
  A 3D chess variant played across multiple layers.

- **Renju / Gomoku**  
  A Renju-style Gomoku implementation with rule restrictions.

---

### 🧱 Minecraft

- **Chess Minecraft**  
  A hybrid experiment combining chess logic with Minecraft-style visuals.

- **Minecraft**  
  A basic Minecraft-inspired sandbox experiment.

- **One Chunk Prototype**  
  A Minecraft-style world restricted to a single chunk for experimentation. 

- **Steve Skin Check**  
  A tool to preview and test Minecraft-style character skins.

---

### 🧠 Program

- **Code Indenter / Dedenter**  
  A utility for indenting or dedenting code.

- **Learn Everything**  
  An experimental interactive learning or knowledge interface.

- **Memory Game**  
  Multiple games for improving memory.

- **Next Button Predictor**  
  A playful experiment attempting to predict user button clicks.

---

### 🌌 Simulation

- **2D Buoyant Thermal Plume**  
  A 2D fluid simulation of buoyant thermal flow.

- **2D Mushroom Cloud (Buoyant Blast)**  
  A buoyant explosion-style fluid simulation inspired by mushroom clouds.

- **2D Navier–Stokes Toroidal Vortex**  
  A Navier–Stokes simulation showing vortex ring behavior.

- **2D Smoke Fluid Simulation**  
  A 2D smoke simulation based on fluid dynamics.

- **4D Tesseract Explorer**  
  A visualization of a 4D hypercube projected into lower dimensions.

- **5D Penteract Explorer**  
  A higher-dimensional hypercube visualization experiment.

- **Beautiful Like Wind**  
  A visual simulation focused on aesthetic motion and flow.

- **Black Hole (Mobile Improved)**  
  A gravity-based visualization inspired by black holes, optimized for mobile.

- **CFD Research Sandbox**  
  A sandbox environment for computational fluid dynamics experiments.

- **Flatland Prototype**  
  A simulation inspired by *Flatland*, exploring lower-dimensional worlds.

- **Mandelbrot, Mandelbrot Shutter**  
  An interactive Mandelbrot set explorer.

- **Music Visual (2D)**  
  A 2D music-reactive visualization.

- **Navier–Stokes Fluid Simulation**  
  A general-purpose Navier–Stokes fluid dynamics visualization.

- **Rubik’s Cube**  
  A Rubik’s Cube visualization or interaction experiment.

- **Schlieren Fluid Lab**  
  A schlieren-style visualization of fluid density gradients.

- **Three Body Problem, Disco Butterfly**  
  A simulation of chaotic motion in a three-body gravitational system.

- **Game Vector Normalization Simulator**  
  A visualization of vector normalization in game-development contexts.
  
---

### 🛠 Tools

- **Card Counter Trainer**  
  A training tool for practicing card counting.

- **Dual HTML Player**  
  A tool for displaying or comparing two HTML files side by side.

- **Online HTML Viewer (1 / 2 / 3)**  
  Progressive versions of a simple HTML viewing tool.

- **NATO Phonetic Trainer**  
  A trainer for learning the NATO phonetic alphabet.

- **Snake in the Title Bar**  
  A playful experiment rendering a snake game in the browser title bar.

- **Unity Sandbox**  
  A Unity-like sandbox experiment implemented in HTML.

- **Unity Sandbox with AI**  
  An extended sandbox experiment including AI behavior.

---

## Bugs & Issues

Some programs are experiments and may contain bugs.

If you find an issue, please open a GitHub Issue and include:
- file name
- what you expected vs what happened
- browser + OS
- screenshot if possible

---

## Improvements Wanted

Possible future improvements:
- Better mobile support (some programs already support mobile)
- Clear instructions at the top of each file
- UI and performance refinements
- Code cleanup

---

## Browser Support
- Tested mainly on Chrome
- Other modern browsers should work, but are not guaranteed

---

## Contributing
Feel free to fork the repository and submit pull requests.

Please respect the core rule:  
**one program must remain one independent HTML file.**

---

## Author
GitHub: https://github.com/HTML-is-the-best-programming-language
