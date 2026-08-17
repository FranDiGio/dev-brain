
An **API style** defines the architectural conventions used to structure how an API exposes functionality and how consumers interact with it. Different API styles make different trade-offs around communication patterns, data representation, performance, flexibility, contracts, and client-server coupling.

---
## Key Ideas

- **REST** models an API around resources and commonly uses standard HTTP semantics such as URLs, methods, headers, and status codes.
	
- **GraphQL** allows clients to describe the exact data they need through queries against a defined schema.
	
- **gRPC** models communication as remote procedure calls between strongly defined services, typically using Protocol Buffers and efficient binary serialization.
	
- **SOAP** defines a highly structured messaging protocol based on XML and formal service contracts, commonly used in enterprise integrations.
	
- **WebSocket APIs** maintain a persistent connection between client and server, allowing both sides to send messages independently and enabling real-time bidirectional communication.
	
- Each style optimizes for different requirements. REST prioritizes simplicity and broad web compatibility, GraphQL prioritizes flexible data retrieval, gRPC prioritizes efficient service-to-service communication, SOAP prioritizes strict contracts and interoperability, and WebSockets prioritize continuous real-time communication.
	
- API styles are not mutually exclusive at a system level. A system may expose different APIs using different styles depending on the needs of its consumers and internal services.

---
## Connected Notes

- [[API]]
- [[REST API]]
- [[GraphQL]]
- [[gRPC]]
- [[SOAP]]
- [[WebSocket API]]