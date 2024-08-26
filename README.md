# :bookmark: Curso-Kubernetes-Beginners-Udemy 

<br> :classical_building: Software: Kubernetes
<br> :luggage: Banco de Dados: Postgres e Redis
<br> :page_facing_up: Padronização: YAML

## :dart: Sobre

Curso de Kubernetes para iniciates com exemplos de comandos node, pod, replicaSet, replicationController, scale, deployment e service.

## :building_construction: Instalação do projeto

### :classical_building: Rodar o Docker

- Para criar e iniciar o Kubernetes:
```
minikube start --driver=docker
```

- Para verificar o status do Kubernetes:
```
minikube status
```

## :bar_chart: Rodando

### :test_tube: Exemplos de uso

- Acessar a url do service:
```
minikube service app-service --url
```

- Mudar o padrão do edit:
```
export KUBE_EDITOR="nano"
```

- Acessar tudo que está rodando no node:
```
kubectl get all
```

- Acessar nodes que estão rodando:
```
kubectl get nodes
```

## :door: Portas do Projeto

#### :label: Redis

http://localhost:6379

#### :label: Postgres

http://localhost:5432

#### :label: Voting

http://localhost:30004

#### :label: Result

http://localhost:30005
