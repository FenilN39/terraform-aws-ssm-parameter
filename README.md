# terraform-aws-ssm-parameter

[![CircleCI](https://circleci.com/gh/tmknom/terraform-aws-ssm-parameter.svg?style=svg)](https://circleci.com/gh/tmknom/terraform-aws-ssm-parameter)
[![GitHub tag](https://img.shields.io/github/tag/tmknom/terraform-aws-ssm-parameter.svg)](https://registry.terraform.io/modules/tmknom/ssm-parameter/aws)
[![License](https://img.shields.io/github/license/tmknom/terraform-aws-ssm-parameter.svg)](https://opensource.org/licenses/Apache-2.0)

Terraform module template following [Standard Module Structure](https://www.terraform.io/docs/modules/create.html#standard-module-structure).

## Usage

Named `terraform-<PROVIDER>-<NAME>`. Module repositories must use this three-part name format.

```sh
curl -fsSL https://raw.githubusercontent.com/tmknom/terraform-aws-ssm-parameter/master/install | sh -s terraform-aws-sample
cd terraform-aws-sample && make install
```

## Examples

- [Minimal](https://github.com/tmknom/terraform-aws-ssm-parameter/tree/master/examples/minimal)
- [Complete](https://github.com/tmknom/terraform-aws-ssm-parameter/tree/master/examples/complete)

## Inputs

Write your Terraform module inputs.

## Outputs

Write your Terraform module outputs.

## Development

### Requirements

- [Docker](https://www.docker.com/)

### Configure environment variables

```shell
export AWS_ACCESS_KEY_ID=AKIAIOSFODNN7EXAMPLE
export AWS_SECRET_ACCESS_KEY=wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
export AWS_DEFAULT_REGION=ap-northeast-1
```

### Installation

```shell
git clone git@github.com:tmknom/terraform-aws-ssm-parameter.git
cd terraform-aws-ssm-parameter
make install
```

### Makefile targets

```text
check-format                   Check format code
cibuild                        Execute CI build
clean                          Clean .terraform
docs                           Generate docs
format                         Format code
help                           Show help
install                        Install requirements
lint                           Lint code
release                        Release GitHub and Terraform Module Registry
terraform-apply-complete       Run terraform apply examples/complete
terraform-apply-minimal        Run terraform apply examples/minimal
terraform-destroy-complete     Run terraform destroy examples/complete
terraform-destroy-minimal      Run terraform destroy examples/minimal
terraform-plan-complete        Run terraform plan examples/complete
terraform-plan-minimal         Run terraform plan examples/minimal
upgrade                        Upgrade makefile
```

### Releasing new versions

Bump VERSION file, and run `make release`.

### Terraform Module Registry

- <https://registry.terraform.io/modules/tmknom/ssm-parameter/aws>

## License

Apache 2 Licensed. See LICENSE for full details.
