# Coolbernetes

My development stuff in Kubernetes.

## Environment
A Kubernetes cluster running in a Docker Desktop for Mac, version 4.4.2.

## Common Setup
```bash
$ make common.setup
```

## Apps Setup
```bash
$ make apps.setup
```

## Monitoring Setup
```bash
$ make monitoring.setup
```

### Prometheus
```bash
$ make monitoring.prometheus
$ open localhost:9090
```

### Grafana
```bash
$ make monitoring.grafana
$ open localhost:3000 (Login: admin | admin)
```

### Destroy
```bash
$ make monitoring.destroy
```
