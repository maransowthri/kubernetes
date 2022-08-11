# `kubectl logs` Commands

## Getting the logs of the deployment

```bash
kubectl logs deploy/my-apache --follow --tail 1
```

## Getting the logs of all pods based on the label

```bash
kubectl logs -l app=my-apache
```
