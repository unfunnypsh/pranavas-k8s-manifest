Monitoring with Prometheus & Grafana, Clean-up Tools

1. Monitoring in Kubernetes:

Essential to observe performance, resource usage, health.

2. Prometheus:

A time-series database and monitoring system.
Collects metrics (CPU, memory, uptime, etc.)
Deploy as a pod or service in cluster.

3. Grafana:

Visualization tool to display Prometheus metrics.
Dashboards with graphs, pie charts.

4. Setup Overview:

Deploy Prometheus + Grafana in Kubernetes.
Connect Prometheus as a data source to Grafana.

5. Configuration Management:

Use Ansible to automate EC2, app deployments.

6. Cluster Deletion Command (cleanup):

eksctl delete cluster --name <cluster-name>
