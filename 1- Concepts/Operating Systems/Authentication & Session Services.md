
### `Definition`

**Authentication & Session Management** encompasses the mechanisms that verify user identity and maintain a user’s active state across system and application interactions.

---
### `Key Ideas`

- **Authentication**  
    Determines **who** a user is.  
    Common methods:
    
    - passwords
    - SSH keys
    - OAuth tokens
    - biometrics
    - OS accounts
    - federated login (SSO)
    
- **Authorization** _(often paired conceptually)_  
    Controls **what** a user can access after being authenticated.
    
- **Session Management**  
    Maintains a user’s authenticated state using:
    
    - session tokens
    - cookies
    - access/refresh tokens
    - OS login sessions
    - TTY/terminal sessions
    - desktop login sessions
    
- **Exists at multiple layers**:
    
    - **OS-level**: user login, permissions, shells, sudo
    - **Application-level**: web sessions, JWT, OAuth
    - **Network-level**: SSH, Kerberos
    
- Sessions require **state tracking** and **expiration policies** to prevent unauthorized reuse.
    
- Essential for **security**, **resource access**, and **multi-user environments**.

---
### `Connected Notes`

- [[User Space Components (OS)]]