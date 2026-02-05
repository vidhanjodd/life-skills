# REST Architecture Overview

Representational State Transfer (REST) is an architectural style for networked applications, proposed by Roy Fielding in 2000. It focuses on a stateless client-server architecture where resources are addressed using URIs and manipulated using standard HTTP verbs such as GET, POST, PUT, and DELETE.

## Architectural Constraints

The main constraints are:

- **Statelessness**: Every request is self-contained, holding all the information needed.
- **Uniform Interface**: Uniform access to resources using standard methods.
- **Cacheability**: Responses can be cached for optimization purposes.
- **Layered System**: Scalability using layered components.
- **Code on Demand** (optional): Server can send code to clients for execution.
- **HATEOAS** (optional): Hypermedia as the engine of application state.

## Advantages and Applications

These constraints allow for scalable and maintainable web services that are used by most modern APIs. REST assumes that everything is a resource with a representation (usually JSON/XML), emphasizing simplicity and interoperability on the Web.

## References

- [REST - Wikipedia](https://en.wikipedia.org/wiki/REST) [web:3]
- [What is a REST API? (BrowserStack)](https://www.browserstack.com/guide/rest-api) [web:1]
- [REST API Tutorial (restfulapi.net)](https://restfulapi.net)