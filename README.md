# terraform-module-november-2024

```hcl
module "november-2024" {
  source  = "Bakyt65/november-2024/module"
  version = "4.0.0"
  region = "us-east-1" # Replace with your place
  vpc_cidr = "10.0.0.0/16" # Replace with your place
  subnet_cidr = "10.0.1.0/24" # Replace with your place
  igw_name = "Kaizen" # Replace with your place
}

```