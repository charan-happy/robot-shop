# Install EKS

Please follow the prerequisites doc before this.

## Install using Fargate

```
eksctl create cluster --name demo-cluster-three-tier --region us-east-2
```

## Delete the cluster

```
eksctl delete cluster --name demo-cluster-three-tier --region us-east-2
```