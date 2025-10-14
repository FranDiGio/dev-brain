
## `Summary`

 **Express** is a lightweight web framework for Node.js that simplifies building web servers and APIs.

---
## `Explanation`

At its core, Express handles **HTTP requests and responses**. Instead of writing raw Node.js server code, it provides an easier way to define **routes** (URLs) and attach **handlers** (functions) for different HTTP methods (`GET`, `POST`, `PUT`, `DELETE`).

It also supports **middleware**, which are functions that run in sequence on every request (for tasks like parsing JSON, handling sessions, or logging). This makes Express flexible for building everything from small apps to full REST APIs.

When you write things like `req.params`, `req.body`, `req.query`, or even `res.json()`, those aren’t built into raw Node.js — they’re **conveniences provided by Express (and its middleware)**. Express parses the incoming request and makes these objects available so you don’t have to manually handle raw HTTP streams.

In short: Express acts as the **bridge** between a client request and the server’s response, giving developers a clean, structured way to build web backends.


---
## `Code Example`

```js
import express from 'express';

const app = express();

// Middleware: parse JSON bodies
app.use(express.json());

// Route: GET /hello
app.get('/hello', (req, res) => {
  res.send('Hello World');
});

// Route: POST /users
app.post('/users', (req, res) => {
  const user = req.body;
  res.status(201).json({ message: 'User created', user });
});

app.listen(3000, () => console.log('Server running on port 3000'));

```


---
## `Links`

