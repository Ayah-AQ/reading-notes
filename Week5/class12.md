## Socket.io Chat Example

>Q1: Explain to a non-technical recruiter what the Chat Example (above) does.
>The Chat Example is a demonstration of a chat application that allows people to talk to each other in real-time.

>Q2: What proof of life are we getting on the backend from the above app?
>>The backend of the app receives and processes messages from users, and sends responses back to them.

>Q3: Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
>>To exclude a specific user, we can use the `socket.broadcast.emit()` method.

## Rooms

>Q1: What is a room and how might a room be useful?
>>A room is a virtual group where users can join. It helps organize and manage communication between specific groups of users.

>Q2: How do you join a room?
>>To join a room, you use the `socket.join('roomName')` method.

>Q3: how do you leave a room?
>>To leave a room, you use the `socket.leave('roomName')` method.

## Namespaces

>Q1: What is a Namespace and what does it allow you to do?
>>A namespace is like a separate channel for communication. It allows you to organize different parts of your app and handle them independently.

>Q2: Each namespace potentially has its own what? (hint: 3 things)
>>Each namespace potentially has its own sockets, events, and configuration.

>Q3: Discuss a possible use case for separate namespaces
>>Separate namespaces in Socket.IO let each organization have their own private messaging space, ensuring privacy and customization. It simplifies management, improves security, and supports scalability in the application.
