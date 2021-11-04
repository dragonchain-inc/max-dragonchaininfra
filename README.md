# Infra Deployment

## Terraform

```
cd terraform
terraform init
terraform plan
terraform apply
```

## OpenFaaS

```
# curl -sL https://cli.openfaas.com | sudo sh
# arkade install openfaas --load-balancer
```

# Helm

```
# cd helm
# helm upgrade --install my-dragonchain --values opensource-config.yaml --namespace dragonchain dragonchain/dragonchain-k8s
```
