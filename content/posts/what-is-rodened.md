---
title: What is Apivis?
date: 2020-01-16T19:29:21.867Z
thumb_img_path: /images/asphalt-blur-car-290470.jpg
img_path: /images/asphalt-blur-car-290470.jpg
excerpt: >-
  The Apivis cloud-based editor is based on Node-RED which is open-source and
  maintained by JS Foundation with primary contributors coming from IBM and
  Hitachi. According to the Github project README, Node-RED is “a visual tool
  for wiring the Internet of Things.”
layout: post
---
<meta name="description" content="Learn more why the Apivis cloud editor is great for fast IT automation, MVP development, backend services, front-end testing, and service API creation. It is a visual programming tool built on Node.js and Node-RED making it incredibly lightweight. It is widely adopted and supported by a large community. Because of this, there are tons of example available online. Read the full story. ">

<meta name="keywords" content="fast IT automation, MVP development, backend services, front-end testing, service API creation, apivis editor, visual programming, no coding, integromat alternative, zapier alternative, activechat alternative">

The Apivis cloud-based editor is based on Node-RED which is open-source and maintained by JS Foundation with primary contributors coming from IBM and Hitachi.  According to the Github project README, Node-RED is “a visual tool for wiring the Internet of Things.”

## Not just for IoT

Node-RED is not just for IoT, but any kind of application involving workflows and/or event processing.  Developers can integrate data sources, APIs, and services with ease. Node-RED “code” is created in a flow, which is easily visualized by both expert and beginner developers alike. 

## Built on node.js

Node-RED is built on Node.js, taking full advantage of its event-driven, non-blocking model. This makes it incredibly lightweight and ideal to run at the edge of the network on low-cost hardware such as the Raspberry Pi as well as in the cloud. In Node-RED, flows are visual, so you can effectively draw your code as flows with drag and drop functionality.  Each box is referred to as a node. Node-RED nodes are connected together to create a Node-RED flow.

## Widely adopted

There are plenty of nodes prepackaged into Node-RED as well as thousands of additional nodes available on npm. One of the biggest benefits of Node-RED is how widely adopted and supported it is within the IoT and Node.js communities.\
Because of this, there are tons of examples available online. 

## Cookbook and example flows

The Node-RED website features both a cookbook full of recipes that solve common programming issues and over 1000 community sourced example flows.  Tasks like edge analytics, data ingestion, and server-side data migration can be handled with ease with a relatively simple flow.  More complex flows can be made manageable by using subflows.

## Version control

In the Apivis cloud editor, we are using the project setting as default.  The flows created are backed by a Git repository, meaning all of the files are fully version controlled and allow developers to use familiar workflows to collaborate with others.

## Frontend

Node-RED excels in building backend services, but building a simple web page could be a little more challenging. This article gives some tips and tricks:  
<a href="https://flows.nodered.org/flow/1bffe6808d37bd96cce283939983e758" target="_blank">Front-end Website with Node-RED using CSS/JS/HTML : Example Form</a>

##### Uibuilder

With the uibuilder node we can create a responsive UI. See the following example: [UIbuilder with MoonJS - simple, responsive UI quick example](https://flows.nodered.org/flow/e909c3fa700b68abe94cd822e46c084f)

##### Dashboard

With the [dashboard](https://flows.nodered.org/node/node-red-dashboard) node it is easy to make a dashboard to show input from IoT devices by using nodes for different gauges, tables, forms or graphs for time series. 

##### Freeboard

The freeboard [node](https://flows.nodered.org/node/node-red-contrib-freeboard) is also useful to create a dashboard. Follow the link to read more about it and see examples.

## Use cases

Connect IoT devices is an obvious use case. Here follows some other cases:

* Create a service API based on input from other service APIs.
* Continuous integration and development (CI/CD) Mock up a node-red back-end to test a [front-end](https://ordina-jworks.github.io/testing/2018/08/15/node-red-dev-ci.html)
* [API testing](https://ordina-jworks.github.io/testing/2018/01/04/3-stages-api-testing.html)
* Use node-red for testing other applications 

  The node-red-contrib-nbrowser node provides a virtual web browser (a.k.a. "headless browser") appearing as a node. The web browser is based on the open source electron.atom.io and nightmarejs.org projects. The node edit panel provides the ability to easily navigate and automate most web browser operations as well as display an interactive window for easy debugging. In headless mode the browser omits downloading images and is highly optimized for speed and performance. This makes testing and automation incredibly fast and versatile. Extended features include the ability to inspect DOM elements, upload & download files, and answer common dialogs. The node provides a high level browser automation node based on nightmarejs.org. [Node-RED node information and example](https://flows.nodered.org/node/node-red-contrib-nbrowser), [Github page](https://github.com/steveorevo/node-red-contrib-nbrowser)

## Testing the flows

It is important to be able to test that the flows you create work as intended.  Here is nodes that can be used for testing the [flows](https://github.com/node-red/node-red/wiki/Flow-testing)

## Support with flows

We have a Telegram chatbot that uses the latest in NLP, Natural Language Processing that can answer frequently asked questions about building flows with the Node-RED editor.
This Youtube video shows you how to use it:  https://youtu.be/wbkLMtuh8KA
