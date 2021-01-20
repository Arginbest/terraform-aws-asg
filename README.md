# A Terraform module for creating an Auto-Scaling Group and a launch configuration for it, 
# for use with an Elastic Load Balancer. Add this module and Change following variables:

```
module "wordpress-oregon" {

source = "./module"

region = "us-west-2"

image_owner = "137112412989"

desired_capacity = 1

max_size = 1

min_size = 1 
} 
```
