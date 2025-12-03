
### `Definition`

A **load balancer** is a system component that distributes incoming network traffic across multiple servers to ensure no single server becomes overloaded. It improves performance, availability, and reliability of applications in production.

---
### `Key Ideas`

- **Traffic Distribution:**  
    Routes client requests across multiple backend servers (server farm).
    
- **High Availability:**  
    If one server fails, traffic is redirected to healthy servers.
    
- **Scalability:**  
    Enables horizontal scaling by adding or removing backend servers.
    
- **Request Routing Logic:**  
    Uses algorithms like round-robin, least connections, or health-based routing.
    
- **Placement in Architecture:**  
    Typically sits between clients and web or application servers.
    
- **Common in Production:**  
    Essential for handling concurrent users and peak traffic reliably.

---
### `Connected Notes`

- [[Production Deployment Components]]