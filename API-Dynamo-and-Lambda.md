What are serverless functions?

are single-purpose, programmatic functions that are hosted on managed infrastructure. 

[Link](https://www.pubnub.com/blog/what-is-a-serverless-function/)

If you were to create a system that emulated Lambda functions, how would you do it?

Install the lambda dependencies

Initializes the event.json, context.json, .env, 
deploy.env files, and event_sources.json files. event.json is where you mock your event. 
context.json is where you can add additional mock data to the context passed to your lambda function.
.env is where you place your deployment configuration. deploy.env has the same format as .env,
but is used for holding any environment/config variables that you need to be deployed 
with your code to Lambda but you don't want in version control

[Link](https://www.npmjs.com/package/node-lambda)


Describe how a CDN works

An end user requests for static assets on your web page for the first time
The assets are retrieved from the origin server and once delivered are stored in the PoP edge 
caching server close to the end user.
When the same user requests the same assets the next time, the requests don’t go to the origin server. 
Instead the requests go to the cached files from the PoP server to see if the stored assets are still 
available and deliver them to the user.  If they are not available or 
the caching server has not cached the assets yet, the request is sent to the origin server again.

[Link](https://www.cdnetworks.com/web-performance-blog/how-content-delivery-networks-work/)

Serverless Functions- single-purpose, programmatic functions that are hosted on managed infrastructure.

Cloud Storage- n ever-growing list of storage bucket locations where you can store your data with multiple 
automatic redundancy options

CDN- (Content Delivery Network): a highly-distributed platform of servers that helps minimize delays 
in loading web page content by
reducing the physical distance between the server and the user.
