
# Multi-client Chatroom Application using NodeJS, socket.io and Redis

Implemented a chat room among multiple clients. Functionality is as described below:
* When the client requests the connection, the server prompts for the client’s nickname. Thus, each client should register with the server with his/her nickname.
* The messages on the chat room shows the nickname of the person posting the chatting message.
* The messages are be broadcasted to all the clients: so it is a real chat so that everyone sees who posted what message.
* Redis is used to provide persistent data handling in the message board. If someone joined later then the prior messages up to that point are visible to the recently joined participant of the chat.

###How to run
### How to run
Make sure Redis server is up and runnning.
Navigate to directory containing above code. Start the server using following command:
```
	node app.js
```

In web browser, enter following URL to execute [localhost:3001/chatroom](http://localhost:3001/chatroom)