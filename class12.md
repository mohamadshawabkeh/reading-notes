# Socket.io

## Web Sockets

### What is a Web Socket?

A Web Socket is a communication protocol that enables real-time, full-duplex communication between a client and a server over a single TCP connection.

### Describe the Web Socket request/response handshake and what happens once the connection is established.

During the Web Socket request/response handshake:
1. The client sends a WebSocket upgrade request to the server.
2. The server responds with a WebSocket upgrade response, indicating a successful handshake.
Once the connection is established, both the client and server can send messages to each other in real-time.

### Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.

Web Sockets provide a standardized way for the server to send content to a client without first receiving a request from that client, eliminating the need for continuous polling and enabling efficient real-time communication.

## Socket.io Tutorial

### What does the event handler io.on() do?

The event handler `io.on()` listens for incoming events from connected clients on the server-side, allowing the server to respond accordingly.

### Describe some possible proof of life or proof that the code works as expected.

To verify that the code works as expected, you can:
1. Establish a WebSocket connection between client and server.
2. Send test messages between client and server to ensure successful communication.
3. Validate specific functionalities and scenarios to ensure expected behavior.

### What does socket.emit() do?

`socket.emit()` is used on the client-side to send custom events or messages to the server via the WebSocket connection, enabling client-server communication and event triggering.

## Socket.io vs Web Sockets

### What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

WebSocket is a low-level communication protocol, while Socket.IO is a JavaScript library that abstracts WebSocket and provides additional features for real-time communication.

### When would you use Socket.IO?

Socket.IO is ideal for applications requiring real-time, event-based communication, such as chat apps, collaborative tools, and live dashboards.

### When would you use WebSockets?

WebSockets are used for direct, high-performance, bidirectional communication, suitable for applications like online gaming, stock market tickers, and live sports updates.


## OSI Model Explained

### What are a couple of key takeaways from this video?

- Each layer has a specific set of responsibilities and performs distinct functions, enabling the reliable and efficient transmission of data.

- The layering approach allows for modular design, flexibility, and interoperability between different network components and technologies.

- The OSI model provides a common language and reference point for network engineers and developers, facilitating troubleshooting, communication, and network design.

 ### TCP Handshakes Explained
 
TCP handshakes are like saying 'hello' and making sure the other device is ready to talk before starting a conversation on the internet. It's a way for devices to establish a connection and ensure smooth communication.

### return to [Main Read Me File](./README.md)
