# Kubernetics
kubectl run pod-nginx --image=nginx:latest --dry-run=client -o yaml
kubectl create -f pod.yaml
kubectl describe pod pod-nginx
kubectl create deployment httpd --image=httpd:latest
kubectl get deployment

#First Command: Generates a Pod configuration for nginx without creating it.

Second Command: Applies the generated configuration to create the Pod.

Third Command: Shows detailed information about the created Pod.

Fourth Command: Creates a new Deployment for httpd (Apache).

Fifth Command: Lists all existing Deployments.

These commands are useful for managing and debugging your Kubernetes resources.
