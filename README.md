# Vite + React + PNPM + Docker

This repository demonstrates how to Dockerize a Vite + React application using PNPM as the package manager. It includes a multi-stage Dockerfile for efficient builds and a lightweight production-ready setup.(~200mb image)

## Prerequisites

Before you begin, ensure you have the following installed:

  - Docker

  - Node.js

  - PNPM

--- 

## Getting Started

### 1. Clone the Repository

```
git clone https://github.com/nivethan-me/dockerized-react.git
cd dockerized-react
```

### 2. Build the Docker Image

```
docker build -t dockerized-react .
```

### 3. Run the Docker Container

```
docker run -p 5173:5173 dockerized-react
```
The app will be available at http://localhost:5173.


