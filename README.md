# Cluster AWS EKS

## Instalação

```sh
terraform init
```

```sh
terraform apply --auto-approve
```

## Adicionando contexto do cluster ao kubectl

```sh
aws eks --region us-east-1 update-kubeconfig --name k8s-demo
```

```sh
kubectl get nodes
```
