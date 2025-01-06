# Container with docker

## Technologies used:

- Docker, Node.js, MongoDB, MongoExpress, Amazon ECR, Nexus, DigitalOcean, Linux

## Job name: Use Docker for local development
### Job description:

- Create Dockerfile for Nodejs application and build Docker image
- Run Nodejs application in Docker container and connect to
- MongoDB database container locally.
- Also run MongoExpress container as a UI of the MongoDB database.

## Job name: Docker Compose - Run multiple Docker containers
### Job description:

- Write Docker Compose file to run MongoDB and MongoExpress containers

## Job name: Docker Compose - Dockerize Nodejs application and push to private Docker registry
### Job description: 

- Write Dockerfile to build a Docker image for a Nodejs application
- Create private Docker registry on AWS (Amazon ECR)
- Push Docker image to this private repository

## Job name: Docker Compose - Deploy Docker application on a server with Docker Compose
### Job description:

- Copy Docker-compose file to remote server
- Login to private Docker registry on remote server to
- fetch the app image
- Start the application container with MongoDB and
- MongoExpress services using docker compose

## Job name: Docker Compose - Persist data with Docker Volumes
### Job description:

- Persist data of a MongoDB container by attaching a Docker volume to it

## Job name: Docker Compose - Create Docker repository on Nexus and push to it
### Job description:

- Create Docker hosted repository on Nexus
- Create Docker repository role on Nexus
- Configure Nexus, DigitalOcean Droplet and Docker to be able to push to Docker repository
- Build and Push Docker image to Docker repository on Nexus

## Job name: Docker Compose - Deploy Nexus as Docker container
### Job description:

- Create and Configure Droplet
- Set up and run Nexus as a Docker container
