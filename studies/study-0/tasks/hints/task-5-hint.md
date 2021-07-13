# Create an application
kubectl apply -f /your/path/to/guestbook
# Get the pods
kubectl get pods
# Get the logs of a pod
kubectl logs $POD_NAME
# Delete an application
kubectl delete -f /your/path/to/guestbook
