
### `Definition`

A durability mechanism that records changes to a database in an append-only log before those changes are applied to data pages on disk.

---
### `How It Works`

- Before a transaction is committed, its changes are **written to the log**
    
- Log records are appended sequentially, making writes fast and reliable
    
- Data pages in memory may be updated later, independently of the log write
    
- On crash or restart, the database **replays the log** to restore a consistent state
    
- The log serves as the authoritative source for recovery until data pages are safely persisted

---
### `Why It Exists`

- Disk writes to data files are slow and unpredictable
    
- Sequential log writes are faster and safer than random page writes
    
- WAL ensures **durability** even if the system crashes before pages are flushed
    
- It decouples **correctness** from **when data pages reach disk**

---
### `Connected Notes`

- [[Database Storage Layers]]
- [[Checkpointing]]