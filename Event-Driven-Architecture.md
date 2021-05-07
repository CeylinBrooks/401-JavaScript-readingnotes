What’s the difference between a FIFO and a standard queue?

FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once processing.

[Link](https://aws.amazon.com/about-aws/whats-new/2016/11/amazon-sqs-introduces-fifo-queues-with-exactly-once-processing-and-lower-prices-for-standard-queues/#:~:text=FIFO%20queues%20have%20essentially%20the,being%20received%20by%20message%20consumers.)

How can the server be assured a message was properly received?

TCP/IP cannot guarantee that all data that have been sent will also be received.
But even if it would guarantee it that is not what you need. What sender actually needs is to know if it does not have to send data again,
and that usually implies if sent data has been processed on receivers side.

[Link](https://stackoverflow.com/questions/16731849/check-if-data-has-been-received-socket-c-sharp)


What classic design pattern is best represented by event driven programming?



How do you test an event driven system?


FIFO Queue- 

Pub/Sub- 
