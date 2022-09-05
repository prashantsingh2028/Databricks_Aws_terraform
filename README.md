# Databricks_Aws_terraform


Step 1 : A development machine with the Terraform CLI . See Download Terraform on the Terraform website.

Run the following commands, one command at a time, from the preceding directory. These commands instruct Terraform to download all of the required dependencies to your development machine, inspect the instructions in your Terraform files, determine what resources need to be added or deleted, and finally, create all of the specified resources.


You must provide Terraform with your AWS account credentials. These can be specified through sources such as environment variables or shared configuration and credentials files. See https://registry.terraform.io/providers/hashicorp/aws/latest/docs#authentication-and-configuration on the Terraform website.

Step 2 : 
this not not best practice but can be used to do test deployment. 
Add access key and secret key for AWS in init file or add variable to get it via variable from command line 


access_key = "<aws access key>"
  
secret_key = "<aws secret key>"

Step 3 : 


Bash

terraform init
terraform apply -var-file="variable.tfvars"

Input values in commandline for variable .
  

Within a few minutes, your Databricks workspace is ready. Use the workspace’s URL, displayed in the commands’ output, to sign in to your workspace. Be sure to sign in with your Databricks workspace administrator credentials.
