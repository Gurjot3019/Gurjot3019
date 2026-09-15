# EX-7: Dockerizing a Flask Application

## Objective
Create a simple Python Flask web application, build a Docker image for it, and run the application inside a Docker container.

## Project Structure
- `app.py` - Flask application
- `requirements.txt` - Python dependency list
- `Dockerfile` - Instructions to build the Docker image

## Flask Application
The application runs on port 5000 and returns **Hello, Docker!** at the root URL.

## Docker Commands

Build the image:
```bash
docker build -t my-flask-app .
```

Run the container:
```bash
docker run -p 5000:5000 my-flask-app
```

Open in browser:
`http://localhost:5000`

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

## Result
The Flask application can be packaged as a Docker image and executed as a Docker container.
