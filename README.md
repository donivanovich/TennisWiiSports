# 🎾 Wii Sports Tennis

A 3D tennis game developed in **Unity** as part of the 2nd-year Multiplatform Application Development (DAM) course.

## 📋 Table of Contents

- [Team Members](#-team-members)
- [Project Overview](#-project-overview)
- [Gameplay Features](#-gameplay-features)
- [Technologies](#-technologies-and-tools)
- [Assets and External Resources](#-assets-and-external-resources)
- [Project Structure](#-project-structure)
- [Controls](#-controls)
- [Development Status](#-development-status)

## 👥 Team Members

| Name | Role |
|------|------|
| Ivan Kosolovskyy Fetsyk | Developer |
| Javier Jiménez Simón | Developer |
| Mario Martínez Castro | Developer |

| Information | Details |
|-------------|---------|
| **Submission Date** | December 9, 2025 |
| **Course** | 2nd Year DAM B |
| **Group** | LES |
| **Version** | 1.2 |

## 🎮 Project Overview

**Game Title:** Wii Sports Tennis  
**Genre:** Sports / Simulation  
**Game Engine:** Unity

### Synopsis

Wii Sports Tennis is a 3D tennis game inspired by the classic Wii Sports experience.

The player controls a Mii character named **Matt**, competing in fast-paced tennis matches against an AI-controlled opponent named **Elisa**.

The game focuses on simple and intuitive controls, realistic ball physics, and an arcade-style tennis experience.

### Gameplay

- **Main Mechanics:** Player movement and racket swings with directional control.
- **Match Duration:** Approximately 20 minutes.
- **Difficulty:** Ultimate.

## ⚡ Gameplay Features

### Implemented Mechanics

- [x] **Player Movement:** Move around the court using WASD or arrow keys.
- [x] **Ball Physics:** Realistic ball movement and bouncing.
- [x] **Racket Swing System:** Hit the ball with directional control and progressive power.
- [x] **Scoring System:** Traditional tennis scoring (15, 30, 40, Game and Set).
- [x] **User Interface:** In-game scoreboard.
- [x] **Sound Effects:** Audio feedback for racket hits and ball bounces.

## 🛠️ Technologies and Tools

| Category | Technology |
|----------|------------|
| Game Engine | Unity |
| Programming Language | C# |
| IDE | Visual Studio 2022 |
| Version Control | Unity Version Control |
| Audio Resources | YouTube |

## 🎨 Assets and External Resources

The project combines custom-made assets with external 3D models and resources.

### 3D Assets

| Asset | Source |
|-------|--------|
| Tennis Racket 3D Model | [TurboSquid](https://www.turbosquid.com/es/3d-models/3d-model-tennis-racket-3d-model-realistic-sports-asset-2345659) |
| Tennis Court A3 | [TurboSquid](https://www.turbosquid.com/es/3d-models/3d-tennis-court-a3-2136003) |
| Mii Characters | Custom models created by Ivan Kosolovskyy Fetsyk |
| Tennis Ball | [TurboSquid](https://www.turbosquid.com/es/3d-models/3d-tennis-ball-lowpoly-pbr-2455752) |
| Stadium | [TurboSquid](https://www.turbosquid.com/es/3d-models/3d-stadium-gallery-1307326) |

### Tutorials and References

The following tutorials were used as learning resources during development.

| Resource | Link |
|----------|------|
| Game Development Tutorial | [YouTube Playlist](https://www.youtube.com/watch?v=mfLDmGrYHxg&list=PL9lDuR1A0BQBc5KnS2F2EUlEW-3PTHgsz) |
| Main Menu | [YouTube Tutorial](https://www.youtube.com/watch?v=f1wugS7ZfiM) |
| Audio Mixer | [YouTube Tutorial](https://www.youtube.com/watch?v=LzRyqbS0vlg&t=72s) |

### Additional Resources

**Audio Cleaning and Processing**
- [Audio Cleaner](https://audiocleaner.ai/)
- [Clipto AI](https://www.clipto.com/)

**AI Tools**
- [Perplexity](https://www.perplexity.ai/)
- [Google Gemini](https://gemini.google.com/)

> [!NOTE]
> External assets, tutorials and resources are credited to their respective creators and sources. Please refer to their original websites for licensing and usage conditions.

## 📁 Project Structure

The following tree represents the main organization of the Unity `Assets` directory.

```text
Assets/
├── Art/
│   ├── Mii/
│   │   ├── Textures/
│   │   │   ├── Brown/
│   │   │   ├── Purple/
│   │   │   ├── Skin/
│   │   │   └── White/
│   │   ├── Mii/
│   │   ├── Mii Elisa/
│   │   └── Mii Matt/
│   │
│   ├── Stadium/
│   │   ├── Textures/
│   │   └── Stadium and Gallery/
│   │
│   ├── Tennis_Ball/
│   │   ├── Textures/
│   │   ├── Rebote/
│   │   └── Tennis_Ball/
│   │
│   ├── Court/
│   ├── Menu Picture/
│   └── Racket/
│
├── Music/
│   ├── Ball Bounce/
│   ├── Hot Ball/
│   └── Menu Theme/
│
├── Scenes/
│   ├── Main/
│   └── SceneMenu/
│
└── Scripts/
    ├── Bola/
    ├── Bot/
    ├── LimitesCampo/
    ├── Menu/
    └── Mover/
```

> [!NOTE]
> This structure shows the main project assets and folders. Individual Unity files, textures and other supporting resources have been omitted for readability.

## 🎮 Controls

| Action | Keyboard / Input | Description |
|--------|------------------|-------------|
| Move Left | A / ← | Move the player to the left. |
| Move Right | D / → | Move the player to the right. |
| Move Forward | W / ↑ | Move the player forward. |
| Move Backward | S / ↓ | Move the player backward. |
| Right Swing | Right Mouse Button | Perform a racket swing. |
| Left Swing | Left Mouse Button | Perform a racket swing. |

> [!TIP]
> Combine player movement with directional racket swings to position yourself and control your shots more effectively.

## 🚧 Development Status

| Property | Value |
|----------|-------|
| **Current Version** | 1.2 |
| **Last Update** | December 9, 2025 |
| **Development Status** | Completed project |

> [!WARNING]
> This project was developed as an academic assignment. It is not an official Nintendo or Wii Sports product and is not affiliated with or endorsed by Nintendo.

---

*Developed with Unity and C# by Ivan Kosolovskyy Fetsyk, Javier Jiménez Simón and Mario Martínez Castro.*
