# timeoff-management-app-infra

Terraform IaC form TimeOff Application

# AWS Components Used

* Virtual Private Cloud (VPC)
* Public Subnets
* Private Subnets
* Internet Gateways (IG)
* NAT Gateways + Elastic IPs
* Application Load Balancer (ALB)
* Security Groups (SG) 
* Elastic Container Registry (ECR)
* Elastic Container Service (ECS) + Fargate
* Auto Scaling Group (ASG)
* Cloudwatch Dashboard
* Cloudwatch Logs
* Cloudwatch Metrics
* Cloudwatch Alarms
* IAM Policies and Roles
* KMS Encryption Key

## Requirements
| Name | Version |
|------|---------|
| terraform | >= 0.12.6, < 0.14 |
| aws | ~> 2.57 |

## Providers

| Name | Version |
|------|---------|
| aws | ~> 2.57 |

## CD/CD 

* Github Actions