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


Can an application be both a socket server and a socket connection?

