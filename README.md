# Java Matchmaker

A lightweight Client-Server matchmaking system built using pure Java TCP sockets. 

## Project Purpose
This project is not meant to be a production-ready application. It is a dedicated sandbox built from scratch to practice and understand:
* **Core Java:** Structuring a real application without heavy frameworks.
* **Networking:** Low-level TCP socket communication, data streams, and raw client-server architecture.
* **Multithreading:** Handling concurrent users, thread-safe data queues, and preventing race conditions.
* **Version Control:** Proper Git workflow, project structuring, and repository management.

## Architecture
* **Server:** A multithreaded hub that listens for incoming connections, maintains a thread-safe queue of players, and pairs them based on a simple ELO system.
* **Client:** A lightweight console application that connects to the server, requests a match, and alerts the user when an opponent is found.