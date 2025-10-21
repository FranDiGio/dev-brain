
### `Definition`

The **browser environment** is the runtime context in which JavaScript executes inside a web browser. It provides objects, APIs, and the global scope that make it possible for JavaScript to interact with the page, the user, and the network.

---
### `Explanation`

- **Global Object** → `window`
    - Holds all global variables, functions, and browser-specific APIs.

- **DOM (Document Object Model)** → `window.document`
    - A structured representation of the web page (HTML, elements, text, etc.).

- **BOM (Browser Object Model)** → APIs for the browser itself
    - e.g., `navigator`, `location`, `history`, `screen`.

- **Web APIs** → Additional features exposed by the browser
    - e.g., `fetch`, `WebSockets`, `localStorage`, `setTimeout`.

- **Event loop & timers** → Browser provides scheduling and asynchronous task handling.

---
### `Limitations`

- The **JavaScript language** itself doesn’t define `window`, `document`, `fetch`, etc.
- These exist because the **browser environment** supplies them. (Outside a browser, like in Node.js, you don’t have `window` or `document`.)

---
### `Connected Notes`


