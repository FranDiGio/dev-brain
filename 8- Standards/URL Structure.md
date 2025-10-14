
## `Summary`

A **URL (Uniform Resource Locator)** specifies the address of a resource on the web and defines how to access it using HTTP/HTTPS. It is made up of structured parts that together describe the location and optional instructions (parameters, fragments).

---
## `Explanation`

A URL has several components, each serving a specific role:

- **Scheme/Protocol** → Defines how to access the resource (`http`, `https`, `ftp`).
    
    - Example: `https://`

- **Host/Domain** → The server or domain name hosting the resource.
    
    - Example: `example.com`

- **Port (optional)** → The port used to connect to the server. Default is `80` for HTTP and `443` for HTTPS.
    
    - Example: `:8080`

- **Path** → The specific resource being requested on the server.
    
    - Example: `/users/profile`

- **Query String (optional)** → Starts with `?`, contains key-value pairs separated by `&`. Used to send extra parameters.
    
    - Example: `?sort=asc&limit=20`

- **Fragment (optional)** → Starts with `#`, points to a specific section inside the resource (client-side only, not sent to the server).
    
    - Example: `#section2`


---
## `Code Example`

```bash
https://example.com:443/users/profile?sort=asc&limit=20#details

- Scheme: `https`
    
- Host: `example.com`
    
- Port: `443`
    
- Path: `/users/profile`
    
- Query: `sort=asc&limit=20`
    
- Fragment: `details`
```

```python
# Basic GET request with query parameters
GET /search?q=python&limit=10 HTTP/1.1
Host: www.google.com

# Example URL in Python
import requests

url = "https://api.example.com/users"
params = {"sort": "desc", "limit": 5}

response = requests.get(url, params=params)
print(response.url)
# -> https://api.example.com/users?sort=desc&limit=5
```
---
## `Connected Notes`

