
### `Definition`

A Kubernetes Deployment is a resource that **manages the lifecycle, scaling, and updates of pods in a declarative way**. It defines the desired state of an application and ensures that the system continuously maintains that state over time.

---
### `How It Works`

- A deployment defines a **desired number of pod replicas**
- Uses a **pod template** to specify how pods should be created
- Kubernetes creates and manages **ReplicaSets** to maintain the desired number of pods
- The system continuously compares:
    - Desired state (defined in the deployment)
    - Actual state (running pods)
- If there is a mismatch, Kubernetes **reconciles the state** by:
    - Creating new pods
    - Removing excess pods
- Supports **rolling updates**:
    - Gradually replaces old pods with new ones
    - Maintains availability during updates
- Supports **rollbacks** to previous versions if needed
- Works with the scheduler to **place pods on appropriate nodes**

---
### `Why It Exists`

Deployments provide a **reliable and automated way to manage application state over time**.

They enable:

- Maintaining a consistent number of running instances
- Updating applications without downtime
- Automatic recovery from failures
- Declarative management of application lifecycle

By abstracting pod management, deployments allow developers to define **what the system should look like**, while Kubernetes handles how to achieve it.

---
### `Connected Notes`

- [[Kubernetes]]