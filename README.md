# kuber_lesson_2

### 1. Docker with autobild
```
docker login -u
docker tag yeasy/simple-web likemaydev/kuber-lesson-2:latest
docker push likemaydev/kuber-lesson-2:latest
```
### 2. Kubernetes cluster with LoadBalancer svc
```
kubectl apply -f deploy.yml
```
