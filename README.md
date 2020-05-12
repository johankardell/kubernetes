# kubernetes

All those commands I keep forgetting. Not meant to be a complete reference.

## Kill all pods...

### in a namespace

    kubectl delete --all pods --namespace=foo

### based on a label

    kubectl delete pod -n app -l app=myapp
