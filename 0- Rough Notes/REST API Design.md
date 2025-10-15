
## `Summary`

For **REST APIs**, routes are named around **resources, not actions**. REST routes describe resources, while HTTP methods describe actions.

---
## `Explanation`

Endpoints should use **nouns in plural form** (like `/users`, `/posts`) to represent collections, with individual items accessed through identifiers (e.g., `/users/{id}`). 

The **HTTP method** itself expresses the action: `GET` to read, `POST` to create, `PUT/PATCH` to update, and `DELETE` to remove—so verbs in the URL aren’t needed.

Relationships are expressed with **nested paths** when a resource belongs to another, such as `/posts/{postId}/comments`. Routes should be **lowercase, consistent, and hyphenated** rather than camelCase or snake_case. Special cases like the authenticated user often use `/me` (e.g., `/users/me` or `/sessions/me`). Filtering or pagination is handled with **query parameters**, not custom verbs in the path. This keeps APIs intuitive, predictable, and aligned with industry conventions.

`/me` is a **convention for "the currently authenticated user"** (based on their session or token), so the client doesn’t need to know or pass their own user ID explicitly.


---
## `Code Example`

```

✅ Good (RESTful)

POST   /users            # Sign up
POST   /sessions         # Log in
DELETE /sessions/me      # Log out

GET    /posts            # List posts
POST   /posts            # Create post
DELETE /posts/42         # Delete post 42

POST   /posts/42/comments      # Add comment
DELETE /posts/42/comments/9    # Delete comment 9

❌ Bad (non-RESTful)

POST   /createUser
POST   /loginUser
POST   /logoutUser

GET    /fetchPosts
POST   /submitPost
DELETE /deletePostById?id=42

POST   /addCommentToPost/42
DELETE /removeCommentFromPost?post=42&comment=9

```


---
## `Connected Notes`

