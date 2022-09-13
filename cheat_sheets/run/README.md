# `kubectl run` Commands

## Running a pod

```bash
kubectl run my-nginx --image nginx
```

## Running a pod in interactive mode

```bash
kubectl run tmp-shell --rm -it --image bretfisher/netshoot bash
```

## Run command in dry-run mode

```bash
kubectl run webserver --image nginx --dry-run=client -o yaml
```
