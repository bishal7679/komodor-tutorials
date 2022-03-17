# Komodor Failure Scenarios

## How it works

Clone the repo, kubectl apply -f any of the demos to see them in action.

All services are prefixed with "komodor" so they're easy to spot and search for if ever using in a customer environment/training

## Currently supported

- Image Pull backoff
    - imagepullbackoff.yaml
- Out of Memory
    - oom.yaml
- Crash Loop BackOff
    - crashloopbackoff.yaml
- Create Container Config Error
    - createcontainerconfigerror.yaml

## Demo/Training deployments

### Beginner

- Step 1: Create basic deployment
- Step 2: Add Komodor service link annotations
- Step 3: Add Komodor deployment link annotations
- Step 4: Add an additional container on a different port
- Step 5: Change the second container to create an error

### Intermediate

- Coming soon

### Advanced

- Coming soon

## Future supported scenarios

- Playbook scenarios
- Integration scenarios
    - Sentry
    - Slack
    - Datadog
    - Grafana
    - PagerDuty