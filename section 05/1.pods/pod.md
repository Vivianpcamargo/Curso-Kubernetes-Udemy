# :bulb: Create
```
kubectl create -f pod.yml
```

```
kubectl create -f pod.yml --record
```

```
kubectl run nginx --image=nginx
```

# :mag: Get
```
kubectl get pods
```

```
kubectl get pods -o wide
```

```
kubectl explain pod | head -n3
```

```
kubectl describe pod nginx
```

# :pencil: Update
```
kubectl apply -f pod.yml
```

```
kubectl edit pod/myapp-pod
```

# :wastebasket: Delete
```
kubectl delete pod/myapp-pod
```