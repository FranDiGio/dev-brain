
### `Definition`

A set of correctness properties that define the guarantees a database system should provide when executing transactions.

---
### `Key Ideas`

- **Atomicity**: A transaction’s operations either all succeed or all fail as a single unit
    
- **Consistency**: A transaction moves the database from one valid state to another according to defined rules
    
- **Isolation**: Concurrent transactions do not interfere in a way that violates correctness
    
- **Durability**: Once a transaction is committed, its effects survive crashes and restarts
    
- ACID describes **what must be guaranteed**, not how those guarantees are implemented
    
- Different databases may satisfy ACID properties using **different internal mechanisms**

---
### `Connected Notes`

- [[Database Transactions]]