# `kubectl explain` Commands

## Listing keys and values available for yaml template for a particular service

```bash
kubectl explain service / deployment / pod --recursive
```

## Lising keys and values but with also some explanations

```bash
kubectl explain service
```

## Explanation about a particular section

```bash
kubectl explain service.spec.type
```
