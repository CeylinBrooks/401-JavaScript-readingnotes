Name 3 real world use cases where you’d want to change the request with custom middleware.

1.Log in authentication

2. To confirm after log in that a user has an account

3. To save user information

True or false: The route handler is middleware? True, middleware is code that examines an incoming request and prepares it for further processing by other handlers or short circuits the processing 


https://stackoverflow.com/questions/58925276/what-is-the-difference-between-a-route-handler-and-middleware-function-in-expres

In what ways can a middleware function end the process and send data to the browser? Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle.

https://medium.com/@selvaganesh93/how-node-js-middleware-works-d8e02a936113

At what point in the request lifecycle can you “inject” middleware?

Middleware lifecycle begins after the request and prior to the response.




What can cause express to error with “Request headers sent twice, cannot start a second response”?

The following callback function not being invoked


Term
Middleware- functions that execute between request and response.
Request Object- the data sent from the client to the server.
Response Object- the data sent from the server to the client.
Application Middleware- a software working between request and response.
Routing Middleware- a routing software working between request and response
Test Driven Development- application creation driven by periodic testing.
Behavioral Testing- a branch of Test Driven Development .










