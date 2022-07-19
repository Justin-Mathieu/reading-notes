# Express REST API

## Es6 Classes

Classes are a template for creating ____.

- Objects.

Can a class declaration be hoisted?

- Classes can not be hoisted.  

How would you describe a constructor and contextual “this” to a non-technical friend?

- A function that Creates an object with a class. This refers to the instanciation of where it is called.

## Using Express Routing  

Within Express, what does routing refer to?

- Application endpoints.

What is the difference between a route path and a route method?

-Route Methods are the http methods that do something. Route paths are the end points and where those methods happen.

When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

- When there are multpile functions in the handler. When next is sent as a parameter you need to call it on the next object.

## Express Routing

What is an Express Router?

- An exress application that gives us only the nessecary peicesto create routes.

By what mean do we initialize express.Router() in an express server?

- Instanciate express.Router and then using in the routes.  

What do we use route middleware for?

- To do something before the request runs.
