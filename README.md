planet view 1# 🌌 3D Solar System Model & Simulation

An interactive 3D Solar System model and astronomical simulation built with Unity and the Universal Render Pipeline (URP). Explore planetary orbits, dynamically lock the camera onto celestial bodies, capture high-resolution space screenshots, and observe solar system mechanics in real time.

[![Play Online on itch.io](https://img.shields.io/badge/Play%20Online-itch.io-red?style=for-the-badge&logo=itch.io)](https://mujtabanite.itch.io/solarsystem-model)
[![Platforms](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20WebGL-blue?style=for-the-badge)](https://mujtabanite.itch.io/solarsystem-model)
[![Made with Unity](https://img.shields.io/badge/Engine-Unity%206-black?style=for-the-badge&logo=unity)](https://unity.com/)

---

## 📸 Screenshots & Showcase

![Solar System Overview](Screenshots/planet%20view%201.png)

### Planetary Views (System Overview)

| Solar System View 1 | Solar System View 2 |
| :---: | :---: |
| ![Planet View 1](Screenshots/planet%20view%201.png) | ![Planet View 2](Screenshots/planet%20view%202.png) |

| Solar System View 3 | Solar System View 4 |
| :---: | :---: |
| ![Planet View 3](Screenshots/planet%20view%203.png) | ![Planet View 4](Screenshots/planet%20view%204.png) |

| Solar System View 5 | Solar System View 6 |
| :---: | :---: |
| ![Planet View 5](Screenshots/planet%20view%205.png) | ![Planet View 6](Screenshots/planet%20view%206.png) |

### Project & Editor Hierarchy Views

| Scene Hierarchy View | Project Structure View |
| :---: | :---: |
| ![Scene Hierarchy](Screenshots/hireachy%20of%20project%20scene.png) | ![Project Structure](Screenshots/project%20structure.png) |


---

## ✨ Features

- **Orbital Physics & Revolutions**: Custom `RotateAround` component simulating smooth planetary and lunar rotations around targeted central bodies.
- **Interactive Camera Target-Lock**:
  - **Left Click**: Focuses and locks the camera view onto any clicked planet or moon in 3D space.
  - **Right Click**: Instantly resets camera view back to the default central perspective (the Sun).
- **In-Game High-Resolution Screenshot Utility**: Press `S` key anytime to save high-res PNG screenshots directly into the `Screenshots/` folder with auto-indexed filenames.
- **Dynamic Object Spawner & Projectiles**: Integrated timer-based object spawning and forward projectile kinematics with automatic distance-based destruction.
- **Universal Render Pipeline (URP)**: Vibrant space graphics using dynamic lighting, shadows, and modern materials.
- **Cross-Platform & Web Deployment**: Play in browser via WebGL or download standalone executables for Windows and macOS.

---

## 🎮 Controls

| Action | Control / Input |
| :--- | :--- |
| **Focus Planet / Moon** | `Left Mouse Click` on celestial body |
| **Reset Camera View** | `Right Mouse Click` |
| **Capture Screenshot** | `S` Key (saved to `Screenshots/`) |

---

## 🌐 How to Play Online & Downloads

### 🌐 Play Online in Browser (WebGL)
You can launch and play the simulation directly inside your browser without downloading or installing anything:
👉 **[https://mujtabanite.itch.io/solarsystem-model](https://mujtabanite.itch.io/solarsystem-model)**

---

### 💻 Downloads & Desktop Setup

#### 🪟 Windows Setup
1. Visit the itch.io page: [https://mujtabanite.itch.io/solarsystem-model](https://mujtabanite.itch.io/solarsystem-model) (or locate `Builds/Windows.zip` in the repository).
2. Extract `Windows.zip` to your computer.
3. Open the extracted folder and run `SolarSystem.exe`.

#### 🍏 macOS Setup
1. Visit the itch.io page: [https://mujtabanite.itch.io/solarsystem-model](https://mujtabanite.itch.io/solarsystem-model) (or locate `Builds/MacOs.app.zip` in the repository).
2. Unzip `MacOs.app.zip`.
3. Launch `MacOs.app`. *(Note: If macOS prompts a developer security alert, right-click `MacOs.app` and choose **Open**)*.

---

## 🛠️ Technologies & Tools Used

- **Game Engine**: Unity 6 (`6000.3.21f1`)
- **Render Pipeline**: Universal Render Pipeline (URP `17.3.0`)
- **Programming Language**: C# (`.NET / Mono`)
- **Input Architecture**: Unity New Input System (`com.unity.inputsystem`)
- **Scripting & Utilities**: Custom C# scripts for raycasting, rotation math, and player preference-based screenshot utilities
- **Build Targets**: Standalone Windows (x86_64), Standalone macOS, WebGL
- **Hosting Platform**: itch.io

---

## 📁 Project Structure

```
SolarSystem/
├── Assets/
│   ├── _Scenes/                      # Primary Solar System Unity scene
│   ├── SolarSystemAssets/            # Textures, Materials, Prefabs & Scripts
│   │   └── Scripts/
│   │       ├── LookAtTarget.cs       # Raycasting & interactive camera locking
│   │       ├── RotateAround.cs       # Orbital rotation logic around targets
│   │       ├── Projectile.cs         # Space projectile movement logic
│   │       ├── Spawner.cs            # Timed prefab instantiation
│   │       └── ScreenshotUtility.cs  # In-game screenshot capture script
│   ├── Settings/                     # URP graphic & render settings
│   └── Resources/                    # Project runtime resources
├── Builds/                           # Production platform builds
│   ├── Windows/ & Windows.zip
│   ├── MacOs.app & MacOs.app.zip
│   └── WebGL/ & WebGL.zip
├── Screenshots/                      # In-game captured high-res screenshots
└── ProjectSettings/                 # Unity metadata and version settings
```

---

## ⚙️ How to Run in Unity Editor

To inspect or edit the project source in Unity:

1. Download and install **Unity 6 (6000.3.21f1)** using [Unity Hub](https://unity.com/download).
2. Clone the repository:
   ```bash
   git clone https://github.com/MujtabaNite/SolarSystem.git
   ```
3. Open Unity Hub, click **Add**, and select the `SolarSystem` root folder.
4. Navigate to `Assets/_Scenes/Solar System.unity` and double-click to open the scene.
5. Press the **Play** button at the top of the Unity Editor to run the simulation.

---

## 👨‍💻 Credits & Acknowledgments

- **Developer**: **MujtabaNite**
- **Professor / Advisor**: **Brian Winn** — *Michigan State University (Games for Entertainment and Learning (GEL) Lab)*
