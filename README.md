# Kubernetes Helm charts by @highwind
[![Release Charts](https://github.com/highwind/helm-charts/actions/workflows/release.yml/badge.svg)](https://github.com/highwind/helm-charts/actions/workflows/release.yml)
[![pages-build-deployment](https://github.com/highwind/helm-charts/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/highwind/helm-charts/actions/workflows/pages/pages-build-deployment)

This is a Helm charts repository for Kubernetes by @highwind.

### Add Helm repository

To install the [highwind](https://highwind.nl) repo run:

```bash
helm repo add highwind https://highwind.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
highwind` to see the charts.
