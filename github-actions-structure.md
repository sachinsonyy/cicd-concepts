# GitHub Actions Structure

## Workflow
A workflow is an automated process triggered by events like git push.

## Workflow Location
GitHub Actions workflows must be placed inside .github/workflows directory.

## Jobs
Jobs define a set of tasks to execute. Each job runs on a runner.

## Runner
A runner is a temporary virtual machine provided by GitHub to run jobs.

## Steps
Steps are individual tasks inside a job. They run sequentially.

## uses vs run
- uses: executes a prebuilt GitHub Action
- run: executes shell commands

## SSH Deployment
In my project, deployment is done by connecting to AWS EC2 via SSH
and running Docker commands remotely.
