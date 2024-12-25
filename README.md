# mChat - A Simple Chat Application

## Overview

mChat is a simple chat application built using Java that allows users to log in, send and receive messages in a real-time chat environment. The application uses sockets to establish a client-server connection, enabling communication between multiple clients.

This application consists of a graphical user interface (GUI) built with Swing for displaying chat interactions, including user login, message sending, and chat history.

## Features

- **User Login**: Users can log into the chat by entering their username.
- **Real-Time Chat**: Users can send and receive messages instantly.
- **Message History**: Chat history is maintained and displayed for all messages sent and received.
- **Logout**: Users can log out of the chat, ending their session.
- **Socket Communication**: The application uses a simple socket connection to enable communication between clients.

## Requirements

To run mChat, make sure you have the following:

- Java Development Kit (JDK) installed on your system.
- A basic understanding of Java programming.
- A running server for handling the socket connections.

## How to Use

### Login:
1. Launch the application.
2. Enter your username and click **LOG IN** to begin the chat.

### Chat:
1. After logging in, you can type messages into the text area and click **SEND** to send them to other users.
2. The chat window will display all sent and received messages.

### Logout:
1. Click **LOG OUT** to end your session and disconnect from the chat.

## Running the Application

### Start the Server:
Before running the client application, ensure that the server (responsible for handling the socket connections) is running. You can modify the server settings in the `mchat` class to connect to the appropriate host.

### Run the Client Application:
1. Compile the `mchat.java` class using:
   ```bash
   javac mchat.java
