```
kubectl create deploy nginx-test --image nginx

```
```
kubectl get all
```
```
kubectl expose deploy nginx-test --port 80 --type NodePort
```