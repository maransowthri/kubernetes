# `kubectl rollout` Commands

## List revisions associated with a deployment

```bash
kubectl rollout history deployment.v1.apps/webserver-deployment
```

## Get info about a specific revision

```bash
kubectl rollout history deployment.v1.apps/webserver-deployment --revision 2
```
