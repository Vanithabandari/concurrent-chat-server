# Project: Concurrent Chat Server
## **Overview**

Concurrent Chat Server is a multi-client chat application built entirely using core Java (no external frameworks).

It allows multiple users to connect to a central server, exchange real-time messages, and share files over a TCP/IP network.

This project demonstrates network programming, multithreading, and clean OOP design.

## **Key Features**

- **Multi-client Support:** Handles many simultaneous users using **ExecutorService** and **ClientHandler** threads.

- **Real-Time Messaging:** Broadcast messages to all connected clients.

- **Private Messaging:** /whisper <username> <message> for one-to-one chat.

- **File Transfer:** Send text or binary files between clients.

- **Command System:** /list to view online users, /rename to change username, /quit to disconnect.

- **Robust Error Handling & Logging:** Graceful disconnects and detailed server logs.

## Tech Stack
- **Language:** Java 24 (LTS Compatible)
- **Core Libraries:** java.net, java.io, java.util.concurrent
- **Build Tools:** Maven *(optional - can run with plain javac)*
