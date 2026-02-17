
### `Definition`

Logical units used by databases to organize, store, and move data on disk and in memory, forming the basic granularity for reads, writes, and caching.

---
### `How It Works`

- Data files are divided into **fixed-size pages** (e.g. 4KB, 8KB, 16KB)
    
- Pages store rows, index entries, or metadata
    
- Pages are grouped into **extents** (contiguous sets of pages)
    
- The database reads and writes data **page by page**, not record by record
    
- Pages are loaded into memory buffers, modified there, and later flushed back to disk
    
- Extents help manage space allocation and reduce fragmentation

---
### `Why It Exists`

- Disk and memory I/O works efficiently on **fixed-size blocks**
    
- Pages provide a consistent unit for caching, locking, and recovery
    
- Extents simplify space management and improve sequential I/O performance
    
- Together, they balance **performance, simplicity, and scalability**

---
### `Connected Notes`

- [[Data Files]]
- [[Index Structures]]