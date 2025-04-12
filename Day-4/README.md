Kubernetes Basics & AWS EKS (Elastic Kubernetes Service)

1. Kubernetes:

An open-source container orchestration platform.
Manages deployment, scaling, and availability of containers.

2. Key Features:

Orchestration

Auto-scaling

Load balancing

Self-healing

3. Kubernetes on AWS (EKS):

AWS-managed Kubernetes cluster.
You manage the containers, AWS manages the infra.

4. Kubernetes Architecture:

Cluster: Master Node + Worker Nodes

Master Node:

API Server
,etcd (key-value store)
,Scheduler
,Controller Manager

Worker Node:

Kubelet,
Kube-proxy, 
Container runtime (e.g., Docker)

5. Cluster Setup:

Use tools: eksctl, kubectl, AWS CLI

Command: aws eks update-kubeconfig --name <cluster-name> --region <region>


