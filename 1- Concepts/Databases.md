
### `Definition`

A **database** is a structured system for **storing, organizing, retrieving, and managing data**. It provides a logical model for representing information and the mechanisms to access it efficiently, consistently, and reliably, independent of specific implementations like MySQL, PostgreSQL, or MongoDB.

---
### `Key Ideas`

- **Data as a structured model**  
    Databases impose a **schema or organizational model** (relational tables, documents, key‑value pairs, graphs, etc.) that describes how information is represented and how relationships are expressed.
    
- **Separation of storage vs. access logic**  
    Databases abstract away physical storage details (files, memory layout) and provide **logical operations** to query or mutate data.
    
- **Access via a query or command interface**  
    Databases expose a formal way to request data — SQL for relational systems, query languages or APIs for non‑relational systems — ensuring predictable interaction.
    
- **Consistency and correctness guarantees**  
    Most databases enforce some level of consistency (from strict ACID to eventual consistency) to ensure data remains **reliable** under concurrent access and failures.
    
- **Indexes and efficient retrieval**  
    Databases optimize data access using **indexes**, execution plans, caching, and query optimization strategies to retrieve data efficiently at scale.
    
- **Concurrency and transactions**  
    Databases manage multiple clients through locking, MVCC, or other concurrency models, ensuring **safe multi-user access** and transactional integrity.
    
- **Durability and persistence**  
    Data is stored in a way that ensures it **survives crashes, restarts, and hardware failures**, typically through write‑ahead logs, snapshots, or replication.

---
### `Connected Notes`

- [[Database Storage Layers]]
- [[Database Engine]]
- [[Database Management Systems (DBMS)]]
- [[Database Clients & Tools]]