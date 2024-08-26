# :bulb: Create
```
kubectl create -f deployments.yml
```

```
kubectl create -f deployments.yml --record
```

```
kubectl create deployment hello-minikube --image=kicbase/echo-server:1.0
```

```
kubectl expose deployment hello-minikube --type=NodePort --port=8080
```

# :mag: Get
```
kubectl get deployments
```

```
kubectl explain deployments | head -n3
```

```
kubectl describe deployments
```

# :pencil: Update
```
kubectl apply -f deployment.yml
```

```
kubectl set image deployment myapp-deployment nginx=nginx:1.18-perl
```

```
kubectl edit deployment.apps/myapp-deployment
```

# :bar_chart: Status
```
kubectl rollout status deployment/myapp-deployment
```

```
kubectl rollout history deployment/myapp-deployment
```

# :arrows_counterclockwise: Restart
```
kubectl rollout restart deployment/myapp-deployment
```

# :back: Rollback
```
kubectl rollout undo deployment/myapp-deployment
```

# :wastebasket: Delete
```
kubectl delete deployment/myapp-deployment
```