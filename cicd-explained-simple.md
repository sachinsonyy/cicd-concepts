# CI/CD Explained Simply

## CI/CD for non-technical audience
CI/CD is an automation process that reduces manual deployment
and improves reliability.

## CI/CD in my project
In my project, CI/CD automatically builds and deploys a Dockerized
application to AWS EC2 on every code push.

## Technical overview
The pipeline is triggered on push, runs on GitHub Actions,
builds Docker images, and deploys to EC2 over SSH using secrets.
