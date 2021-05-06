What does it mean that web sockets are bidirectional? Why is this useful?

Yes, websockets are bidirectional. This enables the server to send real-time updates
asynchronously, without requiring the client to submit a request each time

Does socket.io use HTTP? Why?

No it does not, it falls back on HTTP.

[Link](https://socket.io/docs/v4/index.html)

What happens when a client emits an event?

emit() to send a message to all the connected clients. This code will notify when a user connects to the server. io. on("connection", function(socket)

[Link](https://ably.com/topic/socketio)

What happens when a server emits an event?

The event gets passed to the server through websockets. Its a tcp connection from the browser to the server.

[Link](https://stackoverflow.com/questions/48332454/how-does-socket-io-on-the-client-listen-to-events-emitted-from-server)

What happens if a client “misses” an event?

Unhandled messages are just ignored. It's just like when an event occurs and there are no event listeners for that event. The socket receives the msg and doesn't find a handler for it so nothing happens with it.

[Link](https://stackoverflow.com/questions/25086603/signalr-client-misses-some-events-at-a-regular-interval)

How can we mitigate this?

You could avoid missing messages by always having the handlers installed and then deciding in the handlers 
(based on other state) whether to do anything with the message or not.

[Link](https://stackoverflow.com/questions/25086603/signalr-client-misses-some-events-at-a-regular-interval)


Socket-  a socket is an endpoint of a communication between two programs running on a network. Sockets are used to create a connection between a client program and a server program.

Web Socket- a computer communications protocol, providing full-duplex communication channels over a single TCP connection.

Socket.io- a library that enables real-time, bidirectional and event-based communication between the browser and the server.

Client- makes use of many different native JavaScript functions, methods, and opensource resources to find information about the client.

Server- a computer that provides data to other computers. 

OSI Model- (Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system.

TCP Model- Transmission Control Protocol, uses the client-server model of communication in which a user or machine.

TCP- (Transmission Control Protocol) is a standard that defines how to establish and maintain a network conversation
through which application programs can exchange data.

UDP- (User Datagram Protocol) is a communications protocol that is primarily used for establishing low-latency and loss-tolerating connections between applications on the internet.

Packets-  a small amount of data sent over a network, such as a LAN or the Internet.



