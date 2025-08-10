### kubectl get

**Usage:** Get Kubernetes objects and resources. <br />
**More information:** https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands#get. <br />

Get all namespaces in the current cluster:

```
kubectl get namespaces
```

Get nodes in a specified namespace:

```
kubectl get nodes --namespace namespace
```

Get pods in a specified namespace:

```
kubectl get pods --namespace namespace
```

Get deployments in a specified namespace:

```
kubectl get deployments --namespace namespace
```

Get services in a specified namespace:

```
kubectl get services --namespace namespace
```

Get all resources in a specified namespace:

```
kubectl get all --namespace namespace
```

Get Kubernetes objects defined in a YAML manifest file:

```
kubectl get --filename path/to/manifest.yaml
```
