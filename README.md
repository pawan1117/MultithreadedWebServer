# Multithreaded Web Server

## Overview
This project features a simple multithreaded web server and client implementation in Java. The server is designed to handle multiple client connections simultaneously using threads. Each client connection is handled by a separate thread, allowing the server to serve multiple clients concurrently.

## Features
- **Multithreading**: The server can handle multiple clients at the same time using separate threads.
- **Basic Communication**: Clients can send a message to the server and receive a response.
- **Scalability**: The client implementation creates multiple threads to test server performance under load.

## Getting Started
To run this project, you will need Java installed on your system.

### Prerequisites
- Java Development Kit (JDK) 8 or later

### Running the Server
1. Open a terminal and navigate to the directory containing the server code.
2. Compile the server code:
    ```sh
    javac Server.java
    ```
3. Run the server:
    ```sh
    java Server
    ```

### Running the Client
1. Open another terminal and navigate to the directory containing the client code.
2. Compile the client code:
    ```sh
    javac Client.java
    ```
3. Run the client:
    ```sh
    java Client
    ```

## Testing
The client will attempt to connect to the server 100 times simultaneously. Each client thread will send a message to the server and print the response received from it.

## Code Structure
- `Server.java`: Contains the implementation of the multithreaded server.
- `Client.java`: Contains the implementation of the client that connects to the server.

![image](https://github.com/user-attachments/assets/28d9d814-62a1-4e0c-a139-15d94f1fa673)
