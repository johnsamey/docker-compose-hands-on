# Getting Started with Docker Compose: Hands-On Project Experience

Welcome to the Docker Compose tutorial! This project demonstrates the fundamental concepts and hands-on experience with Docker Compose, helping you build and manage multi-container Docker applications efficiently.

## Overview

This tutorial will guide you through setting up a multi-container Docker application using Docker Compose. You will learn how to define services, networks, and volumes in a `docker-compose.yml` file and run your application using simple commands.

## Prerequisites

- **Docker**: Make sure Docker is installed and running on your machine. You can download it from [Docker’s official website](https://www.docker.com/products/docker-desktop).
- **Docker Compose**: Docker Compose is included with Docker Desktop. For Linux, you might need to install it separately. Follow the [installation instructions](https://docs.docker.com/compose/install/).

## Project Structure

docker-compose-tutorial/
.
├── api                     
│   ├── index.php
│   ├── app
│       ├── config.php
│       ├── Database.php
│       ├── todos.php
├── db                      
│   ├── dump.sql            
├── frontend               
│   ├── index.html          
├── docker-compose.yml
└── Dockerfile


## Getting Started

### Clone the Repository

```bash
git clone https://github.com/yourusername/docker-compose-tutorial.git
cd docker-compose-tutorial
```

## Review the Docker Compose File
### Open docker-compose.yml to see how the services, networks, and volumes are defined.

## Build and Run the Application
### Use Docker Compose to build and run the application.

## Commands Used
- Build and Run the Application:
```bash
docker compose up --build
```

- Stop and Remove Containers:
```bash
docker compose down
```