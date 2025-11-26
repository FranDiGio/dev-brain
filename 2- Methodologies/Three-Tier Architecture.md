
### `Definition`

**Three-Tier Architecture** is an architectural pattern that divides an application into **three logical and physical tiers**. Each tier runs independently and communicates only with adjacent tiers, creating clear separation of responsibilities.

---
### `Key Ideas`

- **Three Independent Layers:**
    
    - **Presentation Tier:** Handles UI, client interactions, requests.
        
    - **Application Tier:** Processes business rules, workflows, and decisions.
        
    - **Data Tier:** Manages databases, storage, and data access logic.  
        _This separation increases clarity and simplifies team ownership._
    
- **Better Maintainability:**  
    Changes to UI, business rules, or databases can happen within their tier without affecting others.  
    _Often used in enterprise systems to manage complexity._
    
- **Scalable and Modular:**  
    You can scale tiers independently — for example, deploy more application servers under high load.  
    _Common for large applications needing predictable scaling._
    
- **Supports Distributed Deployment:**  
    Tiers can live on separate machines, networks, or cloud services.  
    _Useful for security and redundancy._
    
- **Common Structure For Web Applications:**  
    The pattern maps naturally to modern app setups:  
    Web client → Backend API → Database.

---
### `Challenges`

- Increased operational complexity when tiers run on separate machines.
    
- Higher latency between layers due to more network hops.
    
- If layering is too strict, simple flows become overly complicated.
    
- Risk of “bloated middle tier” when business logic grows too large.
    
- Requires careful API boundary design to avoid leakage between layers.

---
### `Connected Notes`

- [[Layered Architecture]]