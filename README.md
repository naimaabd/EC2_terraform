# EC2_terraform
Creating an EC2 instance using Terraform

<!-- BEGIN_TF_DOCS -->
## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | 5.39.0 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [aws_instance.web](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_ami"></a> [ami](#input\_ami) | the ami of the EC2 instance | `string` | n/a | yes |
| <a name="input_instance_type"></a> [instance\_type](#input\_instance\_type) | the type of the EC2 instance | `string` | n/a | yes |

## Outputs

No outputs.
<!-- END_TF_DOCS -->