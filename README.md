# terraform-aws-vpc

**Terraform VPC Module**
```
resource "aws_vpc" "main" {
  cidr_block       = var.cidr_block
  instance_tenancy = "default"
  tags             = var.tags
}
```