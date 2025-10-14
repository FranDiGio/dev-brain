
## `Summary`

The `window` is the **global object** in the browser. It represents the **browser window/tab itself** and everything running inside it. It is **not part of core JS**. It’s part of the _browser environment_.

---
## `Explanation`

- Almost everything in the browser lives under `window`:
    
    - Built-ins: `window.alert()`, `window.setTimeout()`, `window.fetch()`, `window.localStorage`, etc.
        
    - Global variables you define (`let foo = 123;`) automatically become `window.foo` (in non-module scripts).
        
    - The `document` object itself is a property of `window` → `window.document`.

Think of it like the **big container** that holds the page, history, location, storage, and APIs.

- **JavaScript** = the language (doesn’t know `window` or `document` by itself).
- **Browser environment** = provides `window` as the global object.
- **DOM** = lives inside `window.document`, it’s how you manipulate HTML.


---
## `Code Example`

```

```


---
## `Connected Notes`
