# Wallarm Public Charts

Follow the steps below to start deploying any of them in your Kubernetes cluster:

```bash
helm repo add wallarm https://charts.wallarm.com
helm search repo wallarm # -l --devel
helm install my-release wallarm/chart-name
```
