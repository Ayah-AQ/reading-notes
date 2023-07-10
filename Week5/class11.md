
## Web Sockets

>Q1: What is a WebSocket?
>>A WebSocket is a technology for real-time communication between a web browser and a server.

>Q2: Describe the WebSocket request/response handshake and what happens once the connection is established.
>>The WebSocket handshake is when the browser and server exchange information to connect. Once connected, they can communicate in real-time.

>Q3: What is a standardized way for the server to send content to the client without being first requested by the client?
>>WebSocket allows the server to send content to the client without the client asking for it, enabling real-time updates.

## Socket.io Tutorial

>Q1: What does the event handler io.on() do?
>>The io.on() event handler listens for specific events from clients and triggers a function when those events occur.

>Q2: Describe some possible proof of life or proof that the code works as expected.
>>Proof can be provided through testing, checking inputs and outputs, logging, and having another developer review the code.

>Q3: What does socket.emit() do?
>>socket.emit() lets the server send custom events to clients.

## Socket.io vs Web Sockets

>Q1: What is the difference between WebSocket and Socket.IO?
>>WebSocket is a communication protocol, while Socket.IO is a library that simplifies real-time communication using WebSocket and adds extra features.

>Q2: When would you use Socket.IO?
>>Socket.IO is used when you need real-time communication with features like automatic reconnection and browser compatibility.

>Q3: When would you use WebSockets?
>>WebSockets are used when you need a fast, bidirectional connection for real-time updates in applications.

## OSI Model Explained
```
The video explains that before data is sent over the internet, there is a process of establishing a connection, similar to introducing yourself before a conversation. Once connected, devices can communicate in real-time. It's an important step for sharing information quickly.
```