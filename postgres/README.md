# postgres-sql

=======================================================

1.  kubectl create -f postgres-configmap.yaml 
2.  kubectl create -f postgres-storage.yaml 
3.  kubectl create -f postgres-deployment.yaml 
4.  kubectl create -f postgres-service.yaml 

=========================================================
To delete the deployment
1.   kubectl delete service postgres
2.   kubectl delete deployment postgres
3.   kubectl delete configmap postgres-config
4.   kubectl delete persistentvolumeclaim postgres-pv-claim
5.   kubectl delete persistentvolume postgres-pv-volume
