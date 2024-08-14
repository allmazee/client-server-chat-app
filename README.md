# Cleint-server chat application

This is a multithreaded chat application based on Java—Sockets API. The application allows multiple clients to connect to a server and send messages to each other in real time. Users' data (including encrypted passwords) and their messages are stored in a database.

## Technologies

The application is built using the following technologies and frameworks:

- Java 8

- Apache Maven

- Spring framework

- Spring Security

- Java Sockets API

- JDBC

- PostgreSQL

## Installation

#### Starting the server

In the SocketServer root folder run the following commands:

`mvn clean package`

`java -jar target/socket-server.jar --port=8081` 

#### Starting the client

In the ClientSocket root folder run the following commands:

`mvn clean package`

`java -jar target/socket-client.jar --server-port=8081`


