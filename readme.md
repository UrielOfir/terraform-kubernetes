# About this Terraform code
With this terraform code you can create Kubernetes cluster and contaniner registry.  
Then you can easily run the Weight Tracker app on the cluster, with this Azure Devops pipeline: https://github.com/UrielOfir/kubernetes-pipeline


## requirements
You need to connect your machine to Azure, before you run this terraform code.

To run the code just write the commands:
```
terraform init;
terraform plan;
terraform apply;
```