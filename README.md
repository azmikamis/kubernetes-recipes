# kubernetes-recipes
```
kubectl proxy
```
```
curl http://localhost:8001/api/v1/namespaces/$NAMESPACE/pods/$POD_NAME/proxy/
curl http://localhost:8001/api/v1/namespaces/$NAMESPACE/services/http:$SVC_NAME:/proxy/
```
