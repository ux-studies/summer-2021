# Create a pod
kubectl apply -f /your/path/to/pod.yaml
# Get the logs for a pod
kubectl logs $POD_NAME 
# Delete a pod
kubectl delete -f /your/path/to/pod.yaml
