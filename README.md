# Kubernetics
kubectl run pod-nginx --image=nginx:latest --dry-run=client -o yaml
kubectl create -f pod.yaml
kubectl describe pod pod-nginx
kubectl create deployment httpd --image=httpd:latest
kubectl get deployment
