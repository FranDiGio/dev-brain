
### `Definition`

Specialized data structures used by databases to organize and access data efficiently, allowing fast lookup, sorting, and range queries without scanning entire data files.

---
### `How It Works`

- Indexes store **references (pointers)** to data records rather than the data itself
    
- They are built on top of **pages**, following a structured layout (e.g. tree-based or hash-based)
    
- Queries use indexes to **narrow down the search space** before accessing data pages
    
- Index pages are read, cached, updated, and flushed using the same page and buffer mechanisms as data pages
    
- Index maintenance occurs on writes to keep indexes consistent with underlying data

---
### `Why It Exists`

- Full table scans do not scale for large datasets
    
- Indexes drastically reduce **read latency** for common access patterns
    
- They enable efficient **ordering, filtering, and range operations**
    
- They trade **additional storage and write overhead** for faster reads

---
### `Connected Notes`

- [[Pages & Extents]]