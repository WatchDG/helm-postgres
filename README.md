# helm-postgres
helm postgres

# helm-influxdb

## render
```shell script
helm template helm-postgres > postgres.yml
```

## port-forward
```shell script
kubectl port-forward --namespace postgres svc/postgres 5432
```