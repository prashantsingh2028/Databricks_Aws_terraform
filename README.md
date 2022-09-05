# Databricks_Aws_terraform

Run the following commands, one command at a time, from the preceding directory. These commands instruct Terraform to download all of the required dependencies to your development machine, inspect the instructions in your Terraform files, determine what resources need to be added or deleted, and finally, create all of the specified resources.




Bash

terraform init
terraform apply -var-file="variable.tfvars"

Within a few minutes, your Databricks workspace is ready. Use the workspace’s URL, displayed in the commands’ output, to sign in to your workspace. Be sure to sign in with your Databricks workspace administrator credentials.
