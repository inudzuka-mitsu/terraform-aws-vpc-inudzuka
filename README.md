# terraform-aws-vpc-inudzuka

```hcl
module "vpc" {
    source = "inudzuka-mitsu/vpcinudzuka/aws"
    region = "us-east-2"
    vpc_cidr = "10.0.0.0/16"
    s1_cidr = "10.0.1.0/24"
    s2_cidr = "10.0.2.0/24"
    s3_cidr = "10.0.3.0/24"
}
```
