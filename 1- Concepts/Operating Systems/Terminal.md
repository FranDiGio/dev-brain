
### `Definition`

A **terminal** is a user-space interface that allows users to **interact with the operating system through text-based commands**. It provides the visual environment (window or console) where a shell runs, enabling command execution, automation, and system control.

---
### `Key Ideas`

- **Interface, Not a Shell**  
    A terminal displays text input/output.  
    A _shell_ runs **inside** the terminal and interprets commands.
    
- **Multiple Implementations**
    
    - Windows: Windows Terminal, CMD console
    - macOS: Terminal.app, iTerm2
    - Linux: GNOME Terminal, Konsole, xterm
    
- **User-Space Application**  
    The terminal itself has no elevated privileges; it communicates with the OS via the shell and system calls.
    
- **Scriptable & Developer-Friendly**  
    Used for running scripts, development tools, build systems, and administrative commands.
    
- **Local or Remote**  
    Terminals can connect to remote systems via SSH, giving access to shells on other machines.

---
### `Connected Notes`

- [[User Space Components (OS)]]