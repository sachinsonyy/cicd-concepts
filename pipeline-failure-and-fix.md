# CI/CD Pipeline Failure and Fix

## What went wrong
The pipeline failed during the Docker build step because
an incorrect base image name was used in the Dockerfile.

## How I identified the issue
I checked GitHub Actions logs and found an error indicating
that the Docker image could not be pulled.

## How I fixed it
I corrected the Dockerfile to use a valid base image name
and pushed the changes again.

## Outcome
The pipeline ran successfully and the application was
deployed automatically.
