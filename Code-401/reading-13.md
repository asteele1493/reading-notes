# Messsage Queues

[Socket.io Chat Example](https://socket.io/get-started/chat/)

**Explain to a non-technical recruiter what the Chat Example (above) does.**

- The example walks us through how to build a simple application using a server and client to successfully send and receive data, in this case, messages in a chatbox.

**What proof of life are we getting on the backend from the above app?**

- What port the server is running on.

**Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?**

- The broadcast flag. When we want to sent an event to everyone, we would use the emit() method.

[Rooms](https://socket.io/docs/v4/rooms)

**What is a room and how might a room be useful?**

- A room is a channel that sockets can join and leave. Rooms are also a server-only concept. Rooms can be useful because they at their core, connect a group of users. Reminds me of the single-responsibility principle. They could be important to distinguish different intentions.

**How do you join a room?**

- To join a room, you would use the socket.join() method

**How do you leave a room?**

- To leave a room, you would use the socket.leave() method; used in the same fashion as joining.

[Napespaces](https://socket.io/docs/v4/namespaces/)

**What is a Namespace and what does it allow you to do?**

- A namespace is a communication channel that allows you to split the logic of your application over a single shared connection. Namespaces allow you to split the logic of an application by utilizing a single channel.

**Each namespace potentially has its own what? (hint: 3 things)**

- Each namespace has its own connection?

**Discuss a possible use case for separate namespaces**

- Having a separate namespace for admins versus users.

## Bookmark & Review

[Socket.io Emit Cheatsheet](https://socket.io/docs/v4/emit-cheatsheet/)