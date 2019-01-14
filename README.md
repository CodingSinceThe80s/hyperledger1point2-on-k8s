# hyperledger1point2-on-k8s
Helps you setup a hyperledger 1.2 deployment with kafka using the Azure Kubernetes Service

# Setting up the Kubernetes cluster
## Prereqs
The kubectl tool - if on Windows you have to get the binary (kubectl.exe)
## Instructions
After having freshly deployed an AKS (Azure Kubernetes Services) cluster you may wish to create a service account for Tiller. Please use the k8s-setup/helm-rbac.yaml file to do this e.g
kubectl apply -f k8s-setup/helm-rbac.yaml
