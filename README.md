# tf_chef_server_aws
Terraform Config Module for spinning up a Chef Server on AWS

## This is a work in progress!

## Pre-requisites

To use this module, you will need
* An AWS account
* AWS access key and secret key credentials
* An AWS keypair
* At least one AWS Security Group
* An AWS VPC (default is fine)

## Inputs

### AWS Inputs
access_key
secret_key
region
instance_type
ami
key_name
private_ssh_key_path
vpc_security_group_ids
vpc_subnet

### Chef Server Inputs
chef_server_username
chef_server_user_full_name
chef_server_user_email
chef_server_user_password
chef_server_organization
chef_server_organization_full_name

## Outputs

TBD
