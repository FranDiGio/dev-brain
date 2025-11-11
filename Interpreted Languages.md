
### `Definition`

An **interpreted language** is executed **line-by-line at runtime** by an **interpreter**, rather than being compiled into machine code ahead of time. The interpreter translates source code into machine instructions dynamically as the program runs.

---
### `Key Ideas`

- **Execution Model:**  
    The interpreter reads, parses, and executes code directly — each statement is translated on demand.
    
- **Development Benefits:**
    
    - Rapid iteration (no build step)
    - Easier debugging and testing
    - Platform independence (runs anywhere the interpreter exists)
    
- **Technical Drawbacks:**
    
    - Slower execution speed due to runtime translation
    - Heavier memory use compared to compiled binaries
    
- **Common Interpreters:**  
    CPython (for Python), Node.js (for JavaScript), Ruby MRI (for Ruby).

---
### `Use Cases`

- **Scripting and Automation:** Ideal for quick scripts and task automation.
- **Web Development:** JavaScript engines power client-side interactivity.
- **Data Science:** Python’s interpreted nature allows dynamic experimentation.

---
### `Connected Notes`

- [[Programming Languages]]
- [[Runtime Environment]]
- [[Interpreter]]