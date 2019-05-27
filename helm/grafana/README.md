# Grafana

To install or upgrade grafana:

```
helm upgrade --install bdf-grafana stable/grafana -f helm/grafana/config.yml --namespace bdf --tiller-namespace tiller
```

## Config

* LoadBalancer service enabled.
Expose the grafana service to be accessed from outside the cluster.
* Persistant: 10Gi
* Default user/password: admin/password