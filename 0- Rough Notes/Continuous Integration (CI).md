
#### `What was explained`

- CI is the process of building, testing, and integrating code in a consistent manner to the master branch after tests have passed.
- Its difference from CD is that CD is the process of deploying to production-like environments when is safe to do so.
- The traditional approach was to have different branches (Dev, Test, UAT, Staging), and commit all changes in them and eventually pass it to the next level, resulting in lots of merge conflicts and bulk patches to Production.
- You should assume code doesn't work if it hasn't been tested and the build hasn't been done.


---
#### `Why it matters`

- It allows you to develop faster thanks to automation of tests and reducing instances of merge conflicts as you're always delivering in small batches.
- You get faster feedback and are able to react fast to issues.



---
#### `What I’m confused about`

Isn't deploying to the master branch the same as deploying to PROD?



---
#### `Connections I noticed`

- DevOps
- CD