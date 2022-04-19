# Kubernetes Helm charts by @highwind

This is a Helm charts repository for Kubernetes by @highwind.

### Add Helm repository

To install the [highwind](https://highwind.nl) repo run:

```bash
helm repo add highwind https://highwind.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
highwind` to see the charts.
