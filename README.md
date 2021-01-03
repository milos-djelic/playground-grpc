# GRPC Server and Client in Node.js

## Installation

```
npm i
```

## Run the project 

Start the server. It will provide the calls for creating and retching todo items
```
node server.js
```

Start the client from another terminal window and pass the message text. It calls server functions and creates a new todo item, and then fetches one by one all created list items. 
```
node client.js $MESSAGE_TEXT
```
