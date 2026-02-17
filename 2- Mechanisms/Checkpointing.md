
### `Definition`

A recovery mechanism that periodically synchronizes in-memory database changes with persistent storage, establishing a known consistent point from which recovery can start.

---
### `How It Works`

- The database selects a point in time to create a checkpoint
    
- Dirty pages in memory are flushed to disk up to that point
    
- The position of the write-ahead log corresponding to the checkpoint is recorded
    
- After a crash, recovery starts from the most recent checkpoint instead of replaying the entire log
    
- Checkpointing runs in the background to limit recovery time and log growth

---
### `Why It Exists`

- Replaying the entire write-ahead log on recovery is inefficient
    
- Checkpoints bound **crash recovery time**
    
- They prevent unbounded growth of log files
    
- They coordinate durability between in-memory state and persistent storage

---
### `Connected Notes`

- [[WAL (Write-Ahead Logging)]]