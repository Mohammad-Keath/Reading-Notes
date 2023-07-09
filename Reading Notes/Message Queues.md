
- ## Message Queues   .  [<sub>    Reference </sub>](https://canvas.instructure.com/courses/6888396/discussion_topics/18305207/submit)
   - ### Socket.io Chat Example
      1. #### Explain to a non-technical recruiter what the Chat Example (above) does.
         - it simply add the message to the screen without any res and it will aoutomaticly refreshed to show you the messages immediatly
      2. #### What proof of life are we getting on the backend from the above app?
         - it easier our lifes to make a simple chat with users, and it will be very fast and useful
      3. #### Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
         - socket.emit()
   - ### Rooms
      1. #### What is a room and how might a room be useful?
         - we use room to send messages to specifec group of people not all of them, and it is useful because it will minimius the load on the server and make the chat more secure and specific
      2. #### How do you join a room?
         - io.on("connection", (socket) => {
            socket.join("some room");
           });
      3. #### how do you leave a room?
         - io.on("connection", (socket) => {
            socket.leave("some room");
           });
   - ### Namespaces
      1. #### What is a Namespace and what does it allow you to do?
         - name space is a division of the main channel to small ones, and it makes the main more secure and it will minumise the load on the main sever
      2. #### Each namespace potentially has its own what? (hint: 3 things)
        - event handlers , rooms, middlewares
      3. #### Discuss a possible use case for separate namespaces.
         - when you want to enable specific user to join it not the others, so you will make it secure 