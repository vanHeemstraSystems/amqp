# 100 - Introduction

Based on "Part 2: LavinMQ for beginners - Sample code for Node.js" at https://www.cloudamqp.com/blog/lavinmq-for-beginners-part-2-getting-started-with-nodejs.html

Welcome to LavinMQ for beginners! This article is the second in a series of LavinMQ and will take you through code examples with Node.js, steps to set up your own LavinMQ instance, and a relatable example of a working LavinMQ system to follow for yourself. The guide goes on to explain the steps to set up a connection and the basics of publishing/consuming messages from a queue.

This article assumes that you have a running LavinMQ server installed, if not - get started with a free LavinMQ plan at [CloudAMQP](https://www.cloudamqp.com/plan.html).

This tutorial follows the scenario used in the previous article, [Part 1: LavinMQ for beginners - What is LavinMQ?](https://www.cloudamqp.com/blog/lavinmq-for-beginners-part-1-what-is-lavinmq.html)

The example follows a web application that allows users to upload a profile picture. Once the image is uploaded the user can traditionally decide what part of the image they want to show, scale it up or down and move it around.

The web application takes these instructions and the image and sends a request to the part of the system that is responsible for "Image Processing", which usually includes downsizing and web optimization.

The website handles the information, scales the image, and saves it in the new format. In the example, the entire scaling process will take several seconds. Let’s get started.

