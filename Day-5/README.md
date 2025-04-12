Kubernetes Resources & Services

1. Namespaces:

Logical partitions of a cluster.
Default namespaces: default, kube-system, kube-public, kube-node-lease

2. Pods & ReplicaSets:

Pod: Smallest deployable unit. Runs one or more containers.

ReplicaSet: Maintains desired number of pod replicas.

3. Deployments:

Manage ReplicaSets.
Allow rollouts, rollbacks.

4. Services:

Expose applications:

ClusterIP: Internal access only.

NodePort: Exposes on each Node’s IP at a static port.

LoadBalancer: Exposes using a cloud load balancer.

5. Volumes:

Persist data across pod restarts.
