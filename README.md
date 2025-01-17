# AWS EC2 Experience

This repository documents my experience creating, managing, and working with AWS EC2 instances. It includes step-by-step guides, sample configurations, and key learnings.

## Highlights
- Created and managed EC2 instances using AWS Management Console and CLI.
- Configured key pairs for secure SSH access.
- Utilized security groups to manage network access.
- Automated EC2 creation using Terraform.

## Key Pair Created
1. Navigated to the *Key Pairs* section in the AWS Management Console.
2. Created a new key pair (example-key).
3. Downloaded the .pem file and keep it secure.

## 3. Launched an EC2 Instance
1. Navigated to *Instances > Launch Instance*.
2. Choose an AMI
3. Selected an instance type i.e t2.micro for free tier.
4. Assigned the key pair created earlier.
5. Configured security groups:
   - Allow SSH (port 22).
6. Launched the instance and noted its public IP/DNS.

## Connected to the Instance Using SSH.

## Using PuTTY (Windows):
1. Converted .pem to .ppk using PuTTYgen.
2. Loaded the .ppk file in PuTTY under SSH > Auth.
3. Connected using the instance's public IP.

## Automated Instance Creation (Terraform).


## Lessons Learned :
Understanding Instance type
Key Pair Management
Security Groups
IAM Roles
Cost management
Networking Configurations
