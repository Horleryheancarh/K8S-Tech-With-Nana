## Tech With Nana K8S Youtube Tutorial

### Start Minikube
```bash
  # start minikube
  minikube start

  # Give service an IP address
  minikube service <service-name>
```

### kubectl Commands
```bash
  # Create a deployment
  kubectl create deployment <deployment-name> --image=nginx
  # from file
  kubectl apply -f <file-name>

  # Delete a deployment
  kubectl delete deployment <deployment-name> --image=nginx
  # from file
  kubectl delete -f <file-name>

  # Check running resources
  kubectl get <resource>

  # Edit running deployment
  kubectl edit deployment <deployment-name>


  # Debugging
  kubectl logs <pod-name>
  kubectl describe <pod-name>
  kubectl exec -it <pod-name> -- bin/bash
```

### K8S files
```yaml
```