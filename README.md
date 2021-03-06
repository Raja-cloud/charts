# HAProxy Ingress Charts

This is the home of HAProxy Ingress Charts for [Helm](https://helm.sh) package manager.

[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/haproxy-ingress)](https://artifacthub.io/packages/search?repo=haproxy-ingress)

Add HAProxy Ingress as a new repository:

```console
$ helm repo add haproxy-ingress https://haproxy-ingress.github.io/charts
```

List current charts:

```console
## Latest version
$ helm search repo haproxy-ingress

## All stable versions
$ helm search repo haproxy-ingress -l

## All stable and non stable versions
$ helm search repo haproxy-ingress -l --devel
```

See installation options in the chart directory:

* [HAProxy Ingress](/haproxy-ingress)
