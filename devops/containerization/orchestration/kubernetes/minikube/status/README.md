### minikube status

**Usage:** Gets the status of a local Kubernetes cluster. <br />

Check cluster status (default text output):

```
minikube status
```

Continuously watch cluster status every 1 second:

```
minikube status --watch=1s
```

Show status for a specific node (e.g., minikube-m02):

```
minikube status --node=minikube-m02
```

Output in JSON format:

```
minikube status --output=json
```

Customize output using Go template format:

```
minikube status --format='{{.Name}}: Host={{.Host}}, Kubelet={{.Kubelet}}, API={{.APIServer}}'
```
