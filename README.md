# Unity Quake-Style Movement Controller

A **Quake-style movement controller** for Unity, built using the **KinematicCharacterController (KCC) asset**

## Requirements

- Unity version 2020.3.30+  
- [KinematicCharacterController (KCC) Asset](https://assetstore.unity.com/packages/tools/physics/kinematic-character-controller-99131)
  
## Installation

1. **Install Unity** make sure you have a compatible unity version
2. **Install KinematicCharacterController** from the asset Store  
3. **Copy the files** from this repository into your Unity project
4. **Change input** in the `Player` and `PlayerCamera` scripts according to your project settings
5. **Create two gameobjects** in your scene: `Player` and `PlayerCamera` 
6. **Create another two gameobjects:**  
Player --> CameraTarget and PlayerCamera --> Camera(with MainCamera tag)
7. **Attach scripts** to the Player and PlayerCamera objects and configure the KCC settings as desired
