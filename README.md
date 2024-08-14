# Cleint-server chat application

This is a multithreaded chat application based on Java—Sockets API. The application allows multiple clients to connect to a server and send messages to each other in real time. Users' data (passwords are encrypted) and their messages are stored in a database.

## Starting the server

In the SocketServer root folder run the following commands:

`mvn clean package`

`java -jar target/socket-server.jar --port=8081`

Starting the client
-------------------



In the ClientSocket root folder run the following commands:

`mvn clean package`

`java -jar target/socket-client.jar --server-port=8081`


