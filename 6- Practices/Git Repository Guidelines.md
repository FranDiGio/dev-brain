## `Principle`

A **clean and modular Git workflow** ensures clarity, accountability, and maintainability in collaborative development. Each microservice or component should have its own repository, and branches should reflect focused, short-lived units of work.  

This practice promotes parallel development, reduces merge conflicts, and keeps the main branch stable for integration and delivery.

---
## `Applications`

- **One repo per service or component** → Keeps ownership clear and reduces dependency overhead; avoids large, complex monorepos.
    
- **Single main branch policy** → The `main` (or `master`) branch represents production-ready code.
    
- **Feature branching workflow** →
    
    1. **Clone** the repo locally.
        
    2. **Create** a new branch for each feature or fix.
        
    3. **Commit and push** the branch to the remote.
        
    4. **Open a Pull Request** for review and merge into `main`.
        
    5. **Delete the branch** after merging to keep history clean.
    
- **Pull requests (PRs)** → Encourage at least one reviewer for every PR (“two sets of eyes”), improving code quality and knowledge sharing.
    
- **Issue tracking** → Each branch or PR should correspond to a Git issue to link work with requirements or bug reports.


---
## `Challenges`

- **Monorepos vs. Polyrepos** → While monorepos simplify dependency management, they can slow builds and complicate ownership for large teams.
    
- **Branch sprawl** → Without cleanup discipline, feature branches can accumulate and confuse history.
    
- **Merge conflicts** → Poorly synchronized branches or long-lived features increase merge difficulty.
    
- **Cultural adoption** → Teams may resist strict review or branching conventions if not clearly justified by quality and maintainability goals.


---

## `Connected Notes`

- [[Git]]
- [[Branching Strategies]]
- [[DevOps Culture]]