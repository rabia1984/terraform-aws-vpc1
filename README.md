#   Terraform Aws vpc Module
### USAGE

```
module "vpc" {
    source = "rabia1984/vpc1/aws"
    cidr_block = "10.0.0.0/16"
    private_subnets_cidr = [10.0.1.0/24]

    tags {
        name = "Dev"
    }

}

```