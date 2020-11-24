# lambda-code-pipeline-terraform
Terraform code for create a CodePipeline for lambda

### Usage
```HCL
module "lambda-code-pipeline" {
  source   = "abdellatif05/lambda-code-pipeline/aws"
  prefix                    = "your-prefix"
  codestar_connection_arn   = "arn-of-aws-codestar-connection"
  repository_id             = "your-lambda-repository"
  branch_name               = "branche-name"
  cloudformation_stack_name = "cloudformation-name-of-lambda"
}
```
