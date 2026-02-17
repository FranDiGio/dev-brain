
### `Definition`

A mechanism that manages how database pages are loaded into memory, reused, modified, and eventually written back to disk to reduce disk I/O and improve performance.

---
### `How It Works`

- Data is read from disk **page-by-page** into an in-memory buffer cache
    
- Pages in memory can be **clean** (same as disk) or **dirty** (modified)
    
- Repeated accesses hit memory instead of disk, avoiding expensive I/O
    
- Dirty pages are flushed back to disk asynchronously, often coordinated with checkpoints
    
- Eviction policies decide which pages to keep or remove when memory is full

---
### `Why It Exists`

- Disk access is orders of magnitude slower than memory access
    
- Databases must balance **performance** with **durability**
    
- Buffering allows write operations to be batched and reordered efficiently
    
- Caching enables predictable performance under repeated or concurrent access

---
### `Connected Notes`

- [[Database Storage Layers]]
- [[Pages & Extents]]