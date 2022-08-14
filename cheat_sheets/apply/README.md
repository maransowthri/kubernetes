# `kubectl apply` Commands

## Creating / Updating resources in a file

```bash
kubectl apply -f myfile.yaml
```

## Creating / Updating resources under a whole directory

```bash
kubectl apply -f myyaml/
```

## Creating / Updating resources from a URL

```bash
kubectl apply -f https://maransowthri.dev/pod.yaml
```

## Dry run

```bash
kubectl apply -f app.yaml --dry-run=server
```
