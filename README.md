# AIRFLOW KUBERNETES

## Install kind cluster node

```sh
kind create cluster --name airflow-cluster --config kind-cluster.yaml

## check create sussesfull
kind get clusters
kubectl cluster-info --context kind-airflow-cluster
```