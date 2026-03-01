
### `Definition`

**Cassandra Query Language (CQL)** is a declarative query language used to define and manipulate data stored under the wide-column model in Apache Cassandra. It provides a SQL-like syntax tailored for distributed, partition-based data systems.

---
### `Key Ideas`

- **SQL-Inspired Syntax**  
    CQL resembles SQL in structure, making it familiar to users of relational databases.
    
- **Partition-Oriented Queries**  
    Queries are designed around partition keys and clustering columns, reflecting Cassandra’s distributed architecture.
    
- **Denormalized Data Design**  
    Data modeling prioritizes query patterns over relational normalization.
    
- **No Traditional Joins**  
    CQL does not support relational joins; relationships are typically handled through data duplication.
    
- **Model-Specific Semantics**  
    Designed specifically for the Wide-Column Model, not for relational or graph systems.

---
### `Use Cases`

- High-throughput distributed systems
    
- Time-series and event data
    
- Large-scale, horizontally partitioned datasets
    
- Architectures prioritizing availability and scalability

---
### `Connected Notes`

- [[Wide-Column Model]]