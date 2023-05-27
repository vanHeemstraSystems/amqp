# 100 - Getting started with LavinMQ and Node.js

Start by downloading the client-library for Node.js. Node developers have a number of options for AMQP client libraries. In this example is [amqplib](https://github.com/squaremo/amqp.node/) used. Start by adding [amqplib](https://github.com/squaremo/amqp.node/) as a dependency to your package.json file.

Full code can be downloaded from [GitHub](https://github.com/cloudamqp/nodejs-amqp-example/tree/master/amqplib).

Queues and exchanges will be declared and created if they do not already exist and, finally, a message is published. The publish method queues messages internally if the connection is down and resends them later. Once the consumer subscribes to the queue, the messages are handled one by one and sent to the image processor.

A default exchange, identify by the empty string ("") will be used. The default exchange means that messages are routed to the queue with the name specified by routing_key, if it exists. (The default exchange is a direct exchange with no name)


