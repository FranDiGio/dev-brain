### `Definition`

A **Database Engine** is a category of core database software responsible for executing queries, managing storage, enforcing transactions, and coordinating concurrency inside a database system.

It is the computational and storage subsystem that implements persistence, indexing, recovery, and query execution — independent from client tools or administrative interfaces.

---
### `Key Ideas`

- **Execution Core of a DBMS**  
    The engine parses, optimizes, and executes queries, translating logical requests into physical data operations.
    
- **Implements Core Database Mechanisms**  
    Uses mechanisms such as Write-Ahead Logging, MVCC, Locking, Buffer Management, and B-Tree Indexes.
    
- **Transaction Management**  
    Enforces atomicity, consistency, isolation, and durability (see ACID Properties).
    
- **Storage Coordination**  
    Manages files, pages, caching layers, checkpoints, and crash recovery.
    
- **Distinct From Tools**  
    Separate from clients like SSMS, psql, or DataGrip — those interact with the engine but are not the engine.

---
### `Use Cases`

- Storing structured or semi-structured application data
- Supporting transactional systems (banking, ERP, trading platforms)
- Powering analytics and reporting workloads
- Handling concurrent multi-user data access
- Ensuring durability and recoverability in production systems

---
### `Connected Notes`

- [[SQL Server Database Engine]]
- [[PostgreSQL Engine]]
- [[MySQL Engine]]
- [[SQLite Engine]]
- [[Oracle Engine]]
- [[MariaDB Engine]]
- [[Amazon Aurora Engine]]