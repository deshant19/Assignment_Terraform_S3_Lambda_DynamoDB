# Terraform_S3_Lambda_DynamoDB

Prerequisites:
1. Terraform binaries are required to be installed.
2. A .csv file(Added information.csv)

Steps to run:
1. Add Access key and secret key to providers.tf
2. Run following commands</br>
  2.1 terraform init</br>
  2.2 terraform plan</br>
  2.3 terraform apply(Creates S3 buket, aws lambda, iam roles and dynamodb)
3. Upload csv file to s3 bucket created.
