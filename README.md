# kubernetes-recipes
```
kubectl proxy
```
```
curl http://localhost:8001/api/v1/namespaces/$NAMESPACE/pods/$POD_NAME/proxy/
curl http://localhost:8001/api/v1/namespaces/$NAMESPACE/services/http:$SVC_NAME:/proxy/
```
```
kubectl run --generator=run-pod/v1 kubernetes-bootcamp --image=gcr.io/google-samples/kubernetes-bootcamp:v1 --port=8080
```
```
openssl req -x509 -newkey rsa:4096 -sha256 -nodes -keyout tls.key -out tls.crt -subj "/CN=example.com" -days 365
```
