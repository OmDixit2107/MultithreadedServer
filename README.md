# Multithreaded Server and Client Application

This project implements a **multithreaded client-server application** using **Java** and **networking libraries**. The application demonstrates how to manage simultaneous client connections in a server, handling each client in a separate thread for concurrent communication.

## Features
- **Multithreaded Server**: The server listens on port `8010` and handles multiple client requests concurrently using separate threads for each connection.
- **Client Program**: The client connects to the server, sends a message, and waits for a response. Multiple clients can be spawned, demonstrating the server’s capability to handle multiple connections simultaneously.
- **Real-Time Communication**: Utilizes Java's `Socket` and `ServerSocket` classes for efficient real-time communication between the client and server.
- **Single-Threaded Version**: Also includes a simple single-threaded server implementation to demonstrate basic socket programming without concurrency.

## Project Structure
- **Client.java**: Implements the client that connects to the server and sends messages.
- **Server.java**: Implements the multithreaded server that handles incoming client connections.
- **SingleThreadedServer.java**: A simplified version of the server, handling requests sequentially without multithreading.

## Getting Started

### Prerequisites
- Java 8 or higher
- A basic understanding of Java networking concepts

### Running the Server
1. Clone this repository:
   ```bash
   git clone https://github.com/OmDixit2107/MultithreadedServer.git
   cd MultithreadedServer

