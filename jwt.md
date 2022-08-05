# Bearer Authorization

## Intro to JWT  

What is a JSON Web Token (JWT)?

- A way of transfering information in a JSON object that is signed by using a secret.  

When should we use JSON Web Tokens?

- For authorizing access to routes or exchanging information.  

Claims are expected in which structural component of a JWT?

- Claims are the statements and informatin they are stored in the paylod.  

## Are JWTs secure  

If I get a JWT and I can decode the payload, how can we call that secure?

- The secret adds further protection by being a key that both parties know. 

If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

- The secret  

Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.


- The combination of the secret on the JWT side and the encryption of the https make the transfer secure the JWt can be read but not changed duer to the secret.  


## JWTs Explained  

Why use JWT?

- JWTS are compact and Fast making them eaily used in the a url or header.

JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

- JWTs are self contained in the way that the token itself holds the information about the user this makes the token efficient for databases and authorization.  

What are the three components (the structure) of a JWT signature?

- The Structure of A JWT is: (base 64 encoded header).(base 64 encoded payload).(secret)
