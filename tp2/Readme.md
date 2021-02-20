# Deployment of my first application : NGINX

## Commands uses to execute our Pod
* `kubectl apply -f pod.yml`
* `kubectl get pod`
* `kubectl describe po simple-webapp-color`

## Commands uses to execute our  Deployment
* `kubectl apply -f nginx-deployment.yml`
* `kubectl get deploy`
* `kubectl get  replicaset`
* `kubectl get po`  
If we wont to see more details:
* `kubectl get  replicaset -o wide` 
