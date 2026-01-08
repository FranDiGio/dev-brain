
### `Definition`

A **process** is an **instance of a running program**, representing the unit through which an operating system **executes, schedules, and manages work**.

It encapsulates a program’s **execution state**, allocated resources, and isolation boundaries.

---
### `Key Ideas`

- **Execution Context**  
    A process includes the program code plus its runtime state: registers, program counter, stack, and heap.
    
- **Isolation & Protection**  
    Each process runs in its own **virtual address space**, preventing it from directly accessing memory or resources of other processes.
    
- **Lifecycle**  
    Processes typically move through states such as _created_, _ready_, _running_, _waiting_, and _terminated_.
    
- **Resource Ownership**  
    A process owns resources like memory regions, file descriptors, handles, and security credentials.
    
- **Scheduling Unit**  
    The OS scheduler selects which process (or its threads) gets CPU time.
    
- **Parent–Child Relationships**  
    Processes are often created by other processes, forming hierarchies used for control and cleanup.
    
- **User Space vs Kernel Space**  
    Most process execution occurs in user space, with controlled transitions into kernel space via system calls.
    
- **Threads vs Processes**  
    A process may contain one or more threads, which share the same address space but execute independently.

---
### `Connected Notes`

- [[Kernel Responsibilities]]
- [[Operating System (OS)]]