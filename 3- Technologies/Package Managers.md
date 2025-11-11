
### `Definition`

A **package manager** is a **tool that automates installing, upgrading, configuring, and removing software packages**. It ensures that all project dependencies are correctly versioned and compatible.

---
### `Key Ideas`

- **Dependency Management:**  
    Automatically downloads and resolves dependencies (and their sub-dependencies).
    
- **Registry Integration:**  
    Connects to centralized repositories (e.g., npm, PyPI, Maven Central) or private registries.
    
- **Version Locking:**  
    Uses lock files (e.g., `package-lock.json`, `Pipfile.lock`) to ensure consistent environments.
    
- **Global vs Local:**
    
    - **Global installs:** Available system-wide.
        
    - **Local installs:** Scoped to a project.
    
- **Popular Tools:**
    
    - **JavaScript:** npm, Yarn, pnpm
        
    - **Python:** pip, Poetry
        
    - **Java:** Maven, Gradle
        
    - **Linux systems:** apt, yum, pacman

---
### `Use Cases`

- Setting up development environments quickly
- Installing libraries and frameworks automatically
- Managing project dependencies and avoiding version conflicts
- Keeping software up to date with minimal manual effort

---
### `Connected Notes`

- [[Build Tools]]
- [[Packages]]