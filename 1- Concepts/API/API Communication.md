
**API communication** describes the mechanisms and conventions used to exchange information between an API consumer and the system exposing the API.

It covers how requests and responses are structured, how data is represented, and how protocols such as HTTP communicate metadata, actions, and outcomes between systems.

---
## Key Ideas

- **Request / Response** is the most common API interaction model. A client sends a request containing an intended action or data requirement, and the server returns a response containing the result.
	
- **Serialization** converts application data into a transferable representation such as JSON, XML, or a binary format so it can be transmitted between systems and reconstructed by the receiver.
	
- **HTTP Methods** communicate the intended operation of an HTTP request. Common methods include `GET`, `POST`, `PUT`, `PATCH`, and `DELETE`.
	
- **Headers** carry metadata alongside a request or response, such as authentication credentials, accepted formats, caching information, and content details.
	
- **Status Codes** communicate the outcome of an HTTP request. They indicate whether an operation succeeded, failed because of a client issue, or failed because of a server issue.
	
- **Content Types** describe the format of the data being transmitted. For example, `application/json` indicates that the message body contains JSON data.
	
- These mechanisms form the communication layer used by many API styles, but their importance and exact usage vary depending on the protocol or style being used.

---
## Connected Notes

- [[API]]
- [[Request - Response]]
- [[Serialization]]
- [[HTTP Methods]]
- [[Headers]]
- [[Status Codes]]
- [[Content Types]]