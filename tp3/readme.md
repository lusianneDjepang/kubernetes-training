# Creation of a nodeport service

## Commands uses

* `kubectl apply -f namespace.yml`
* `kubectl apply -f pod-red.yml -n production`
* `kubectl apply -f pod-blue.yml -n production`
* `kubectl get pod -n production`
* `kubectl apply -f service-nodeport-web.yml -n production`
* `kubectl -n production get service`  
ou  
* `kubectl -n production get svc`
* `kubectl -n production describe svc service-nodeport-web`
