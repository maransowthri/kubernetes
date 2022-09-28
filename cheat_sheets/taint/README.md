# `kubectl taint` Commands

## Tainting a node - Marking it as unavailable

```bash
kubectl taint nodes node3 key=value:NoSchedule
```

NOTE: You would need to use a special pass (toleration) to make use tainted nodes
