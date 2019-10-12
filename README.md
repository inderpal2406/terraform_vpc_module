# terraform_vpc_module
This repository contains configuration files for a basic VPC module, which can be imported into other terraform configuration files.

## AWS VPC module for terraform
A lightweight VPC module for terraform

## Usage
module "vpc_basic" {
  source        = "github.com/inderpal2406/terraform_vpc_module"
  name          = "vpc_name"
  cidr          = "10.0.0.0/16"
  public_subnet = "10.0.1.0/24"
}

See [interface.tf](./interface.tf) file for additional configurable variables.

## License
[MIT](./LICENSE)
