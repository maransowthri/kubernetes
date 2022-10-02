# `kubectl rollout` Commands

## List revisions associated with a deployment

```bash
kubectl rollout history deployment.v1.apps/webserver-deployment
```

## Get info about a specific revision

```bash
kubectl rollout history deployment.v1.apps/webserver-deployment --revision 2
```

## Check rollout status

```bash
kubectl rollout status deployment webserver
```

## Rollback last deployment

```bash
kubectl rollout undo deployment webserver
```
