CFT module for AWS EC2 Single Instance.

Resources created by module -
EC2 Single Instance, SecurityGroup, TargetGroup, ALBListener and InternetGateway.

Prerequisites
* Following values are required:
VPC, Two Private Subnets, EC2SecurityGroup, component.

For example - 

VPC id
VPC = "vpc-09814294f140cac4e"

Private Subnet1
SubnetA = "subnet-0dbe095a74d090f71"

Private Subnet2
SubnetB = "subnet-0876769b280289250"

EC2SecurityGroup id
EC2SecurityGroup = "sg-04153325b23fe6b86"

Usage -
1. Modify the parameter file (qual, dev etc) present under env_params folder.
