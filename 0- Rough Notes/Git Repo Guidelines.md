
#### `What was explained`

- Create a repo per microservice or component, you don't wanna monorepos.
- Only one master branch and other branches are created per feature or fix (Issue) as necessary. Delete after all work is done and merged.

Git feature workflow:

GitHub Repo -> **clone** -> Local Repo -> **branch** -> Local Branch - > **push** -> Remote Branch -> **pull request** -> GitHub Repo

Note: - I've seen this approach at my current company.

---
#### `Why it matters`

- Monorepos only work for demos but not for production code as people may want to checkout just the code that they care about.
- If you make other people merge your Pull Requests, you to have 2 sets of eyes for all code that goes into the repo.


---
#### `What I’m confused about`

- What are git Issues?
- I'm sure I'm missing stuff (guidelines)


---
#### `Connections I noticed`

- Git
