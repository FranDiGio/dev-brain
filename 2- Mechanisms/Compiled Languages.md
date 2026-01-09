
### `Definition`

A **compiled language** is one where the source code is **translated into machine code** by a **compiler** before execution. The resulting binary can run directly on the target hardware without further translation.

---
### `Key Ideas`

- **Execution Model:**  
    Compilation occurs ahead of time, producing an executable file optimized for the system architecture.
    
- **Performance Advantages:**
    
    - Fast execution and lower runtime overhead
    - Opportunities for deep optimization during compile time
    
- **Technical Characteristics:**
    
    - Platform-specific binaries (unless cross-compiled)
    - Requires recompilation after code changes
    
- **Common Compilers:**  
    GCC (C/C++), Rustc (Rust), Go Compiler, Swift Compiler (LLVM-based).

---
### `Use Cases`

- **Systems Programming:** OS kernels, embedded systems, and device drivers.
- **High-Performance Applications:** Games, finance, scientific simulations.
- **Static Environments:** Where predictable runtime performance is essential.

---
### `Connected Notes`

- [[High-level Languages]]
- [[Compiler]]
- [[Build Tools]]