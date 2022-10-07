# `kubectl get` Commands

## List all objects

```bash
kubectl get all
```

## List all pods / replicasets / deployments / services / nodes / secrets / configmaps and watch it live

```bash
kubectl get nodes / pods / replicasets / deployments / services / secrets / configmaps -w
```

NOTE: `--show-labels` to include labels in the output

## Get secrets

```bash
kubectl get secret firstsecret -o yaml
echo <encoded_secret> | base64 -d
```

## Get pods with IPs and node names

```bash
kubectl get pods -o wide
```

## Get pods in a different name space

```bash
kubectl get pods --namespace dev

(Or)

kubectl get pods -n dev
```

## Listing pods in all namespaces

```bash
kubectl get pods --all-namespaces

(Or)

kubectl get pods -A
```
