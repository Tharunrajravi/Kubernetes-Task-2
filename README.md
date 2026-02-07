Kubernetes-Task-2

steps:
  - Configured AWS CLI using aws configure
  - Verified AWS authentication with sts get-caller-identity
  - Created AWS EKS cluster using eksctl
  - Waited for EKS control plane creation
  - Faced nodegroup creation delay due to instance capacity
  - Created new nodegroup with supported instance type
  - Updated kubeconfig to connect kubectl with EKS cluster
  - Deployed Nginx application using Kubernetes Deployment
  - Exposed Nginx using Service of type LoadBalancer
  - Retrieved external LoadBalancer DNS
  - Accessed Nginx application outside the cluster
