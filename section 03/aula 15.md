minikube start --driver=docker

minikube status

kubectl get nodes

kubectl create deployment hello-minikube --image=kicbase/echo-server:1.0

kubectl get deployments

kubectl expose deployment hello-minikube --type=NodePort --port=8080

minikube service hello-minikube --url

kubectl delete services hello-minikube

kubectl delete deployment hello-minikube

kubectl get pods