
### `Definition`

**NoSQL (Not Only SQL)** refers to a family of **non-relational database systems** designed to handle **unstructured, semi-structured, or rapidly changing data** at scale. They provide flexible data models and high performance for distributed, modern applications.

---
### `Key Ideas`

- **Non-Relational Model:**  
    Unlike SQL databases, NoSQL systems do **not rely on fixed table schemas** or relationships.  
    Data is stored in formats suited to specific needs — such as documents, key-value pairs, columns, or graphs.
    
- **Main NoSQL Types:**
    
    - **Document Stores:** Store JSON-like documents (e.g., **MongoDB**, **CouchDB**).
        
    - **Key-Value Stores:** Store data as simple key-value pairs (e.g., **Redis**, **DynamoDB**).
        
    - **Column-Family Stores:** Organize data by columns instead of rows (e.g., **Cassandra**, **HBase**).
        
    - **Graph Databases:** Model relationships as edges between entities (e.g., **Neo4j**, **Amazon Neptune**).
    
- **Schema Flexibility:**  
    NoSQL databases allow **dynamic schemas**, meaning data structures can evolve over time without migrations.
    
- **Scalability:**  
    Built for **horizontal scaling** — data can be distributed across multiple servers or regions to handle high volumes and traffic.
    
- **Consistency Models:**  
    Typically trade strict ACID guarantees for **eventual consistency** (depending on system and use case).  
    Many NoSQL systems follow the **BASE** model: _Basically Available, Soft state, Eventually consistent._
    
- **Querying:**  
    Queries vary by database type — many use JSON-like query languages or APIs instead of SQL.

---
### `Use Cases`

- Real-time web and mobile applications.
- Big Data and analytics workloads.
- Content management systems and recommendation engines.
- IoT platforms and time-series data storage.
- Scenarios requiring high throughput and flexible data modeling.

---
### `Connected Notes`

- [[NoSQL Databases]]
- [[Key-Value Databases]]
- [[Document Databases]]
- [[CAP Theorem]]