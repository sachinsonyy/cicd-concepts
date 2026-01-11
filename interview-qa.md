# CI/CD Interview Questions & Answers

## What is CI/CD?
CI/CD automates build and deployment to reduce manual errors.

## Which tool did you use?
GitHub Actions.

## Explain your pipeline
Triggered on push, builds Docker image, deploys to EC2 via SSH.

## What if pipeline fails?
Check GitHub Actions logs, then Docker and system logs.

## How are secrets managed?
Using GitHub Secrets.
