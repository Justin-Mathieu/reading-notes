# Socket.io and Websockets

## Web Sockets

What is a Web Socket?

- A protocal for computer communications, over a single TCP connection.  

Describe the Web Socket request/response handshake and what happens once the connection is established.

- The client sends the web socket request handshake request(HTTP protocol). Then the server returns the response of the handshake.  

Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.

- Once the connection is established the client does not need to send a request to recieve from the web socket.

## Socket.io Tutorial

What does the event handler io.on() do?

- io.on handles the connection of the web socket and the client.  

Describe some possible proof of life or proof that the code works as expected

- You could go to the url that you are connecting to to simulate a user connection and then print in the console the connection and testy it that way.  

What does socket.emit() do?

- socket.emit fires off an event.  

## Socket.io vs Web Sockets

What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

-

When would you use Socket.IO?

- If multiple sockets are needed.  

When would you use WebSockets?

- When only one socket is needed and TCP connections are prefered.  

## OSI Model Explained  

What are a couple of key takeaways from this video?

- OSI model are the layers of protocals and processes that allows computers talk to eachother in the different ways.

- Application layer for protocols like HTTP FTP and SMTP.  

- Presentation layer translates and cpomresses data which improves speed of transmission also encrypts data.  

- Session layer sets up connections and disconnections (Authentication and Authorization) also keeps track of what is being downloaded(Session Management).  

- Transport layer handles the data that is recieved from the session layer and divides it into segments containing the port number and sequence number and sends to the correct application. Contols flow/amount of data. Handles errors.  

- Networking layer controls routing path determination and addressing(IP address) via packets.

- Data link layer handles physical addressing frames data packets(accessing media and error detection).

- Physical layer converts data to signal to send data.  

## TCP Handshakes Explained

Translate the gist of this video to a non-technical friend

- Transmission Control protocal uses a threeway handshake to establish a connection, the client sends a request to connect server sends a sychronization acknowledgement and request to open connection then the client sends its own acknowledgment the the connection is established.
