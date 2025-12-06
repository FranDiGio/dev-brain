
### `Definition`

User Space vs Kernel Space refers to the **two execution environments** in a modern operating system. **Kernel Space** is the privileged region where the kernel runs and manages hardware, while **User Space** is the restricted environment where applications execute without direct hardware access.

---
### `Key Ideas`

- **Privilege Levels:**  
    Kernel space runs with full system privileges; user space runs with restricted permissions to maintain safety.
    
- **Memory Separation:**  
    User programs cannot access kernel memory; attempts cause faults. The kernel enforces strict boundaries.
    
- **System Calls as the Bridge:**  
    User applications cannot perform privileged operations directly. They request them via system calls, which transition execution into kernel space.
    
- **Stability & Security:**  
    Crashes in user space only affect the specific process, while crashes in kernel space can bring down the entire OS.
    
- **Execution Model:**  
    User processes execute normal instructions; privileged instructions (I/O, memory control, hardware access) are reserved for kernel space.

---
### `Connected Notes`

- [[Operating System (OS)]]
- [[Kernel Responsibilities]]