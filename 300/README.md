# 300 - Building Our Application

Based on "Part 2: LavinMQ for beginners - Sample code for Node.js" at https://www.cloudamqp.com/blog/lavinmq-for-beginners-part-2-getting-started-with-nodejs.html

The example follows a web application that allows users to upload a profile picture. Once the image is uploaded the user can traditionally decide what part of the image they want to show, scale it up or down and move it around.

The web application takes these instructions and the image and sends a request to the part of the system that is responsible for "Image Processing", which usually includes downsizing and web optimization.

The website handles the information, scales the image, and saves it in the new format. In the example, the entire scaling process will take several seconds. Let’s get started.

![image](https://github.com/vanHeemstraSystems/amqp/assets/1499433/cbf055ce-9296-42ef-b5e2-7fabb4ac1f75)

## 100 - Getting started with LavinMQ and Node.js

See [README.md](./100/README.md)
