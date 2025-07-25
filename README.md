# k8s-nginx-deployment

# NGINX Kubernetes Deployment

This project deploys a simple NGINX web server using Kubernetes. It includes:

- A Deployment with 2 replicas
- Liveness & readiness probes
- A ClusterIP Service

## How to Apply

```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
