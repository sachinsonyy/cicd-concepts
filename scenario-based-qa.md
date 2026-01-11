# Scenario-Based CI/CD Questions

## Website is down
Check EC2 status, Docker container, logs, and restart if needed.

## Pipeline passed but app not working
Check Docker logs, container ports, and application startup.

## Pipeline failed after push
Check GitHub Actions logs to identify failed step and fix accordingly.

## Deployment failed at night
Restore service first, then analyze root cause.

## SSH failure in pipeline
Verify SSH keys, EC2 accessibility, and secrets configuration.
