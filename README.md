# Oumuamua Homelab

## Headlamp

**URL:** https://k8s.o5s.lol

### Retrieve auth token

```bash
kubectl get secret headlamp-admin-token \
    -n headlamp \
    -o jsonpath='{.data.token}' | base64 --decode
```

## Apps
- Zotero
