
### `Definition`

**User space** is the **restricted execution environment** where applications, utilities, and non-kernel system processes run. It is separated from kernel space to ensure stability, security, and controlled access to system resources.

---
### `Key Ideas`

- **Restricted Privileges:**  
    Programs in user space cannot directly access hardware or kernel memory.  
    They must request privileged operations through **system calls**.
    
- **Process Isolation:**  
    Each application runs in its own protected memory region, preventing crashes from affecting the whole system.
    
- **System Libraries & APIs:**  
    User programs rely on OS-provided libraries (e.g., libc, Win32 API, system frameworks) to perform common tasks.
    
- **User-Level Components:**  
    Shells, package managers, GUI environments, daemons/services, and CLI tools run entirely in user space.
    
- **Boundary with Kernel Space:**  
    User space interacts with the kernel through a strict interface to maintain security and stability.

---
### `Connected Notes`

- [[Operating System (OS)]]
- [[Windows User Space]]
- [[macOS User Space]]
- [[Linux User Space]]