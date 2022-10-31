# `kubectl auth` Commands

## Check the permission without making any real actions

```bash
kubectl auth can-i create deploy
```

## Check the permission as different user

```bash
kubectl auth can-i create pods --as dev-user
```

NOTE: use `--namespace` option to specify namespace
