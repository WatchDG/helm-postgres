# helm-postgres
helm postgres

# helm-influxdb

## install
```shell script
helm install postgres helm-postgres --atomic --wait --set storage=100Gi
```

## render
```shell script
helm template helm-postgres > postgres.yml
```

## port-forward
```shell script
kubectl port-forward --namespace postgres svc/postgres 5432
```