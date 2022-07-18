# Set context
>kubectl config set-context contextName --namespace=namespaceName

# Alias for kubectl
>alias k=kubectl

# Find short resource names
>kubectl api-resources

# Delete objects
>kubectl delete pod podName --grace-period=0 --force

# Find obj info
>kubectl describe pods | grep ...

# Discover options
kubectl commandNAme --help
kubectl explain commandName

