# geth-helm

A helm chart to run a geth ethereum node on kubernetes.

## tl;dr

Add the chart repo:

```bash
helm repo add geth https://holzeis.github.io/geth-chart
helm install geth geth/geth -f values.yaml # create your own values.yaml
```