# my-docker-app

This is a simple Docker application that prints "Hello, World!".

## Building the Docker Image

To build the Docker image, navigate to the directory containing the Dockerfile and run the following command:

```bash
docker build -t my-docker-app .
```

This command builds a Docker image using the Dockerfile in the current directory and tags the image as "my-docker-app".

## Running the Docker Container

To run the Docker container, use the following command:

```bash
docker run my-docker-app
```

This command runs a Docker container using the "my-docker-app" image. When the container runs, it executes the command specified in the Dockerfile, which prints "Hello, World!".