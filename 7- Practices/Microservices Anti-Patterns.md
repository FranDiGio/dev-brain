
Microservices anti-patterns are **development and architectural practices that undermine the benefits of microservices**, typically leading to higher operational complexity, tighter coupling, and reduced system reliability.

They often emerge when microservices are adopted without sufficient need, discipline, or supporting infrastructure.

---
### `Key Ideas`

- **Microservices should not be the starting point**  
    Systems should begin as monoliths and only be decomposed when complexity, scale, or team structure justifies it.
- **Automation is non-negotiable**  
    Microservices require strong CI/CD, monitoring, and deployment automation due to the increased number of independently evolving services.
- **Service granularity must be balanced**  
    Over-fragmentation leads to nanoservices, increasing communication overhead and operational burden.
- **Clear service boundaries are essential**  
    Weak boundaries or shared data models can cause microservices to regress into tightly coupled architectures resembling SOA.
- **Cross-cutting concerns should be centralized**  
    Concerns like authentication, routing, and rate limiting should be handled via infrastructure (e.g. API gateways), not duplicated per service.

---
### `Challenges`

- Starting microservices before a real monolith scaling problem exists
- Lack of CI/CD pipelines, monitoring, or deployment automation
- Over-splitting services into nanoservices with excessive communication overhead
- Poorly defined service boundaries leading to hidden coupling
- Shared databases across services breaking independence
- Rebuilding infrastructure concerns (auth, routing, analytics) inside every service
- Drift toward SOA-style tight coupling instead of independent services

---
### `Connected Notes`

- [[Microservices Architecture]]