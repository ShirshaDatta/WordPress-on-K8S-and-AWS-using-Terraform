# WordPress-on-K8S-and-AWS-using-Terraform
 You can find a detailed article on the same here =>

https://medium.com/@shirshadatta2000/deploy-the-wordpress-application-on-kubernetes-and-aws-using-terraform-c7833c11e276
## USAGE
To initialize with the dependencies
```
terraform init
```

To deploy the whole infrastructure on AWS consisting of:

* RDS and its dependencies
* WordPress over Kubernetes via Minikube
* Expose the WordPress pod

```
terraform apply --auto-approve
```

To destroy the infrastructure use the command:
```
terraform destroy --auto-approve
```
