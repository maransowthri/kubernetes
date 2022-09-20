# `kubectl create` Commands

## Creating a deployment

```bash
kubectl create deployment nginx --image nginx
```

## Checking the command status and the output without creating real resources

```bash
kubectl create deployment sample --image nginx --dry-run=client
```

NOTE:

- We could use `--dry-run` for all other actions like creating service / jobs etc.
- There's an exception here. If we try to dry run `expose` it will need real deployment to exist

## Creating deployment in dry run mode and saving the spec in yaml format

```bash
kubectl create deployment sample --image nginx --dry-run=client -o yaml > pod.yaml
```

## Creating secrets

```bash
kubectl create secret generic firstsecret --from-literal=dbpass=mypassword
kubectl create secret generic secondsecret --from-file=./credentials.txt
```

## Creating configmaps

```bash
kubectl create configmap dev --from-literal app.mem=2048m
```
