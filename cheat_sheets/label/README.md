# `kubectl label` Commands

## Adding a new label to a running object

```bash
kubectl label <object_type> <object_name> <labels>

E.g

kubectl label pod webserver env=dev
```

## Removing a label from a running object

```bash
kubectl label pod webserver env-
```

## Adding a new label to all running objects

```bash
kubectl label pods --all status=running
```
