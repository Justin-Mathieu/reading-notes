# Authentication

## Securing Passwords

Explain to a non-technical friend how you would safely hash and store a password.

- Use salt to add a string of characters to the end of the user generated password, Then use bcrypot to hash the result and save the hashed password.

What is Bcrypt?

- Bcrypt is a password hashing function.

Why might you use something like Bcrypt?

- To secure sensetive data.

## Basic Auth

What is Basic Authentication?

- An HTTP method that allows safe transfer of passwords and user names.

What properties are necessary in the header of a Basic Auth request?

- tyhe Authorization header requries an encoded is and a password with a colon in between the two.

How are username:password in Basic Auth encoded?

- Base64 encoded id and password separated by a colon.

## OWASP Auth Cheatsheet

Define the authentication process to a non-technical recruiter.

- A request is sent to the server and the server verifys that the request is valid and that the credentials match the database.

How should your error messaging respond (both HTTP and HTML)? Why?

- Error messages should be generic in order to prevent exploitation.
