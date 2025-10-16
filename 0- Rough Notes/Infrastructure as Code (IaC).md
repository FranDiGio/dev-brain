
#### `What was explained`

- Is the idea of storing infrastructure as a text-based executable format. i.e. code.
- This is where containers come into play, these are executable infrastructure where all the configuration is already pre-applied to run your application.
- These containers are ephemeral, you use them as you need them and shut them down when they start misbehaving or don't need them anymore.
- When patching a container, you don't patch the running ones, you patch the image (or blueprint) from which these running containers where created from.
- Infrastructure as cattle, not pets. You shouldn't attach yourself to these servers, you should use them and scrap them as per your needs.


---
#### `Why it matters`

- This allows automated infrastructure and speeds up setting up for development, testing, or even changing the production environment.



---
#### `What I’m confused about`

Is it really that easy? 
What are the downsides of containers? Any competitors?



---
#### `Connections I noticed`

- Containers