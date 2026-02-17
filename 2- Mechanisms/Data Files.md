
### `Definition`

Persistent files on disk where a database stores the actual data and metadata needed to reconstruct tables, indexes, and internal structures.

---
### `How It Works`

- Database data is written to one or more files managed by the storage engine
    
- These files are typically organized into logical units (pages, extents, segments)
    
- Reads and writes are done in blocks, not row-by-row
    
- Data files persist state across restarts and crashes
    
- Changes are coordinated with logging mechanisms (e.g. WAL) to ensure correctness

---
### `Why It Exists`

- To provide **durable storage** independent of memory
    
- To allow databases to handle **large datasets** that exceed RAM
    
- To enable **recovery** after crashes or shutdowns
    
- To separate long-term persistence from in-memory optimization layers

---
### `Connected Notes`

- [[Database Storage Layers]]
- [[Pages & Extents]]