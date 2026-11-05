# VR Horror Game — Unity & C#

**A personally developed VR-oriented horror game prototype built with Unity, C#, and XR interaction tools.**

**Project status:** Prototype / testing

## Overview

This repository contains my personal horror game development project. I used Unity to assemble interactive 3D scenes, organize the game flow, and integrate VR-oriented interaction components and supporting C# scripts.

The project combines my own development and integration work with Unity sample components and third-party assets. Those external packages are not presented as code I authored.

## Project highlights

- **3D horror environments:** Unity scenes and environment assets for an immersive game prototype.
- **VR-oriented interactions:** XR Interaction Toolkit resources and interaction examples integrated into the project.
- **Scene organization:** Separate scenes for the main game, main menu, and scene loading.
- **C# scripting:** Project scripts for player placement and preserving components across scene loads.

> Some included packages contain example functionality. Listing them here does not mean every example is used in the finished gameplay.

## Technology stack

| Area | Technology |
| --- | --- |
| Game engine | Unity 2022.3.11f1 |
| Programming | C# |
| XR tools | Unity XR Interaction Toolkit and associated examples |
| Assets | Unity scene assets and third-party environment/gameplay packages |

## Repository structure

```text
Assets/
  Scenes/                # Main, MainMenu, SceneLoader, and other scenes
  OUT_OF_FEAR/            # Game-specific environments and XR integration files
  PlayerLoader.cs        # Player placement/scene setup script
  DontDestroyComponent.cs # Preserves a component between scene loads
  HororGame/             # Includes imported HFPS assets and example content
Packages/                # Unity package dependencies
ProjectSettings/         # Unity project settings
```

## How to open the project

1. Install **Unity Hub** and **Unity Editor 2022.3.11f1**.
2. Clone the repository:
   ```bash
   git clone https://github.com/M-Abdullah11/unity-vr-horror-game.git
   ```
3. In Unity Hub, choose **Add project from disk** and select the cloned folder.
4. Let Unity import assets and packages; review any missing dependencies or import warnings.
5. Start by inspecting the scenes under `Assets/Scenes/`. Check the project's active build scenes and XR/runtime configuration before attempting to play in VR.

**Note:** This is a prototype and has not been verified here as a plug-and-play release. Compatible XR hardware/runtime may be required for VR interactions.

## Media

Gameplay footage and screenshots will be added once the scenes and controls have been verified in the target environment.

## Development and attribution

**Personal project by Muhammad Abdullah.** I developed and assembled this game prototype and its Unity project integration. The repository also includes third-party frameworks, sample scenes, models, materials, and XR components. Attribution and redistribution rights for those dependencies remain with their respective authors and licensors.

## Contact

- [GitHub](https://github.com/M-Abdullah11)
- [LinkedIn](https://www.linkedin.com/in/muhammad-abdullah-083906415/)


- [GitHub](https://github.com/M-Abdullah11)
- [LinkedIn](https://www.linkedin.com/in/muhammad-abdullah-083906415/)
