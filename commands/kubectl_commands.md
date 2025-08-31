### make port forward
```bash
kubectl port-forward --help
```
example
```bash
  # Listen on ports 5000 and 6000 locally, forwarding data to/from ports 5000 and 6000 in the pod
  kubectl port-forward pod/mypod 5000 6000
```
Note: It can be done with different Kubernetes elements, for example pods, deployments, services.