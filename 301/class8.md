# Class 8 Notes - APIs

## Summary of Topics

### API Design Best Practices

1. What does REST stand for?

- representational state transfer
- architectural approach to designing web services 

2. REST APIs are designed around a ____.

- resources

3. What is an identifier of a resource? Give an example.

- every resource has one, its a URI that uniquely identifies that resource

4. What are the most common HTTP verbs?

- post - create new
- get - retreive all
- put - update
- patch - partial update
- delete - remove

5. What should the URIs be based on?

- URIs should be based on nouns (the source), and not verbs (the operations)

6. Give an example of a good URI.

- one that represents an object uniquely and permanently

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

- a web server that has many requests causing a bigger load for the server.  its a bad thing bc it could require a client application to send multiple requests to find all of the data that it requires

8. What status code does a successful GET request return?

- 200

9. What status code does an unsuccessful GET request return?

- 404

10. What status code does a successful POST request return?

- 201

11. What status code does a successful DELETE request return?

- 204
