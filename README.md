# Terraform AWS VPC Module

## Example

```hcl
module "vpc-aws" {
  source  = "issallina/vpc-aws/module"
  version = "0.0.3"

  vpc_cidr = "10.0.0.0/16
  subnet_cidr = ["10.0.1.0/24", "10.0.2.0/24"]    
}
```
