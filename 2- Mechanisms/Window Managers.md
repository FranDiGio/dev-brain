
### `Definition`

A **Window Manager** is a system component in the graphical user space that controls how windows are placed, moved, resized, minimized, and displayed on screen. It is responsible for the _look and behavior_ of graphical windows—but **not** for drawing widgets or controlling the entire desktop environment.

---
### `Key Ideas`

- Part of the **GUI stack** in user space.
    
- Handles:
    
    - window placement & tiling
    - focus behavior
    - borders, decorations, shadows
    - keybindings for window actions
    
- **Two main categories**:
    
    - **Stacking Window Managers** – traditional overlapping windows (e.g., Openbox, Fluxbox).
    - **Tiling Window Managers** – windows auto-arrange without overlap (e.g., i3, bspwm, AwesomeWM).
    
- In Linux, they can operate:
    
    - **Standalone**, or
    - As part of a **Desktop Environment** (GNOME Shell, KWin in KDE).
    
- On Windows or macOS, the window manager is bundled inside the OS and not replaceable.

---
### `Connected Notes`

- [[User Space Components (OS)]]