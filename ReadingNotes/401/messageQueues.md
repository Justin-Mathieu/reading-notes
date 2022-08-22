# Message Queues 

## Socket.io Chart Example

Explain to a non-technical recruiter what the Chat Example (above) does.

- Creates an express server and uses socket io to allow the two browsers to communicate with each other via the same port/server

What proof of life are we getting on the backend from the above app?

- The console logs when the connection is made and disconnected.

Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

- You would use the braodcast flag.  


## Rooms 

What is a room and how might a room be useful?

- Can be a good way to divide up the sockets to broadast to multiple at once in specific groups.

How do you join a room?

- Using the join method on the socket and defining the room. 

how do you leave a room?

- Same as join just using the leave method.  

## Namespaces

What is a Namespace and what does it allow you to do?

- A joint communication channel used to split the logic.  

Each namespace potentially has its own what? (hint: 3 things)

- Middlewares, event handlers and rooms.  

Discuss a possible use case for separate namespaces

- An admin namespace or a namespace that can only be used by authorized users and is separate.  
