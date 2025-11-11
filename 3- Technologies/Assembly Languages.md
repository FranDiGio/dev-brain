
### `Definition`

**Assembly languages** are **low-level programming languages** that use symbolic instructions (mnemonics) to represent **machine code** operations. Each statement in assembly corresponds **one-to-one** with a CPU instruction.

---
### `Key Ideas`

- **Direct Hardware Control:**  
    Offers precise access to CPU registers, memory addresses, and input/output operations — enabling **fine-grained performance tuning**.
    
- **Mnemonics and Operands:**
    
    - **Mnemonics** are human-readable representations of binary instructions (e.g., `MOV`, `ADD`, `JMP`).
        
    - **Operands** specify the data or memory location affected by the instruction.
    
- **Assembler Translation:**  
    Assembly code is converted into binary **machine code** using an **assembler** (not a compiler or interpreter).  
    This translation creates highly efficient executables.
    
- **Architecture Dependence:**  
    Each processor architecture (e.g., **x86**, **ARM**, **MIPS**) has its own instruction set and syntax — code written for one is **not portable** to another.
    
- **Human Role in Optimization:**  
    Programmers can directly manage instruction order, memory access, and registers to **optimize performance or reduce resource usage**.

---
### `Use Cases`

- Embedded systems and firmware development
- Writing or optimizing kernels and device drivers
- Reverse engineering and security research
- Low-level debugging or hardware interfacing

---
### `Connected Notes`

- [[Low-level Languages]]