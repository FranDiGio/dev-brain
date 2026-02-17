
### `Definition`

A logical unit of work that groups one or more database operations into a single all-or-nothing execution boundary within a database system.

---
### `Key Ideas`

- A database transaction represents **intent**, not implementation
    
- It defines **when database work starts and ends**, and when results become visible
    
- Transactions provide a mental model for **correctness under concurrency and failure**
    
- They are **atomic at the semantic level**, even though execution may be incremental
    
- Transactions bridge application logic and database guarantees

---
### `Connected Notes`

- [[ACID]]