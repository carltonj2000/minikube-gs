# What is Minikube

Notes for the
[What is minikube](https://youtu.be/uo82-n1gMcI)
video.

```
minikube start/stop
kubectl delete deployment hello-minikube
kubectl create deployment hello-minikube --image=docker.io/nginx:1.23
kubectl delete service hello-minikube
kubectl expose deployment hello-minikube --type=NodePort --port=80
kubectl port-forward service/hello-minikube 7080:80 &

minikube delete --all --purge # remove everything minikube put on your system
minikube delete --all # remove all minikube deployments
```
