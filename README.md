# Temperature Converter

## Sobre o projeto:
- O projeto é um laboratório Docker e Kubernetes.
- O objetivo é a criar um ambiente com containers para suportar uma aplicação de Node.js.

## Sobre a aplicação:
- A aplicação é um convertedor de temperatura.
- O objetivo é converte uma temperatura em escala Fahrenheit(°F) para Celcius(ºC) ou vice-versa.
- A aplicação é construída em Node.js. 


## Pré-requisitos:

- Docker
- K3d

## Como utilizar:

### Executando o K8S
```sh
kubectl apply -f k8s/deployment.yaml
```

### Comandos úteis:
```sh
# Exibindo o status do deploy
kubectl get deploy

# Exibindo o status do replicaset
kubectl get replicaset

# Exibindo o status dos Pods
kubectl get pod

# Exibindo todos os status
kubectl get all

```
