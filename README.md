
 
---

# (WIP) Live Streaming and Streaming Key Manager

This is a live streaming manager application that handles authentication for video ingestion. The project is currently a **Work in Progress (WIP)** and is actively under development.

## Features
- **Live Streaming Management**: Manage live stream ingestion and streaming keys.
- **Authentication**: Secure authentication for stream ingestion.

## Requirements

Before running the project, ensure you have the following:

- **Basic knowledge of containers** (Docker, Docker Compose).
- **Basic understanding of NGINX**.
- **Basic knowledge of the Go programming language**.

## Getting Started

To get started with the project, follow these steps:

### 1. Clone the repository:

```bash
git clone https://github.com/thalisonsilva/streaming-key-server
cd live-streaming-manager
```

### 2. Build and start the application using Docker Compose:

Make sure you have [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/) installed.

```bash
docker-compose up
```

This command will build and start the necessary containers, launching the live streaming manager along with all of its components.

### 3. Access the application:

Once the containers are up and running, you can access the application by navigating to `http://localhost:<port>` (default port may vary depending on your Docker Compose configuration).

