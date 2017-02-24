# terraform_wordpress_aws
Edit the host file to required ip address
show an execution plan: terraform plan

Builds or makes actual changes in infrastructure: terraform apply

To inspect Terraform state or plan: terraform show

To destroy Terraform-managed infrastructure: terraform destroy

#Once the terraform creates the resources we actually run the ansible 

ansible-playbook site.yml -e../secret/secure.yml
