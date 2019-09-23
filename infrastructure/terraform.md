# Terraform

Terraform is our infrastructure as code tool. It is responsible for all the infrastructure held on the convivio.cloud domain.

Our existing Terraform setup is very much a work in progress. The initial definitions were exported from AWS using a third party tool. Work is ongoing to move components into logical modules.

tfstate is managed via S3 and DynamoDB.

All changes to AWS infrastructure are managed by Mike Bell.

