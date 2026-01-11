# Docker in CI/CD

## Why Docker is used
Docker ensures consistent application environments across
development, CI pipelines, and production servers.

## What happens during docker build
Docker reads the Dockerfile, pulls the base image, executes
instructions layer by layer, and creates an image.

## Image vs Container
- Image: blueprint created during build
- Container: running instance of an image

## Docker in my CI/CD pipeline
In my pipeline, Docker is used to build the application image
and deploy it to AWS EC2 by running containers automatically.
