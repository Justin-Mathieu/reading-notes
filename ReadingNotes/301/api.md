# APIs

## API Best Design Practices

1. What does REST stand for?

- Representational State Transfer.

2. REST APIs are designed around a ____.

-Resources

3. What is an identifier of a resource? Give an example.

- The thing the you get back form an api
 call, an object or data that can be used by the client.

4. What are the most common HTTP verbs?

-GET,POST, PATCH, PUT AND DELETE.

5. What should the URIs be based on?

- The identifier or the resource.

6. Give an example of a good URI.

-<https://adventure-works.com/orders>
(Taken from <https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design#what-is-rest>)

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

- Lots of api calls, apis calls should be kept to a minimum to save on resources.

8. What status code does a successful GET request return?

- Status 200(OK).

9. What status code does an unsuccessful GET request return?

- Status 404(Not Found).

10. What status code does a successful POST request return?

- Status 201(Created).

11. What status code does a successful DELETE request return?

- Status 204(No Content).
