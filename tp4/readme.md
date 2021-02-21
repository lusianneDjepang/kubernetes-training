# Persistent Stockage

Creating volume-type volumes

mysql-volume.yml  
* `mkdir data-volume`
* `kubectl aplly -f  mysql-volume.yml`
* `kubectl get pod`
* `kubectl describe po mysql-volume`
* `ls /data-volume/`
* `kubectl delete -f mysql-volume.yml`
* `ls /data-volume/`  
  
  
Persistent volume : Allows you to make a pvc-type stacking  
  
* pv.yml`
* kubectl apply -f pv.yml`
* kubectl get pv`
* kubectl describe pv pv`
* pvc.yml`
* kubectl apply -f pvc.yml`
* kubectl get pvc`

pod mysql-pv.yml  
  
* `kubectl apply -f mysql-pv.yml`
* `kubectl get po`
* `kubectl describe pod mysql-pv`
* `ls /data-pv`
* `kubectl describe pv pvc`
