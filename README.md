## terraform-vpc-may
```hcl
module "may" {
  source  = "abdy1988/may/vpc"
  version = "2.0.0"
  vpc_cidr = "172.31.0.0/16"
  subnet1_cidr = "172.31.1.0/24"c# insert the 4 required variables here
  subnet2_cidr = "172.31.2.0/24"  
  subnet3_cidr = "172.31.3.0/24"
  vpc_name = "kaizen"
  }
  ```