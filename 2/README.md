kubectl apply -f postgres-pv.yaml
kubectl apply -f redis-pv.yaml
kubectl apply -f postgres-config.yaml
kubectl apply -f postgres-deployment.yaml
kubectl apply -f redis-deployment.yaml
kubectl apply -f cvat-deployment.yaml
