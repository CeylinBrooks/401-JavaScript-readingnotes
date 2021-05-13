Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server

*Express Gateway* is an API Gateway that can sit at the heart of any microservices architecture,
regardless of what language or platform you’re using. Express Gateway secures your microservices and exposes 
them through APIs using Node.js, ExpressJS and Express middleware.

*Amazon’s API Gateway* is a fully managed service that makes it easy for developers to create, publish, 
maintain, monitor, and secure APIs at any scale.

[Link](https://www.express-gateway.io/eg-vs-amazon-aws-api-gateway/)


List the AWS Database offerings and talk about the pros and cons of each

Pros and Cons
Availability on several database instances
Six familiar database to chose from
Efficient
Scalable
Cost reduction
Resizable capacity
Automating time consuming administration tasks
No root access to server.
Downtime required
Not a zero administration database

[Link](https://www.trustradius.com/products/amazon-relational-database-service/reviews?qs=pros-and-cons))

What’s the difference between a FIFO and a standard queue?

FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once processing. FIFO queues provide additional features that help prevent unintentional duplicates from being sent by message producers or from being received by message consumers

[Link](https://aws.amazon.com/about-aws/whats-new/2016/11/amazon-sqs-introduces-fifo-queues-with-exactly-once-processing-and-lower-prices-for-standard-queues/#:~:text=FIFO%20queues%20have%20essentially%20the,being%20received%20by%20message%20consumers.)

How can the server be assured a message was properly received?

Server receives a request. Now server can continue or reject processing this request. When accepts, a further appropriate computation is made and the outcome is then provided to the initiator. Client gets a response and a circuit is closed. 


Serverless API- A resource of this type is implicitly created from the union of Api events defined on AWS::Serverless::Function resources defined in the template that do not refer to an AWS::Serverless::Api resource.

Triggers-  a Lambda resource or a resource in another service that you configure to invoke your function in response 
to lifecycle events, external requests, or on a schedule.

Dynamo vs Mongo- 

MongoDB is vendor agnostic, Open Source, and can be deployed anywhere. DynamoDB is only available on AWS.
DynamoDB is a fully managed AWS service, MongoDB can be self installed or fully managed with MongoDB Atlas.
DynamoDB as an integrated AWS service makes it easier to develop end to end solutions.
DynamoDB uses tables, items and attributes, MongoDB uses JSON-like documents.
DynamoDB supports limited data types and smaller item sizes; MongoDB supports more data types and has fewer size restrictions.

Dynamoose vs Mongoose- 

Dynamoose is a modeling tool for Amazon's DynamoDB

Mongoose provides a straight-forward, schema-based solution to model your application data. It includes built-in type casting, validation, query building, business logic hooks and more, out of the box.
