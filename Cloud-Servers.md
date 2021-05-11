Describe the Web-Request-Response-Cycle

A user opens his browser, types in a URL, and presses Enter.
When a user presses Enter, the browser makes a request for that URL.
The request hits the Rails router (config/routes.rb). The router maps the URL to the correct controller and action to handle the request.
The action receives the request and passes it on to the view.
The view renders the page as HTML.
The controller sends the HTML back to the browser. The page loads and the user sees it.

[Link](https://www.codecademy.com/articles/request-response-cycle-static#:~:text=The%20request%2Fresponse%20cycle%20traces,things%20aren't%20working).)


Explain what a “server” is, as it relates to the WRRC

The client (usually a browser) opens a connection to the server and sends a request. The server processes the request, generates a response, and closes the connection if it finds a Connection: Close header. ... Headers are typically only sent for POST and PUT methods.


Web browsers communicate with web servers using the HyperText Transfer Protocol (HTTP). 

[Link](https://docs.oracle.com/cd/E19857-01/820-7655/abvah/index.html)


What does it mean to “deploy” an application?

Software deployment refers to the process of running an application on a server or device.

[Link](https://www.sumologic.com/glossary/software-deployment/#:~:text=Software%20deployment%20refers%20to%20the,on%20a%20server%20or%20device.&text=Software%20deployment%20refers%20to%20the%20process%20of%20making%20the%20application,user's%20computer%20or%20mobile%20device.)

Server- is a computer that provides data to other computers

Pub/Sub-  an asynchronous messaging service that decouples services that produce events from services that process events.

WRRC- Web Request Response Cycle


