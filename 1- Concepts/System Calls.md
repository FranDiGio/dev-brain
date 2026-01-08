
### `Definition`

**System calls** are the **controlled mechanism** through which **user-space programs request services from the operating system kernel**.

They define how applications safely access core OS functionality without breaking isolation or security.

---
### `Key Ideas`

- **User Space ↔ Kernel Space Boundary**  
    System calls mark the formal transition point between unprivileged application code and privileged kernel code.
    
- **Controlled Privilege Escalation**  
    Applications cannot execute privileged operations directly; system calls provide the only approved path.
    
- **Foundation of OS Abstractions**  
    Core OS concepts such as processes, files, memory, and devices are accessed via system calls.
    
- **Security & Validation Point**  
    All requests are checked, validated, and authorized by the kernel before execution.
    
- **Abstraction over Hardware**  
    System calls shield applications from hardware-specific details and kernel internals.
    
- **Synchronous Interaction Model**  
    Most system calls block the calling thread until the requested operation completes or fails.
    
- **Implementation-Independent Concept**  
    While mechanisms differ across operating systems, the conceptual role of system calls is universal.

---
### `Connected Notes`

- [[Operating System (OS)]]
- [[Kernel Responsibilities]]