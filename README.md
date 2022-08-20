# Django Websocket Chatapp

## Real Time communication
- Websockets and django channels was used in creating this real time chat app.
- Channels is a django library which is used to communicate between the server and the client. It takes django and extends it beyond HTTP to handle Websockets, Chat protocols, IoT protocols and more. it is built on a python specification called ASGI-Asynchronous Server Gateway Interface.
- Websockets is a protocol which is used to communicate between the client and the server. It is a protocol which is used to send and receive data over a network.
- Channels and Websockets will be used to make a two-way communication between the client and the server. Websocket on the client side to initiate connection and channels on the server side to receive and send data back to the client.
- Channel layers allows one to create an interaction between different instances of an application for real time communication.

## 4 key steps to setup the server and create a socket connection
- Configure ASGI: switch the django project to use ASGI, complete basic channels configurations after installation.
- Consumers: create consumers which are the channels version of django views.
- Routing: create routing to handle URL routing for the consumers.
- Websockets: using the built-in javascript websocket API on the client side to initiate handshake and establish connection between the client and the server.
