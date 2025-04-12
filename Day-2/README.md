Containers, Docker & Dockerfile Basics

1. Container Concept:

A container is a lightweight runtime environment where apps run with all dependencies bundled.
Benefits: Portability, consistency, faster deployment.

2. Docker:

A tool to create and manage containers.
Dockerfile: A script that defines how to build a container image.

3. Dockerfile Instructions:

FROM: Base image.
COPY / ADD: Copy files from host to container.
RUN: Install dependencies.
.dockerignore: Ignore unnecessary files.
CMD vs ENTRYPOINT: Define default command to run.
EXPOSE: Define port number.
ENV: Set environment variables.
USER, WORKDIR: Set user and working directory.

4. Docker Commands:

docker build, docker run, docker ps, docker ps -a
-p: Port mapping (e.g., -p 8080:80)

Assignment:
Build a static web app using ChatGPT.
Write a Dockerfile.
Deploy using nginx.
