# :arrows_clockwise: Replace
```
kubectl replace -f replicaset.yml
```

# :arrow_up: Scale
```
kubectl scale --replicas=6 -f replicaset.yml
```

```
kubectl scale replicaset myapp-replicaset --replicas=2
```