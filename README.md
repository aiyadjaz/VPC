# Terraform project - Team-1 - VPC
# Project goals 
Project tasks:

* create infrustructure architecture
* the size of the resources (could be parameterized)
* determine dependencies between groups
*flexibility of the code
* make regionless dependency
* deploy into another region with a few clicks
* resources should not depend on specific region

#Team communication:

*How to negotatate with groups inside team
 - chat channel (telegram)
 - zoom
- etc
- which backends we use



# VPC
- make base for other groups - RDS, ASG should not wait
- VPC organise as a Terraform mudule
- module published in Terraform Registry for public use 



- 3 public subnets
- 3 private subnets
- 1 GW
- (depend on parameter) NAT GW
