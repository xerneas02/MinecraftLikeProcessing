# Minecraft-like in Processing

A small **Minecraft-like** project developed in **Processing**, featuring a 3D voxel engine where you can explore, manipulate, and generate a world built from cubes.

---

## Features

* 🌍 **Chunk Generation**

  * Infinite world divided into "chunks" (16×16×16 voxel blocks).
  * Dynamic loading and unloading of chunks around the player.

* 🧱 **Voxels & Textures**

  * Multiple block types (grass, dirt, wood, sand, water, etc.).
  * Textures loaded from a `block.png` spritesheet.

* 🚶 **Player Movement**

  * First-person camera view.
  * Smooth movement (keyboard + mouse).
  * Basic gravity and collision detection with ground and blocks.

* 🔨 **Interaction**

  * Place and remove blocks by pointing and clicking.
  * Simple ray-casting to target blocks.

* 🌿 **Environment**

  * Basic rendering of trees and foliage.
  * Simple water effect in submerged areas.

---

## Project Structure

```
processing-minecraft/
├── texture/
│   └── block.png       # Spritesheet for block textures
├── Player.pde          # Player camera control and rendering
├── Voxel.pde           # Voxel class (type, position, draw)
├── cube.pde            # Textured cube drawing module
├── Chunk.pde           # Chunk management and terrain generation
└── README.md           # This document
```

---

## Installation

1. **Download and install Processing** from [processing.org](https://processing.org).
2. Clone or download this repository into your Processing sketches folder.
3. Make sure the `data` folder containing `block.png` is in the same directory as the `.pde` files.

---

## Usage

1. Open the main sketch (`Player.pde`) in the Processing IDE.
2. Click the **Run** button (▶️) to launch the application.
3. The world will generate around you. Ready to explore!

---

## Controls

| Action        | Key / Mouse    |
| ------------- | -------------- |
| Move Forward  | `W` / `Z`      |
| Move Backward | `S`            |
| Move Left     | `A` / `Q`      |
| Move Right    | `D`            |
| Jump          | `Space`        |
| Look Around   | Mouse movement |
| Place Block   | Right click    |
| Remove Block  | Left click     |

---

## Screenshots

![](https://github.com/user-attachments/assets/37916be8-6f3e-4a31-a811-bd1d7676a63b)
*Front view of a surface chunk.*

![](https://github.com/user-attachments/assets/4d10233a-fc08-4c11-924f-4add5a56c2ae)
*Underwater exploration and special block placement.*

![](https://github.com/user-attachments/assets/7dccaf51-25de-4cfd-84ec-f2cabe30c134)
*HI*

---

## Customization

* **Textures**: Replace or add your own textures by editing `texture/block.png`.
* **Settings**: Adjust chunk size and generation parameters in `Chunk.pde`.
* **Possible Extensions**:

  * Advanced procedural generation (Perlin noise, biomes).
  * Inventory and crafting system.
  * Graphics optimizations (occlusion culling, vertex buffers).

---

## Contact

For questions or further discussion, you can reach me on 
  - discord: **xerneas02**
  - email : **xerneas1702@gmail.com**

## License

This project is released under the MIT License. Feel free to modify and redistribute.
