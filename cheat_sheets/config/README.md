# `kubectl config` Commands

## Display the current-context

```bash
kubectl config current-context
```

## Switching to different namespace (making it as a default)

```bash
kubectl config set-context $(kubectl config current-context) --namespace=dev
```

## Connecting to a service from a different namespaces

```bash
mysql.connect("db-service") # to connect to db-service in the default namespace
mysql.connect("db-service.dev.svc.cluster.local") # to connect to service in the dev namespace
```
