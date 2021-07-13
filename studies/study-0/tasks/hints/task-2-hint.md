# Create an application
kubectl apply -f /your/path/to/pod.yaml
# Get the logs for a pod
kubectl logs $POD_NAME 
# Delete an application
kubectl delete -f /your/path/to/pod.yaml
