# it-ae-azure-tf-template

This is a template for creating a new Terraform project for Azure. It demonstrates how to setup a state backend and OIDC federation for Azure.

## Terraform State

In the `terraform-state/` folder, there is a simple example of using the [state backend for Azure module](https://github.com/tamu-edu/it-ae-tfmod-azure-state). The resulting terraform files, including `terraform.tfstate` and `terraform.tfstate.backup` should be checked into source control. This is not usually suggested for production environments, but because this is a one-time event with no sensitive information, it is acceptable and useful later if the state needs to be cleaned up.

