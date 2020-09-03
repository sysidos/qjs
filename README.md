**Create simple application using golang and sqlite3**

**Modules:**
- Authendication
- Users
- Posts
- Comments


**Requirements:**

- User will able to register with firstname, lastname, email and password.
- Use able to login with email and password.
- User will able to reset their password.
- Use validation for strong password.
- Use JWT and Refresh Token Implementation for Auth and Security
- Encrypt password using Argon2 or Bcrypt

- In login and register responce send User details with JWT and Refresh token.

- Registered user can able to post consist of only title and body. (something like tweet on twitter but only text based)
- Posts will have comments in it.

- Please handle relation betwen Users, Posts and Comments.

- Set all API Prefix to `/api`

**Routes:**
```
POST. /auth/login
POST. /auth/register
POST. /auth/forgot-password
GET. /users/me
GET. /posts
GET. /posts/1
GET. /posts/1/comments
GET. /comments?postId=1
GET. /posts?userId=1
POST. /posts
PUT. /posts/1
PATCH. /posts/1
DELETE. /posts/1
```
