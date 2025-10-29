
### `Definition`

**Microservices** are an architectural style where an application is built as a collection of **small, independent services**, each focused on a single business capability.  

These services communicate with each other through lightweight APIs (often REST or messaging), allowing teams to develop, deploy, and scale them independently.

---
### `Key Ideas`

- **Independence:** Each service is developed, deployed, and maintained separately — enabling faster iteration and flexibility.
    
- **Loose coupling:** Services interact via well-defined interfaces, minimizing interdependencies and reducing the risk of system-wide failure.
    
- **Business alignment:** Each service represents a distinct business function (e.g., payments, inventory, user management).
    
- **Technology freedom:** Teams can choose different languages, frameworks, or databases for each service if needed.
    
- **Scalability and resilience:** Services can scale individually and continue functioning even if others fail.
    
- **Operational complexity:** While flexible, microservices require orchestration, monitoring, and automation (often through containers and DevOps practices).

---
### `Use Cases`

- **Evolving from monoliths:** Ideal for organizations that outgrow monolithic architectures and need agility in deploying or scaling features.
    
- **Large-scale systems:** Common in systems with diverse modules managed by different teams (e.g., e-commerce, banking, logistics).
    
- **Continuous delivery:** Enables rapid, independent releases through CI/CD pipelines.
    
- **Cloud-native applications:** Pairs naturally with containers, Kubernetes, and other cloud technologies for dynamic scaling and resilience.

---
### `Connected Notes`

- [[Cloud-Native Apps]]
- [[System Architecture]]