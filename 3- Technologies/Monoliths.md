
### `Definition`

**Monolithic Architecture** is a **software design pattern** in which all components of an application — user interface, business logic, and data access — are **packaged and deployed as a single unified unit**.  

All functionality runs within a single codebase and process.

---
### `Key Ideas`

- **Single Deployment Unit:**  
    The entire system (frontend, backend, database access, etc.) is built, tested, and deployed together.
    
- **Tight Coupling:**  
    Modules depend heavily on one another, making changes in one part potentially impact others.
    
- **Shared Resources:**  
    Common memory space, shared database, and often synchronous communication between components.
    
- **Simpler Development & Testing (Initially):**  
    Straightforward for small teams and early-stage projects with limited complexity.
    
- **Challenges at Scale:**  
    As the codebase grows, deployments become slower, scaling is inefficient (entire app scales even if one part needs it), and tech stack upgrades are harder.
    
- **Maintenance Complexity:** Large, tightly coupled codebases become difficult to manage over time.
    
- **Technology Lock-In:** Difficult to adopt new frameworks or languages without rewriting major portions.

---
### `Use Cases`

- Startups or small projects needing **fast development and simple deployment**.
    
- Systems where **tight integration** between modules is beneficial (e.g., internal tools).
    
- **Legacy enterprise applications** that evolved before distributed architectures.

---
### `Connected Notes`

- [[System Architecture]]