kubectl replace -f replicaset.yml

kubectl scale --replicas=6 -f replicaset.yml

kubectl scale replicaset myapp-replicaset --replicas=2