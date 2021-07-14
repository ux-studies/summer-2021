# Create a namespace
kubectl create namespace [namespace-name]
# Create an application in the namespace
kubectl apply --namespace [namespace-name] -f /your/path/to/guestbook
# Get the pods
kubectl get pods --namespace [namespace-name]
# Get the logs for a pod
kubectl logs --namespace [namespace-name] [pod-name]
# Delete an application in the namespace
kubectl delete --namespace [namespace-name] -f /your/path/to/guestbook
# Delete a namespace
kubectl delete namespace [namespace-name]
