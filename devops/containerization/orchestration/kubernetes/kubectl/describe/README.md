### kubectl describe

**Usage:** Show details of Kubernetes objects and resources. <br />
**More information:** https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands#describe. <br />

Show details of pods in a namespace:

```
kubectl describe pods --namespace namespace
```

details of nodes in a namespace:

```
kubectl describe nodes --namespace namespace
```

the details of a specific pod in a namespace:

```
kubectl describe pods pod_name --namespace namespace
```

the details of a specific node in a namespace:

```
kubectl describe nodes node_name --namespace namespace
```

details of Kubernetes objects defined in a YAML manifest file:

```
kubectl describe --filename path/to/manifest.yaml
```
