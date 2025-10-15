
#### `What was explained`

- Retry pattern
	- You keep trying to send requests but taking longer between each try. Try-1s-Try-2s-Try-4s-Try-8s.
	- This gives time to the service/database to recover as it could just be a network congestion

- Circuit Breaker pattern
	 - Designed to avoid cascading failures.

- Bulkhead pattern
	 - Designed to isolate failing services.

- Chaos engineering - Monkey Testing
	 - You shut down and kill services randomly to check how your system handles failure and how other services are affected.


---
#### `Why it matters`

- Failure is a constant, is not matter of ***would*** but a matter of ***when*** will the system fail.
- Applications should be built around recovering gracefully, not avoiding failure.


---
#### `What I’m confused about`

- Retry pattern (is it that simple?)
- Circuit Breaker pattern
- Bulkhead pattern



---
#### `Connections I noticed`

