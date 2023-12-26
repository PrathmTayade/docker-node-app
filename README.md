# My Dockerized Node.js App

A simple Node.js app built with Docker.

## Getting Started
To run the app locally:

1. Build the Docker image:

```bash 
docker build -t dockernodeapp .

```


2. Run the Docker container:
```bash
docker run -d -p 3000:3000 dockernodeapp
```

3. Access the app locally:The app will now be running on port 3000 of your Docker host machine. Open http://localhost:3000 in your browser to see it running.

4. Stop the container:

```bash 
docker stop dockernodeapp
```