Docker Images, Hub, and Challenges with Containers

1. Docker Image:

A template that contains the app, dependencies, and configurations.
Created using a Dockerfile.
Run containers from it using docker run.

2. Docker Hub:

A cloud registry for storing and sharing Docker images.
Push/pull images using docker push / docker pull.

3. Problems with Standalone Containers:

No auto-scaling.
No load balancing.
No self-healing if container crashes.
Downtime risk, no persistence.

4. Need for Orchestration Tools:

Containers can't manage large-scale deployments alone.

Solution: Kubernetes.
