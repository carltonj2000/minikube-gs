# Local development using minikube

The contents below are based of the
[Local development using minikube](https://youtu.be/_1uWY1GdDVY)
video.

```base
minikube docker-env
minikube -p minikube docker-env | source # point to minikube's docker deamon
docker build -t local/modex1:v1 .
kubeclt apply -f k8s.yaml
minikube service local-modex1-svc
```
