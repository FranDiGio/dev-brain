
## `Definition`

**Site Reliability Engineering (SRE)** is an **operations-focused engineering discipline** that applies software engineering principles to system administration and reliability tasks.  

Created at Google, it extends DevOps principles by emphasizing **automation, reliability metrics, and accountability** through measurable service-level targets.

---
## `Key Ideas`

- **Shared goals with DevOps** → Both promote collaboration and blameless culture between Development and Operations.
    
- **Engineering approach to Ops** → SREs are software engineers who automate operational processes like deployments, monitoring, and scaling.
	
- SRE often coexists with DevOps culture → SRE enforces reliability constraints while DevOps drives fast delivery.
    
- **Error budgets** → Reliability targets are defined by _Service Level Objectives (SLOs)_ and _error budgets_.
    
    - If the number of incidents exceeds the budget, no new features are deployed until stability is restored.
    
- **Automation over toil** → Any repetitive manual work should be automated to improve efficiency and consistency.
    
- **Visibility and collaboration** → Makes Dev and Ops work transparent, breaking silos through shared metrics and ownership.
    
- **Focus on reliability as a feature** → Availability, latency, and performance are treated as key product outcomes, not afterthoughts.


---
## `Challenges`

- **Balancing innovation vs. reliability** → Too strict error budgets can slow feature delivery; too lenient ones risk instability.
    
- **Cultural friction** → Shifting from firefighting to proactive reliability engineering requires organizational maturity.
    
- **Measuring the right things** → Poorly defined SLOs or irrelevant metrics can lead to wasted effort or misplaced focus.
    
- **Skill gap** → True SREs need both ops experience and strong software engineering backgrounds, which are rare to find.


---
## `Connected Notes`

[[DevOps Culture]]