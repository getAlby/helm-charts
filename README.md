![Logo](logo.png)
# Flitz Technologies [Helm](https://helm.sh) Charts

This respoitory contains [Helm](https://helm.sh) charts for the following projects:

* [LNDHub](charts/lndhub)
* [LND](charts/lnd) (based on [Fold's chart](https://github.com/fold-team/helm-charts/tree/master/charts/lnd))
* [C-Lightning](charts/c-lightning)
* [Eclair](charts/eclair)
* [Bitcoind](charts/bitcoind)
* [Nginx](charts/nginx-ingress)
* [Grafana-agent CRD's](charts/grafana-agent-resources)
* [Cert-manager](charts/cert-manager)
* [Redis](charts/redis)
* [Postgres](charts/postgresql)
* [Clickhouse](charts/clickhouse)
* [Plausible](charts/plausible-analytics)
* [Superset](charts/superset)


```
helm repo add getalby https://getalby.github.io/helm-charts/
helm install lnd getalby/lnd
```
