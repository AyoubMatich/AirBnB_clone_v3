# AirBnB_clone_v3
AirBnB clone - RESTful API

### What REST Means
**REST** stands for **Representational State Transfer**. It is an architectural style for designing networked applications. REST uses a stateless, client-server, cacheable communications protocol -- the HTTP protocol. RESTful applications use HTTP requests to perform CRUD (Create, Read, Update, Delete) operations.

### What API Means
**API** stands for **Application Programming Interface**. An API is a set of rules and definitions that allows software programs to communicate with each other. It defines the methods and data structures that developers can use to interact with a service, software library, or other applications.

### What CORS Means
**CORS** stands for **Cross-Origin Resource Sharing**. It is a security feature implemented by web browsers that allows or restricts web pages from making requests to a domain different from the one that served the web page. CORS allows servers to specify who can access their resources and how.

### What is an API
An **API** (Application Programming Interface) is a set of protocols and tools for building software applications. It specifies how software components should interact and allows different software systems to communicate with each other.

### What is a REST API
A **REST API** (Representational State Transfer API) is an API that conforms to the principles of REST. It provides a way for different systems to communicate over the internet using standard HTTP methods like GET, POST, PUT, DELETE. REST APIs are stateless and can be used to access and manipulate resources represented as URIs (Uniform Resource Identifiers).

### What are Other Types of APIs
1. **SOAP APIs**: Simple Object Access Protocol, a protocol for exchanging structured information in the implementation of web services.
2. **GraphQL APIs**: A query language for your API that provides a more efficient, powerful, and flexible alternative to REST.
3. **gRPC APIs**: A high-performance, open-source universal RPC framework that can run in any environment.
4. **WebSocket APIs**: Provides full-duplex communication channels over a single TCP connection, suitable for real-time applications.

### HTTP Methods to Retrieve Resources
**GET**: The HTTP method used to retrieve resources. It requests data from a specified resource.

### HTTP Method to Create a Resource
**POST**: The HTTP method used to create a new resource on the server.

### HTTP Method to Update a Resource
**PUT**: The HTTP method used to update an existing resource completely.
**PATCH**: The HTTP method used to apply partial modifications to a resource.

### HTTP Method to Delete a Resource
**DELETE**: The HTTP method used to delete a resource from the server.

### How to Request REST API
To request a REST API, you typically follow these steps:
1. **Choose the HTTP method**: Based on what you want to do (GET, POST, PUT, PATCH, DELETE).
2. **Specify the endpoint URL**: This is the address of the resource you want to interact with.
3. **Set headers**: This can include authentication tokens, content types, etc.
4. **Provide parameters**: This can be query parameters for GET requests or body parameters for POST/PUT requests.
5. **Send the request**: Using an HTTP client like `curl`, Postman, or programming libraries like `axios` (JavaScript), `requests` (Python).

Example of a GET request using `curl`:
```sh
curl -X GET "https://api.example.com/resource" -H "Authorization: Bearer YOUR_TOKEN"
```

Example of a POST request using `curl`:
```sh
curl -X POST "https://api.example.com/resource" -H "Content-Type: application/json" -d '{"key1":"value1","key2":"value2"}'
```