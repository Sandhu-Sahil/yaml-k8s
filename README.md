# Commands
```
kubectl apply -f nginx-deployment.yaml
```
```
kubectl get deployment
```
```
kubectl apply -f nginx-service.yaml
```
```
kubectl get service
```
```
kubectl get pod
```
```
get more information about pod
```
```
kubectl describe pod {pod-name}
```
```
kubectl get pod -o wide
```
```
kubectl describe service {service-name}
```

### debugging
get more information in yaml file
```
kubectl get deployment nginx-deployment -o yaml
```
save it in a yaml file:
```
kubectl get deployment nginx-deployment -o yaml > nginx-deployment-result.yaml
```
