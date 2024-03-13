# Control Tower CloudFormation

Repo contains the cloudformation template to deploy AWS Control Tower with the new CloudFormation resources. The template can deploy a new AWS Organization and Control Tower environment. Only inputs needed (required parameters) are two email addresses (ones never used with an AWS account) to create a security and log archive accounts in your control tower deployment. You can also use existing AWS accounts by importing them via this template.

## TL:DR

Template sets up AWS Control Tower in your AWS Management account or standalone AWS account. Deploy template in your home AWS Region, which is the region you want to manage AWS Control Tower from.
