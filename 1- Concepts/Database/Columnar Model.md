
### `Definition`

The **Columnar Model** is a database model that organizes data by storing values column-by-column rather than row-by-row. It is optimized for reading and processing large volumes of data across specific attributes.

---
### `Key Ideas`

- **Column-Oriented Storage**  
    Data is grouped by columns, meaning all values of a single attribute are stored together.
    
- **Efficient Aggregation**  
    Queries that scan specific columns (e.g., analytics, sums, averages) can operate more efficiently.
    
- **Compression-Friendly Structure**  
    Storing similar data types together enables higher compression rates.
    
- **Analytical Focus**  
    Well-suited for workloads involving large-scale data analysis rather than frequent row-level updates.
    
- **Reduced I/O for Targeted Queries**  
    Only relevant columns need to be read during query execution.

---
### `Connected Notes`

- [[Database Models]]