# `kubectl expose` Commands

## Creating a service aka exposing a port in a deployment

```bash
kubectl expose deployment httpenv --port 8888
```

## Exposing a node port

```bash
kubectl expose deployment httpenv --port 8888 --name httpenv-np --type NodePort
```

## Exposing a Load Balancer

```bash
kubectl expose deployment httpenv --port 8888 --name httpenv-lb --type LoadBalancer
```
