
### `Definition`

**Apache Phoenix SQL** is a SQL-based query language layer that enables relational-style querying over data stored in Apache HBase.

It translates SQL queries into native HBase operations while preserving the wide-column storage model underneath.

---
### `Key Ideas`

- **SQL Layer Over Wide-Column Storage**  
    Provides relational-style syntax on top of the Wide-Column Model implemented by HBase.
    
- **Query Translation Engine**  
    Converts SQL statements into HBase scans, reads, and writes.
    
- **Schema Mapping**  
    Maps SQL tables and columns to HBase column families and row keys.
    
- **Performance-Oriented Design**  
    Leverages HBase indexing and region distribution for scalable execution.
    
- **Relational Interface, Non-Relational Core**  
    Offers SQL semantics while the underlying system remains wide-column and distributed.

---
### `Use Cases`

- Running SQL queries on large-scale HBase datasets
    
- Integrating HBase into SQL-based analytics workflows
    
- Enabling relational-style querying in distributed storage environments
    
- Simplifying HBase access for developers familiar with SQL

---
### `Connected Notes`

- [[Wide-Column Model]]