# AWS-CloudFormation
Creating an Amazon VPC and Amazon EC2 instance (and other supporting elements) using an AWS CloudFormation template. The goal is to create a CloudFormation template with the following components
- An Amazon Virtual Private Cloud
- An internet gateway attached to the VPC
- Security groups for accessing the VPC configured to allow SSH from anywhere
- A private subnet within the VPC
- An Amazon EC2 instance (a T3.micro) within the private subnet (Note: It is not necessary to access the EC2 via SSH or Remote Desktop for a successful solution)
