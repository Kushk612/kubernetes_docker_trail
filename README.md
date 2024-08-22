minikube start
minikube status
kubectl get node -o wide 
kubectl get pod

kubectl apply -f secret.yaml
kubectl apply -f mongo-config.yaml
kubectl apply -f mongo-app.yaml
kubectl apply -f web-app.yaml

kubectl get pod
kubectl get configmap
kubectl get secret
kubectl get svc

minikube ip

minikube service webapp-service

kubectl delete deployment --all
kubectl delete secret --all
kubectl delete configmap --all
