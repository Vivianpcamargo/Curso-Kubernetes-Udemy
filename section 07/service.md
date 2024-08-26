# :bulb: Create
```
kubectl create -f service-definition.yml
```

# :mag: Get
```
kubectl get svc
```

```
kubectl explain svc | head -n3
```

```
kubectl describe svc
```

# :pencil: Update
```
kubectl apply -f service-definition.yml
```

```
kubectl edit service/myapp-service
```

# :wastebasket: Delete
```
kubectl delete services/myapp-services
```