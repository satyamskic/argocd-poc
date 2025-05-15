# Argocd POC

### Install argocd  
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml

### To get secret
kubectl get secret argocd-initial-admin-secret -n argocd 

### minkube ip 
192.168.59.101

### Argocd Username and Password
Username - admin
Password - DsyvXi0zrzkj4xc2