- ## Socket.io   .  [<sub>    Reference </sub>](https://canvas.instructure.com/courses/6888396/discussion_topics/18305208/submit)
- ### Web Sockets
    1. #### What is a Web Socket?
        - protocol enables interaction between a web browser (or other client application) and a web server with lower overhead than half-duplex alternatives such as HTTP polling, facilitating real-time data transfer from and to the server.
    2. #### Describe the Web Socket request/response handshake and what happens once the connection is established.
       - The handshake starts with an HTTP request/response, allowing servers to handle HTTP connections as well as WebSocket connections on the same port. Once the connection is established, communication switches to a bidirectional binary protocol which does not conform to the HTTP protocol.
    3. #### Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.
       - request
- ### Socket.io Tutorial
    1. #### What does the event handler io.on() do?
       -Be ready to listen the incoming events from the client.
    2. #### Describe some possible proof of life or proof that the code works as expected
       - they use it to send notification and show them to the users with no need to open the app
    3. #### What does socket.emit() do?
       - It is like the button to click to do function but with no need to press it because it will work spontaneously
- ### Socket.io vs Web Sockets
    7. #### What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).
       - Websocket is a ommunication protocal while Soket.IO is a library that works on the websocket
       - WebSocket doesn’t have fallback options while Socket.io supports fallback.
       - WebSocket is the technology, while Socket.io is a library for WebSockets.
    8. #### When would you use Socket.IO?
       -  all platform, server or device, ensuring equality, reliability, and speed.
       
    9. #### When would you use WebSockets?
       - the most used one and easier to help with vanilla web sockets
       most work with website that needs broadcasting

