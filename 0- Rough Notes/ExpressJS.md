
### `Definition`

**Express.js** is a minimalist web framework for **Node.js** that streamlines the creation of web servers and APIs.  
It provides a structured way to handle **HTTP requests and responses**, letting developers build full-featured backends without dealing with low-level networking code.

---
### `Key Capabilities`

- **Routing made simple** → Define URL endpoints (`GET`, `POST`, `PUT`, `DELETE`) and attach request handlers cleanly.
    
- **Middleware support** → Stack reusable functions that process requests in sequence (e.g., logging, authentication, parsing).
    
- **Convenient abstractions** → Access request data easily with helpers like `req.body`, `req.params`, and send responses with `res.json()`.
    
- **Extensible architecture** → Compatible with third-party middleware and libraries (e.g., CORS, Helmet, JWT).
    
- **Rapid prototyping** → Great for quickly building REST APIs and microservices.

---
### `Usage Basics`

```js
import express from 'express';

const app = express();

app.use(express.json()); // Parse JSON requests

app.get('/hello', (req, res) => res.send('Hello World'));

app.post('/users', (req, res) => {
  const user = req.body;
  res.status(201).json({ message: 'User created', user });
});

app.listen(3000, () => console.log('Server running on port 3000'));

```

---
### `Challenges`

- **Not opinionated** → Flexibility means developers must decide their own structure, which can lead to inconsistency.
    
- **Middleware complexity** → Too many middleware layers can reduce readability and debugging clarity.
    
- **Performance trade-offs** → Slightly slower than lower-level frameworks like Fastify or raw Node.js in high-scale systems.
    
- **Manual scaling** → Lacks built-in clustering, requiring external tools for load balancing or horizontal scaling.

---
### `Connected Notes`

- [[Node.js]]
- [[REST API Design]]
- [[Routing]]
- [[Middleware]]
- [[HTTP Protocol]]