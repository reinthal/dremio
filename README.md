# Dremio Helm Chart

This is the helm chart located here https://github.com/dremio/dremio-cloud-tools/tree/master/charts/dremio_v2 packages as helm chart for easy use with fluxcd kubernetes controllers.

## How to use this helm chart?

```bash

helm repo add dremio https://reinthal.github.io/dremio

helm repo update

helm search repo dremio
```

Now you can install the helm chart

```bash

helm install dremio/dremio_v2
```
