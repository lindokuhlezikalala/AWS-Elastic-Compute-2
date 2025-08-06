# AWS-Elastic-Compute-Cloud-2
Server

This repository contains resources and notes related to **Amazon EC2**, a core service in AWS that provides scalable virtual servers in the cloud.

##  Overview
Amazon EC2 allows users to launch and manage virtual machines, configure networking, and scale compute capacity as needed. This project is part of the AWS Re/Start program.

##  Learning Objectives
- Launch EC2 instances using the AWS Console 
- Configure security groups and key pairs
- Understand instance types and pricing models

# Steps to Launch an EC2 Instance on AWS
1. Log in to AWS Console
Go to AWS Console

Sign in with your credentials

## Navigate to EC2 Dashboard
In the AWS Console, search for EC2

## Click Launch Instance

3. Choose an Amazon Machine Image (AMI)
4. Select an AMI (e.g., Amazon Linux 2023, Ubuntu, Windows Server)

AMIs are pre-configured OS templates

## Choose an Instance Type
Select a type like t3.micro (eligible for free tier)

Click Next: Configure Instance Details

## Configure Instance Details
Set number of instances (usually 1)

Choose network and subnet

Leave other settings as default for basic setup
- Add Storage
Default is 8 GB for Amazon Linux

You can increase or add volumes if needed

7. Add Tags (Optional)
Add tags like Name: MyEC2Instance to help identify your instance

8. Configure Security Group
Create a new security group or select an existing one

Add rules to allow SSH (port 22), HTTP (port 80), etc.
9. Select Key Pair
Choose an existing key pair or create a new one

Download the .pem file — you’ll need it to SSH into your instance

10. Launch the Instance
Review all settings

Click Launch

AWS EC2 instance can also be launched using CLI 

  
