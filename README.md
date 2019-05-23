# terraform_sandbox
Terraform script

To start (in the directory): terraform init

Have way to provide AWS keys e.g. local file

terraform plan -var-file-'path_to_file_containing_AWS_secrets_and_PEM_file_path'

terraform apply -var-file-'path_to_file_containing_AWS_secrets_and_PEM_file_path'