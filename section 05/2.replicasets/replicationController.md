# :bulb: Create
```
kubectl create -f rc-definition.yml
```

```
kubectl create -f rc-definition.yml --record
```

# :mag: Get
```
kubectl get replicationcontroller
```

```
kubectl explain replicationcontroller | head -n3
```

```
kubectl describe replicationcontroller
```

# :pencil: Update
```
kubectl apply -f rc-definition.yml
```

```
kubectl edit replicationcontroller.apps/myapp-replicationcontroller
```

# :wastebasket: Delete
```
kubectl delete replicationcontroller/myapp-replicationcontroller
```