## Rolling update command

kubectl rollout undo deployment deployment-rolling

## AWS CLI Download Link

https://awscli.amazonaws.com/AWSCLIV2.msi

## Kubectl Downlaod

https://dl.k8s.io/v1.33.3/bin/windows/amd64/kubectl.exe

## EKS Connection Commands

aws eks --region us-east-1 describe-cluster --name hiteshCluster --query cluster.status

aws eks --region us-east-1 update-kubeconfig --name hiteshCluster

