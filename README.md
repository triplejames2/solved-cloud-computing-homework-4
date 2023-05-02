Download Link: https://assignmentchef.com/product/solved-cloud-computing-homework-4
<br>
<strong>Messaging in Docker images</strong>

A messaging queue is used to store and communicate between threads. Message queues and mailboxes are software-engineering components used for inter-process communication (IPC), or for inter-thread communication within the same process. They use a queue for messaging – the passing of control or of content. Group communication systems provide similar kinds of functionality.

This time you need to run RabbitMQ to realize a message exchanging between docker microservices. To understand the message exchange in micro services, check <a href="https://codeburst.io/using-rabbitmq-for-microservices-communication-on-docker-a43840401819">this</a>.

Now you need to configure and build RabbitMQ to exchange messages between all docker images in your previous setup, including but not limited to text, text files, image files, and/or videos.

Some general hints on RabbitMQ can be found in here <a href="https://github.com/docker-library/docs/tree/master/rabbitmq/">RabbitMQ</a>

You may need to learn language Go for understanding RabbitMQ, the documents can be found <a href="https://golang.org/doc/faq">here</a>.

To test your Messaging Queue performance, check <a href="https://developer.ibm.com/messaging/2018/01/31/mq-performance-tests-docker/">MQ performance Test</a>.