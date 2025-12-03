# 🌊 Subnautican Adventures — Underwater Arcade Survival Game

Subnautican Adventures is a fast-paced 2D underwater arcade game built using Unity (C#).
You control a submarine navigating through dangerous ocean life — sharks, octopuses, bombs, and other obstacles — while trying to survive as long as possible and score the highest!

Inspired by the simplicity of Flappy Bird, this project introduces a fresh underwater twist, immersive visuals, and smooth, responsive gameplay.

---

## 📋 Table of Contents

- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [How to Run the Project](#how-to-run-the-project)
- [Project Structure](#project-structure)
- [Developer Notes](#developer-notes)
- [Contributing](#contributing)
- [Developed By](#developed-by)

---

<h2 id="key-features">🌟 Key Features</h2>

### 🚤 Submarine Gameplay

- Tap / Click / Spacebar controls for upward movement
- Realistic gravity-based descent
- Smooth, responsive physics for precise navigation
- Endless survival gameplay loop

### 🦈 Underwater Obstacles

- Sharks, octopus, bombs, and more animated obstacles
- Dynamic obstacle spawning
- Challenging gaps designed for fast reflexes
- Increasing difficulty over time

### 🏆 Scoring & Game Logic

- Earn points for each obstacle safely passed
- Real-time score display on screen
- Perfected collision detection
- Immediate Game Over on impact

### 🔊 Visual & Audio Immersion

- Attractive deep-ocean background with realistic lighting
- Clean UI with modern screen overlays
- Sound effects for movement, collisions, and interactions
- Smooth 2D animations for submarine and enemies

---

<h2 id="tech-stack">🛠️ Tech Stack</h2>

| Component | Technology |
|-----------|-----------|
| **Engine** | Unity (2D Mode) |
| **Language** | C# |
| **IDE** | Visual Studio / VS Code |
| **Platform** | Windows |
| **Assets** | Custom sprites, underwater backgrounds, animated obstacles |
| **Physics** | Unity Rigidbody2D & Collider2D system |

---

<h2 id="how-to-run-the-project">🚀 How to Run the Project</h2>

Follow these steps to run Subnautican Adventures on your system.

### ✅ 1. Prerequisites

Make sure you have:

- Unity installed (2021+ recommended)
- Visual Studio / VS Code with C# support
- A Windows PC (or Mac if exporting cross-platform)

### ✅ 2. Clone the Repository

```bash
git clone https://github.com/Sana-ai-coder/Subnautican-Adventures.git
cd Subnautican-Adventures
```

### ✅ 3. Open the Project in Unity

1. Open Unity Hub
2. Click **Open Project**
3. Select the folder containing the project
4. Unity will load:
   - Scenes
   - Scripts
   - Sprites
   - Obstacles
   - UI elements

### ✅ 4. Run the Game

1. Open the main gameplay scene
2. Click the **Play ▶️** button in Unity

### ✅ 5. Build the Game (Optional)

1. Go to **File → Build Settings**
2. Select **Windows**
3. Click **Build**

---

<h2 id="project-structure">📂 Project Structure</h2>

```
Subnautican-Adventures/
├── Assets/
│   ├── Scripts/                # C# scripts (player, obstacles, score system)
│   ├── Sprites/                # Submarine, sharks, octopus, bombs
│   ├── Scenes/                 # Main game scene & UI scenes
│   ├── UI/                     # Score display, game over screen
│   └── Audio/                  # SFX & background music
├── ProjectSettings/            # Unity project settings
├── Packages/                   # Unity package files
└── README.md                   # Documentation
```

---

<h2 id="developer-notes">📝 Developer Notes</h2>

- Built as a college mini-project for understanding game development
- Developed using iterative testing and player feedback
- Designed to improve reflexes, timing, and hand-eye coordination
- Smooth 60 FPS performance at 1920×1080
- Gravity: 9.8, matching realistic downward motion
- Obstacle gaps dynamically vary to increase difficulty
- The project follows a clean block-based internal architecture (Player Controller → Obstacle Generator → Scoring System)

---

<h2 id="contributing">🤝 Contributing</h2>

Want to improve the project?

1. **Fork the repository**

2. **Create a new branch**
   ```bash
   git checkout -b feature/NewImprovement
   ```

3. **Commit your changes**
   ```bash
   git commit -m "Add new feature in gameplay"
   ```

4. **Push the branch**
   ```bash
   git push origin feature/NewImprovement
   ```

5. **Open a Pull Request**

---

<h2 id="developed-by">👨‍💻 Developed By</h2>

**Sana Girish**  