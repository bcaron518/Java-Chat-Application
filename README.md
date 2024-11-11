# Java Socket Chat Application

This is a simple chat application built using Java sockets. It allows multiple clients to connect to a server and exchange messages with each other in real time. The project demonstrates basic socket programming in Java.

## Features

- Server that can handle multiple clients simultaneously.
- Clients can join the server, send messages, and receive broadcast messages from other clients.
- Simple command-line interface for both client and server.

## Requirements

- **Java 8** or later

## Project Structure

- **ChatServer.java**: The server program that listens for incoming client connections, accepts them, and manages message broadcasting.
- **ChatClient.java**: The client program that connects to the server, sends messages, and displays received messages.

## How to Run

1. **Clone the Repository**:

   git clone https://github.com/your-username/java-socket-chat.git
   cd java-socket-chat

2. **Compile the Java Files**:

    javac ChatServer.java ChatClient.java

3. **Start the Server**:

    java ChatServer

4. **Start a Client**:

    java ChatClient

## Troubleshooting

- If clients cannot connect to the server, ensure the server is running and listening on the correct port.
- Make sure there are no firewall restrictions blocking the port.
- Check network settings if running the client on a different machine.

## Licence

This project is open-source and available under the MIT License.
