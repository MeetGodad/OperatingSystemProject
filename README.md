# Docker Challenges Project

This repository contains my solutions for the Docker challenges as part of the course assignment.


## Challenge 1: Static Website

In this challenge, I created a Docker container to host a static website using NGINX. The main steps included:

1. Creating a Dockerfile to build the NGINX image with the static content.
2. Setting up a docker-compose.yml file to manage the container.
3. Configuring NGINX to serve the static files.
4. Testing the setup to ensure the website is accessible.

Detailed steps and code can be found in the `challenge1` directory.

## Challenge 2: NodeJS Application

For this challenge, I containerized a NodeJS application and set up NGINX as a reverse proxy. The key steps were:

1. Creating a Dockerfile for the NodeJS application.
2. Setting up a docker-compose.yml file to manage both the NodeJS and NGINX containers.
3. Configuring NGINX as a reverse proxy to forward requests to the NodeJS application.
4. Testing the setup to ensure the API endpoints are accessible through NGINX.

Detailed steps and code can be found in the `challenge2` directory.

## Reflections and Learnings

Throughout these challenges, I gained valuable experience in:

- Containerizing applications using Docker
- Using Docker Compose for multi-container applications
- Configuring NGINX for both static file serving and as a reverse proxy
- Troubleshooting container networking issues
- Best practices for Dockerfile creation and Docker Compose configuration

These skills will be invaluable for future projects involving containerized applications and microservices architectures.

## References

- [Docker Documentation](https://docs.docker.com/)
- [NGINX Documentation](https://nginx.org/en/docs/)
- [Node.js Documentation](https://nodejs.org/en/docs/)
