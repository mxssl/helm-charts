# selectel-billing-exporter

```sh
# add repo
helm repo add mxssl https://mxssl.github.io/helm-charts

# install / upgrade
helm upgrade \
  --install selectel-billing-exporter \
  --create-namespace \
  --namespace selectel-billing-exporter \
  --set token="" \
  --version 1.0.3 \
  mxssl/selectel-billing-exporter
```
