# `kubectl get` Commands

## List all objects

```bash
kubectl get all
```

## List all pods / replicasets / deployments / services / nodes / secrets and watch it live

```bash
kubectl get nodes / pods / replicasets / deployments / services / secrets -w
```

NOTE: `--show-labels` to include labels in the output

## Get secrets

```bash
kubectl get secret firstsecret -o yaml
echo <encoded_secret> | base64 -d
```
