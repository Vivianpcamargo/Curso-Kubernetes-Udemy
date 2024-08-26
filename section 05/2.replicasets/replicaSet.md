# :bulb: Create
```
kubectl create -f replicaset.yml
```

# :mag: Get
```
kubectl get replicaset
```

```
kubectl explain replicaset | head -n3
```

```
kubectl describe replicaset
```

# :pencil: Update
```
kubectl apply -f replicaset.yml
```

```
kubectl edit replicaset.apps/myapp-replicaset
```

# :wastebasket: Delete
```
kubectl delete replicaset/myapp-replicaset
```