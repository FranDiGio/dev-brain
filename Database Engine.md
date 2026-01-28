
### `Definition`

A **database engine** is the **core software component** responsible for **storing, retrieving, updating, and managing data** inside a database system. It executes queries, manages memory and storage, maintains indexes, enforces transactions, and coordinates all low-level operations that make a database function.

It is the **execution and storage core** of a DBMS — distinct from tools, clients, or administrative layers.

---
### `Key Ideas`

- **Execution of Queries and Commands**  
    The engine parses, optimizes, and executes queries using its internal components (parser, planner, optimizer, executor), transforming logical requests into physical operations on data.
    
- **Transaction and Concurrency Control**  
    The engine ensures correctness during concurrent access using mechanisms like locks, latches, MVCC, or optimistic concurrency, enforcing isolation and atomicity.
    
- **Storage and Retrieval Mechanisms**  
    It manages how data is physically stored and accessed through storage layers — pages, data files, indexes, logs, caching, and checkpointing.
    
- **Index and Data Structure Management**  
    The engine creates, maintains, and updates index structures (B‑trees, hash tables, LSM-trees, etc.) that speed up lookups and enforce ordering or uniqueness.
    
- **Durability and Crash Recovery**  
    Through write-ahead logging, snapshots, and recovery algorithms, the engine ensures data remains consistent after failures or restarts.
    
- **Query Optimization Pipeline**  
    The engine transforms a high-level query into an efficient plan using cost models, statistics, rewrite rules, and heuristics, choosing the best way to access and join data.
    
- **Modular Independence From Tools/Clients**  
    The database engine runs inside the DBMS but remains distinct from external tools (SSMS, psql, DataGrip) or platform layers. Engines are the **core computational subsystem**.

---
### `Connected Notes`

- [[SQL Server Database Engine]]
- [[PostgreSQL Engine]]
- [[MySQL Engine]]
- [[SQLite Engine]]
- [[Oracle Engine]]
- [[MariaDB Engine]]
- [[Amazon Aurora Engine]]