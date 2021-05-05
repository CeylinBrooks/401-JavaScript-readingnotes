What is the benefit of transforming data into packets?

Packets are intended to transfer data reliably and efficiently. Instead of transferring a large file as a single block of data, sending smaller packets helps ensure each section is transmitted successfully.

[Link](https://techterms.com/definition/packet)


UDP is often refereed to as a connectionless protocol. Why is this?

UDP is a connectionless protocol. No connection needs to be established between the source and destination before you transmit data. UDP does not have a mechanism to make sure that the payload is not corrupted. As a result, the application must take care of data integrity all by itself.

[Link](https://www.sciencedirect.com/topics/computer-science/connectionless-protocol#:~:text=UDP%20is%20a%20connectionless%20protocol,data%20integrity%20all%20by%20itself.)


Can a socket server application have multiple socket connections?

A server socket listens on a single port. All established client connections on that server are associated with that same listening port on the server side of the connection.

[Link](https://stackoverflow.com/questions/11129212/tcp-can-two-different-sockets-share-a-port#:~:text=5%20Answers&text=A%20server%20socket%20listens%20on%20a%20single%20port.&text=Multiple%20connections%20on%20the%20same,system%20resources%20allow%20it%20to.)


Can a socket connection application be connected to multiple socket servers?

Multiple connections on the same server can share the same server-side IP/Port pair as long as they are associated with different client-side IP/Port pairs, and the server would be able to handle as many clients as available system resources allow it to.

[Link](https://stackoverflow.com/questions/11129212/tcp-can-two-different-sockets-share-a-port#:~:text=5%20Answers&text=A%20server%20socket%20listens%20on%20a%20single%20port.&text=Multiple%20connections%20on%20the%20same,system%20resources%20allow%20it%20to.)


Can an application be both a socket server and a socket connection?

I am unsure, there is conflicting information about it. 

[Link](https://www.quora.com/Can-you-make-a-client-socket-and-a-server-socket-in-one)

Observer Pattern- a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.

Listener- An event sink,  is a piece of coding that defines how a server or computer is to handle given events.

Event Handler-  scripts that are automatically executed when an event occurs.

Event Driven Programming- a programming paradigm in which the flow of the program is determined by events such as user actions (mouse clicks, key presses), sensor outputs, or message passing from other programs or threads.

Event Loop- a programming construct or design pattern that waits for and dispatches events or messages in a program.

Event Queue- a programming construct or design pattern that waits for and dispatches events or messages in a program.

Call Stack- a mechanism for an interpreter, to keep track of its place in a script that calls multiple functions.

Emit/Raise/Trigger- To Emit the event. To Rasie the event. To Trigger the event.

Subscribe- arrange to receive something regularly, typically a publication, by paying in advance. 

Database- a structured set of data held in a computer, especially one that is accessible in various ways.


