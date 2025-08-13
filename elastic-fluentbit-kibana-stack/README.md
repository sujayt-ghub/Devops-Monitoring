kubectl apply -f . -n logging #to apply all yaml files at once
kubectl get all -n logging  #get all resource in namespace logging
kubectl get cm -n logging #check configmap created under namespace logging
kubectl logs pod/fluent-bit-qc5nq -n logging #check the logs of the fluent-bit pod for any error 
