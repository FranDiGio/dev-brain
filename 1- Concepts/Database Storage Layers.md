
### `Definition`

**Database storage layers** are the internal architectural components that determine **how a database physically stores, organizes, retrieves, and persists data**. They form a multi‑layered system that separates logical data structures from their physical representation, enabling performance, reliability, and durability at scale.

---
### `Key Ideas`

- **Layered Abstraction Between Logical and Physical Storage**  
    Users interact with logical structures (tables, documents, key–value pairs), while the storage layers translate these into **physical formats** optimized for I/O, durability, and access patterns.
    
- **Page-Based Storage Model**  
    Most databases organize on-disk and in-memory data into **pages/extents**, fixed-sized blocks that act as the atomic units of reading and writing. This improves predictability and reduces random disk access.
    
- **Data Files as Persistent Containers**  
    The database writes and organizes pages inside **data files** (or segments), which act as long-term durable storage for all logical objects and indexes.
    
- **Indexes Stored as Parallel Structures**  
    Indexes (B‑trees, LSM-trees, hash indexes, etc.) form separate storage layers designed specifically for **fast lookups, ordering, and selective access**, often with different write/compact strategies.
    
- **Write-Ahead Logging (WAL) for Durability**  
    Any modification to data is first written to a **sequential log** before being applied to pages, ensuring recoverability and preventing data loss on crashes.
    
- **In-Memory Buffering & Caching**  
    A buffer pool or cache layer keeps frequently accessed pages in memory, reducing disk I/O and enabling efficient reads, writes, and query execution.
    
- **Coordination Between Layers**  
    Storage layers interact through mechanisms like **checkpoints**, **dirty page flushing**, **index maintenance**, and **log replay**, ensuring that data remains consistent and durable across crashes and concurrency.

---
### `Connected Notes`

- [[Data Files]]
- [[WAL (Write-Ahead Logging)]]
- [[DB Buffering & Caching]]
- [[Database Transactions]]