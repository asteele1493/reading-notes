# Socket.io

[Web Sockets](https://en.wikipedia.org/wiki/WebSocket)

What is a Web Socket?

- A web socket is a communication protocol. It allows foor a web browser (client) to communicate with a web server with lower overhead than alternative communication methods such as HTTP polling. Offers real-time data transfer.

Describe the Web Socket request/response handshake and what happens once the connection is established.

- The handshake itself begins with an http req/res. HTTP connections and web sockets can use the same port. Once the connection is established, the communication switches to a bidirectional binary protocol. This protocol does not conform to HTTP protocols. The client will also need to send a websocket key header, which will receive a server response with a hash of the key in the websocket accept header.

Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.

- request

[Socket.io tutorial](https://www.tutorialspoint.com/socket.io/)

What does the event handler io.on() do?

- The event handler turns on socket.io (i think). By using the .on method, we're able to listen to events.

[Added resource](https://stackoverflow.com/questions/33703546/difference-between-io-on-and-socket-on-in-socket-io)

What does socket.emit() do?

- This method is inspired by the EventEmitter. In Socket.io, you can emit events on one side and register listeners on the other.

[Socket.io vs. Web Sockets](https://www.educba.com/websocket-vs-socket-io/)

What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

- WebSocket is the library and Socket.IO is the framework that can operate within the protocol?

When would you use Socket.IO?

- Anytime you implement WebSockets. To my understanding, Socket.IO just makes creating applications that use the WebSocket protocol easier to streamline, access, and read.

When would you use WebSockets?

- When you want two-way communication between two networked systems.

[VIDEO: OSI model explained](https://www.youtube.com/watch?v=vv4y_uOneC0)

What are a couple of key takeaways from this video?

- Breaks down the layers that are involved in having two computer systems talk to each other.

- This video felt very meta to me. Almost like computer inception. Took the OSI model and dove deep into each component involved.

[VIDEO: TCP Handshakes explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)

Translate the gist of this video to a non-technical friend

-

## Bookmark & Review

[DOCUMENTATION: Socket.io](https://socket.io/docs/)

[Socket.io Server API](https://socket.io/docs/server-api)

[Socket.io Client API](https://socket.io/docs/client-api)

[Socket Testing tool](https://amritb.github.io/socketio-client-tool/)
