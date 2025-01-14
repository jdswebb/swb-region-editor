## SWB Region Editor for SWGEmu

The **SWB Region Editor** is a standalone tool for creating and editing regions for SWGEmu. It is based on an old (2018) version of the full SWB editor that I have recovered and polished up due to the utility it provided.

SWB is powered by a custom engine that can parse and render most SWG files effectively.

## Screenshots

![image](https://github.com/user-attachments/assets/b958acad-18fb-46fe-a78a-f66397ad44c6)
![image](https://github.com/user-attachments/assets/8333de4f-7613-46ce-83c5-6f965db727b2)

## Shortcuts

### General
- **1**: Switch to Translate gizmo
- **2**: Switch to Scale gizmo
- Drag from the icons on the left to place a new region

### Perspective camera:
- **Shift**: Toggle movement speed
- **E/Q**: Move up/down
- **W/S/A/D**: Move forward/backward/left/right
- **Right-click**: Rotate the camera

### Orthographic camera:
- **Shift**: Toggle movement speed
- **E/Q**: Zoom in/out
- **W/S/A/D**: Translate view
- **Right-click**: Translate view

## Credits

This project wouldn’t have been possible without the contributions of the **SWGEmu** and **MTG** teams, both past and present. 

## Libraries used

The SWB Region Editor relies on the following open-source libraries. License details can be found at their respective URLs:

 - https://github.com/turanszkij/WickedEngine - Uses shaders from an old version of this excellent engine
 - https://github.com/ocornut/imgui - GUI
 - https://github.com/nothings/stb - Utilities for image loading and processing
 - https://github.com/glfw/glfw - Handles windowing and input
 - https://github.com/skypjack/entt - Entity Component System (ECS) framework
 - https://github.com/microsoft/DirectXTex - Texture loading
 - https://github.com/uxlfoundation/oneTBB - Threading/task system
