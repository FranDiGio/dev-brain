
### `Definition`

**Assembly languages** are **low-level programming languages** that use symbolic instructions (mnemonics) to represent **machine code** operations.  
Each statement in assembly corresponds **one-to-one** with a CPU instruction.

---
### `Key Ideas`

- **Direct Hardware Control:**  
    Assembly interacts closely with the processor’s architecture, offering **fine-grained control** over memory, registers, and I/O operations.
    
- **Mnemonics and Operands:**
    
    - **Mnemonics:** Human-readable representations of machine operations (e.g., `MOV`, `ADD`, `JMP`).
        
    - **Operands:** Specify the data or memory location the instruction acts upon.
    
- **Translation via Assembler:**  
    Assembly code is converted into binary **machine code** using an **assembler**, not a compiler or interpreter.  
    This produces highly efficient executable programs.
    
- **Architecture Dependence:**  
    Each CPU type (e.g., x86, ARM, MIPS) has its own assembly syntax and instruction set — code is **not portable** between them.
    
- **Use Cases:**
    
    - Embedded systems and firmware
        
    - Performance-critical components (e.g., kernels, device drivers)
        
    - Reverse engineering and cybersecurity research

---
### `Connected Notes`

- [[Low-Level Languages]]