This repository contains Kubernetes manifests for the IoT project Part 3.

## Application
- Using wil42/playground application
- Current version: v1
- Port: 8888

## To change version
Edit `manifests/deployment.yaml` and change:
```yaml
image: wil42/playground:v1  # Change to v2
```
