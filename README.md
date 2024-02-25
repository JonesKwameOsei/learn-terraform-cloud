<<<<<<< HEAD
# Made repo changes
# Terraform Cloud Getting Started Guide Example

This is an example Terraform configuration intended for use with the [Terraform Cloud Getting Started Guide](https://developer.hashicorp.com/terraform/tutorials/cloud-get-started/cloud-sign-up).

## What will this do?

This is a Terraform configuration that will create an EC2 instance in your AWS account. 

When you set up a Workspace on Terraform Cloud, you can link to this repository. Terraform Cloud can then run `terraform plan` and `terraform apply` automatically when changes are pushed. For more information on how Terraform Cloud interacts with Version Control Systems, see [our VCS documentation](https://www.terraform.io/docs/cloud/run/ui.html).

## What are the prerequisites?

You must have an AWS account and provide your AWS Access Key ID and AWS Secret Access Key to Terraform Cloud. Terraform Cloud encrypts and stores variables using [Vault](https://www.vaultproject.io/). For more information on how to store variables in Terraform Cloud, see [our variable documentation](https://www.terraform.io/docs/cloud/workspaces/variables.html).

The values for `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY` should be saved as environment variables on your workspace.
=======
# learn-terraform-cloud
Configuring a Version Control System (VCS) integration for Terraform organization, connect terraform workspace to the VCS repository, and trigger a speculative plan based on a pull request. Then, merge the pull request to automatically apply changes to the infrastructure to be built using Terraform Cloud. 
>>>>>>> d2995b5693178264adde0958d3d68343e5b10465
