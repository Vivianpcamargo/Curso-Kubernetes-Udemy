export KUBE_EDITOR="nano"

# Create
kubectl create -f deployments.yml
kubectl create -f deployments.yml --record

# Get
kubectl get deployments
kubectl explain deployments | head -n3
kubectl describe deployments

# Update
kubectl apply -f deployment.yml
kubectl set image deployment myapp-deployment nginx=nginx:1.18-perl
kubectl edit deployment.apps/frontend

# Status
kubectl rollout status deployment/myapp-deployment
kubectl rollout history deployment/myapp-deployment

# Rollback
kubectl rollout undo deployment/myapp-deployment