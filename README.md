# Request Header Parser Microservice

This project is an API microservice that returns information about the client making an HTTP request. When making a GET request to the `/api/whoami` route, the API responds with a JSON object containing the client's IP address, preferred language, and software information.

## Description

This microservice is part of a learning project to understand how to handle HTTP request headers in Express. The service provides the following information:

- `ipaddress`: The client's IP address.
- `language`: The client's preferred language according to the `Accept-Language` header.
- `software`: The client's software, typically obtained from the `User-Agent` header.

### Example Response

The response will be a JSON object with the following structure:

```json
{
  "ipaddress": "159.20.14.100",
  "language": "en-US,en;q=0.5",
  "software": "Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:50.0) Gecko/20100101 Firefox/50.0"
}

### Endpoint

- **GET** `/api/whoami`

Technologies Used
Node.js: JavaScript runtime for the server.
Express: Web framework used to build the HTTP server.

##Deploy
[Request Header Parser Microservice](https://request-header-parser-microservice-raj0.onrender.com/)

