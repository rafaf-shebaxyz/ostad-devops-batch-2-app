### How to install prometheus on k8s

```shell
kubectl create namespace prometheus
kubectl apply -f prometheus-config.yaml -n prometheus
kubectl apply -f prometheus-deployment.yaml -n prometheus
kubectl apply -f prometheus-service.yaml -n prometheus
```