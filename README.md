# Dockerized Go Application

This is a simple Go web server that responds with "Hello from Dockerized Go App!".

## Run Locally
To build and run the app locally using Docker:

```bash
docker build -t go-docker-app .
docker run -p 8080:8080 go-docker-app
