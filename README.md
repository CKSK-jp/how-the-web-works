# how-the-web-works
15.1 Exercises on how the web works

## **Part One: Solidify Terminology**

In your own terms, define the following terms:

- What is HTTP?

HTTP (hypertext transfer protocol) is the protocol that governs the Web and how pages/links are loaded from a server to the client.

- What is a URL?

A URL (uniform resource locators) serves as the address for an unique resource on the Web. The URL typically includes: a prototcol (http/https), a domain name/IP address, and a path to the resource.

- What is DNS?

The DNS (domain name system) translates domain names to an assigned IP address. 

- What is a query string?

A query string is used to pass parameters into a web page/server. Usually starts with a "?" after the URL.

- What are two HTTP verbs and how are they different?

1. GET - method that requests data from resource
2. POST - method that submits data to be processed

- What is an HTTP request?

A HTTP request comprises of two main parts:
1. A request line that contains the HTTP method/verb (GET) + URL + HTML Version
2. Headers that can include specific requests from the client or host 

- What is an HTTP response?

A HTTP request comprises of three main parts:
1. The status line which has the HTTP version and a three-digit status code + a readable message
2. Headers - that provide additional information about the server
3. Body - actual data that is being sent from the server to client

- What is an HTTP header? Give a couple examples of request and response headers you have seen.

Headers are components of the HTTP protocol that provide more information about the client request/response
1. General Headers
2. Request Headers
2. Response Headers
3. Entity Headers

eg. www-authentication (request header)
eg. Cookie headers (response header)

- What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?

1. URL parsing occurs - browser will extract info from the URL (http, domain, and path)
2. DNS resolution then translates the domain name to an IP address
3. A TCP (Transmission Control Protocol) is established to the server using the IP and HTTP Port
4. The HTTP request from the browser to server is made that includes the path and headers
5. Server will process the request
6. A resulting HTTP response is received that includes the headers and body of the content
7. Page is rendered onto the browser
8. Browser caching occurs