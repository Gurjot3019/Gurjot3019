# EX-6 Docker Practical: Flask Application

## Objective
Create a simple Flask web application, containerize it using Docker, build a Docker image, run the container, and manage Docker images and containers.

## Project Files
- `app.py` — Flask application.
- `requirements.txt` — Flask dependency.
- `Dockerfile` — Instructions for building the Docker image.

## Local Commands
```bash
mkdir my-flask-app
cd my-flask-app
```

Create `app.py` and `requirements.txt` as provided in the practical, then create the `Dockerfile`.

Build the image:
```bash
docker build -t my-flask-app .
```

Run the container:
```bash
docker run -p 5000:5000 my-flask-app
```

Open:
`http://localhost:5000`

Expected output:
`Hello, Docker!`

## Docker Management Commands
List images:
```bash
docker images
```

List running containers:
```bash
docker ps
```

Stop a container:
```bash
docker stop <container-id>
```

Remove a stopped container:
```bash
docker rm <container-id>
```

Remove the image:
```bash
docker rmi my-flask-app
```
