# postgres-sql

=======================================================

1.  kubectl create -f postgres-configmap.yaml 
2.  kubectl create -f postgres-storage.yaml 
3.  kubectl create -f postgres-deployment.yaml 
4.  kubectl create -f postgres-service.yaml 

# kubectl delete service postgres
# kubectl delete deployment postgres
# kubectl delete configmap postgres-config
# kubectl delete persistentvolumeclaim postgres-pv-claim
# kubectl delete persistentvolume postgres-pv-volume
