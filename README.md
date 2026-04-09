# Docker Lab: Containerizing a Three-Tier Application
**INET 4031 - Introductions to Systems**

This lab demonstrates how to containerize a three-tier application using Docker and Docker Compose. The application uses three services: Apache, Flask, and MariaDB. Each service runs in its own container, and Docker Compose is used to connect and manage them as one complete stack.

## Project Overview

This project is a ticket dashboard application. Apache serves the web frontend, Flask handles the backend logic and API, and MariaDB stores the ticket data. The goal of the lab was to complete the Dockerfiles, bring the stack up correctly, and verify that all services work together.

A user interacts with the application through a web browser. Apache receives the request, forwards it to Flask when needed, and Flask communicates with MariaDB to get the data.

## Prerequisites

Before running this lab, the following must be installed on the VM:

- Docker
- Docker Compose
- Git

A `.env` file must also be created from `.env.example` before starting the stack.

## Getting Started

Clone the repository and move into the project folder:

```bash
git clone https://github.com/Abdirisak323/inet4031-lab12.git
cd inet4031-lab12
