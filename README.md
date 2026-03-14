# Simple Flask Web App

This is a minimal Flask web application, containerized with Docker.

## Build and Run with Docker

1. Build the Docker image:
   ```sh
   docker build -t <your-dockerhub-username>/flask-hello-world .
   ```
2. Run the container:
   ```sh
   docker run -p 5000:5000 <your-dockerhub-username>/flask-hello-world
   ```

Replace `<your-dockerhub-username>` with your Docker Hub username.
