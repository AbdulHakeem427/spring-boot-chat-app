# Real-Time Chat Application

A real-time chat application built with **Spring Boot**, **WebSocket**, **STOMP**, and **Thymeleaf** that enables multiple users to communicate instantly in a chat room.

## Features

- Real-time messaging with **WebSocket** for continuous two-way communication  
- Message routing and broadcasting using **STOMP protocol**  
- Responsive UI built with **Bootstrap** and **JavaScript**  
- Fallback support with **SockJS** for browsers without WebSocket support  
- User-friendly interface to set username and send messages  
- Scalable chat rooms with topic-based subscriptions  

## Technologies Used

- Java 17+  
- Spring Boot  
- Spring WebSocket & STOMP  
- Thymeleaf (server-side templating)  
- SockJS and STOMP.js (frontend WebSocket libraries)  
- Bootstrap 5 (UI styling)  
- Maven (build tool)  
- Lombok (boilerplate reduction)  

## How It Works

- The backend uses Spring Boot to configure WebSocket endpoints and message brokers.  
- Clients connect to the server via WebSocket (or SockJS fallback) and subscribe to chat topics.  
- When a user sends a message, it is routed through STOMP and broadcast to all subscribed clients in real time.  
- The frontend dynamically updates the chat window with incoming messages without page reloads.  

## Getting Started

1. Clone the repository:  
   ```bash
   git clone https://github.com/AbdulHakeem427/spring-boot-chat-app.git

Build and run the Spring Boot application:
bash
./mvnw spring-boot:run

Open your browser and navigate to:
http://localhost:8080/chat

Enter your name and start chatting in real time!

![Screenshot 2025-06-26 144854](https://github.com/user-attachments/assets/92265e5d-4099-4e9b-ae4b-a072fb08e288)


