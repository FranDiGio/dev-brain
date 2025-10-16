
## `Definition`

**Service-Oriented Architecture (SOA)** is a software design style where applications are built as a collection of **interoperable services** that communicate over a network. Each service performs a specific business function and exposes it through standardized interfaces — typically using protocols like **SOAP** or **XML-RPC**.

---
## `Key Ideas`

- **Service abstraction** → Each service encapsulates a business capability and hides its internal logic from consumers.
    
- **Loose coupling** → Services interact through well-defined contracts, reducing dependency between systems.
    
- **Enterprise integration** → Originally aimed at connecting large, heterogeneous systems (databases, legacy apps, ERPs) within organizations.
    
- **Standardized communication** → Uses formal protocols and message formats (e.g., SOAP, WSDL) to ensure interoperability across platforms.
    
- **Reusability and governance** → Promotes reusing shared services across multiple applications, often managed through a central service registry.
    
- **Predecessor to microservices** → Laid the groundwork for distributed architectures but with heavier tooling and less flexibility.


---
## `Use Cases`

- **Enterprise applications** needing integration between diverse systems (e.g., CRM, ERP, billing).
    
- **Legacy modernization** projects where older systems are exposed as services.
    
- **Organizations requiring strict governance and version control** over shared business functions.


---
## `Connected Notes`

- [[Software Architecture]]
- [[Application Evolution]]