# eks-api-gitops-demo
# eks-api-gitops-demo

Demo repository for Kubernetes GitOps deployment using **Argo CD**.

## What this demo shows
- `k8s/dev` → Argo CD **auto-sync** (dev deploys automatically after git commit)
- `k8s/prod` → Argo CD **manual sync** (production-style)

## Structure
k8s/
dev/
deployment.yaml
service.yaml
ingress.yaml
prod/
deployment.yaml
service.yaml
ingress.yaml


## Key idea
Git is the source of truth.  
You change Git → Argo CD syncs Kubernetes.
