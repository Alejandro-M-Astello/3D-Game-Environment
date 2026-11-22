# 3D Game Environment

An interactive 3D real-time graphics and shooter environment built in C++ featuring custom 3D models, spatial audio, camera navigation, and rendering logic.

## Features
- **3D Scene & Object Rendering:** Loads and renders custom 3D meshes and environment assets (`Objects/`) with camera movement and coordinate transforms.
- **Interactive Gameplay & Logic:** Real-time object positioning, collision/interaction handling, and frame updates (`Application/`).
- **Audio Integration:** Spatial sound effects and background audio playback (`wav/`).
- **Modular Engine Architecture:** Separates application logic (`Application/`) from core windowing, rendering, and input management (`Framework/`).

## Tech Stack
- **Language:** C++
- **Graphics & Audio:** DirectX 9 (`D3dx9_43.dll` / DirectX SDK) & Windows Multimedia (`wav/` audio, custom 3D mesh assets)
- **IDE:** Visual Studio (`Demo 5.sln`)

## How to Build & Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Alejandro-M-Astello/3D-Game-Environment.git
   ```
2. Open Demo 5.sln in Visual Studio

3. Ensure the DirectX SDK (June 2010) include/library paths are configured in project properties if building on a fresh machine

4.   Set the build configuration to debug or release (Win32/ x86) and press Ctrl + F5 to build and run