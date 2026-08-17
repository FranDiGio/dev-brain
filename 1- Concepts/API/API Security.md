
# API Security

**API security** is the set of concepts and mechanisms used to protect APIs, their data, and their consumers from unauthorized access and misuse. It determines how clients prove their identity, what they are allowed to do, how credentials are handled, and how access between different systems and origins is controlled.

---
## Key Ideas

- **Authentication** verifies the identity of a user, application, or service attempting to access an API.
	
- **Authorization** determines what an authenticated identity is permitted to access or perform.
	
- **API Keys** are credentials used to identify or authenticate applications making API requests. They are simple to use but generally provide less flexible security than more complete authentication systems.
	
- **OAuth 2.0** is an authorization framework that allows applications to obtain limited access to resources on behalf of a user or another system without directly sharing the user's credentials.
	
- **JWT** is a compact token format commonly used to carry identity and authorization claims between systems. Tokens can be digitally signed so recipients can verify that their contents have not been modified.
	
- **CORS** is a browser security mechanism that controls whether a web application from one origin is allowed to access resources from another origin.
	
- **Authentication and authorization are separate concerns.** Knowing who a caller is does not automatically mean they should be allowed to perform every operation.
	
- API security should follow the **principle of least privilege**, granting consumers only the permissions they require.
	
- Sensitive credentials such as API keys and tokens should be treated as secrets and should not be exposed in client-side code, source control, logs, or other insecure locations.

---
## Connected Notes

- [[API]]
- [[API Authentication]]
- [[API Authorization]]
- [[API Keys]]
- [[JWT]]
- [[CORS]]