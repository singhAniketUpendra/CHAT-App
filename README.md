# Real-Time Chat Application

A full-stack **real-time chat application** built using **Spring Boot** and **WebSocket** technology.  
This project enables instant communication between users with live message delivery, making the chatting experience smooth, fast, and interactive.

---

## Overview

This application is designed to provide real-time messaging functionality where multiple users can connect and exchange messages instantly without refreshing the page. It uses **Spring Boot** on the backend and **WebSocket** for bidirectional communication between client and server.

The main goal of this project is to demonstrate how real-time applications can be developed using modern Java backend technologies.

---

## Features

- Real-time messaging using **WebSocket**
- Instant message delivery without page refresh
- User-friendly chat interface
- Multiple users can join and chat simultaneously
- Fast and lightweight communication
- Built using **Spring Boot**
- Easy to understand project structure
- Scalable foundation for advanced chat features

---

## Tech Stack

### Back-End
- Java
- Spring Boot
- Spring WebSocket
- Maven

### Front-End
- HTML
- CSS
- JavaScript

---

## How It Works

This chat application uses **WebSocket protocol** to establish a persistent connection between the client and server.  
Unlike traditional HTTP requests, WebSocket allows two-way communication, which means:

- The client can send messages to the server
- The server can instantly push messages to all connected clients
- Messages appear in real time without reloading the page

This makes WebSocket ideal for applications like chat systems, notifications, multiplayer games, and live dashboards.

---

## Project Structure

```bash
src
 ┣ main
 ┃ ┣ java
 ┃ ┃ ┗ com.example.chat
 ┃ ┃   ┣ config
 ┃ ┃   ┣ controller
 ┃ ┃   ┣ model
 ┃ ┃   ┣ service
 ┃ ┃   ┗ ChatApplication.java
 ┃ ┗ resources
 ┃   ┣ static
 ┃   ┣ templates
 ┃   ┗ application.properties
