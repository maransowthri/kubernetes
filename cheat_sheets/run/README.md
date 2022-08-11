# `kubectl run` Commands

## Running a pod

```bash
kubectl run my-nginx --image nginx
```

## Running a pod in interactive mode

```bash
kubectl run tmp-shell --rm -it --image bretfisher/netshoot bash
```
