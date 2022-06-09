# CRUD

## Status Codes on REST Methods

In your own words, describe what each group of status code represents:

100’s = Informs the user that the header has been recieved and the body is being processed or can send an error before the body even starts.  
200’s = These are success codes they inform the user that the request has been valdated at the time it was send not necesarily processed.
300’s = Redirection code that request deos not exist at that location.
400’s = Client error invalid request.
500’s = Error on the server side.

What is a status code 202?

- Accepted the request was valid and should process.  

What is a status code 308?

- Permanent redirection informs user that the endpoint is not useable.  

What code would you use if an update didn’t return data to a client?

- 204 No Content.  

What code would you use if a resource used to exist but no longer does?

- 404 not found or possibly 300 redirect.

What is the ‘Forbidden’ status code?

- Not authorized to access the backend.

## Video  

Why do we need to pull our MongoDB database string out of our server and put it into our .env?

-

What is middleware?

-

What does app.use(express.json()) do?

-

What does the /:id mean in a route?

-

What is the difference between PUT and PATCH?

-

How do you make a default value in a schema?

-

What does a 500 error status code mean?

-

What is the difference between a status 200 and a status 201?

-
