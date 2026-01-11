# Cost Awareness in CI/CD

## Why cost matters
CI/CD pipelines and cloud resources can generate cost if
not managed properly.

## Cost sources in my setup
- EC2 instance runtime
- CI/CD pipeline executions
- Docker resource usage

## Cost optimization steps
- Limited pipeline triggers to main branch
- Stopped EC2 instance when not in use
- Removed unused Docker containers

## Monitoring cost
I use AWS Cost Explorer to monitor usage and avoid waste.
