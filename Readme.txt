Challenge #1 :  A 3 tier environment is a common setup.

> IAM and DNS Setup
IAM and DNS prerequisites are configured such as 
1. Add user and attach policy
2. Register the domain

aws configure --profile <profile_name>
aws route53 create-reusable-delegation-set –caller-reference 1224 –profile <profile_name>
> Credentials and Variables
3. Main.tf
4. Variables.tf
5. Terraform.tfvars
       ws_region and aws_profile etc 

> Terraform Init and IAM   
6. IAM S3 Profile, S3 Access Role and S3 Access policy

> VPC
7. Cidr block and dns hostname etc
8. Internet gateway
9. Route tablesetc

> Creating the Security Groups 
10. SSH & HTTP : ingress
11. Public Security group
12. Outbound internet access
13. Private Security Group
14. RDS Security Group
15. SQL access from public/private security group

> Creating S3 Bucket
16. S3 code bucket
> Creating the RDS instance
17. Compute and key pair
> Creating the ELB
18. Load balancer
> Creating the “Golden” AMI
19. Create AMI
> Configure Auto Scaling Group
20. launch configuration & ASG
> Route 53
21. primary zone
22. secondary zone
23. www &  db etc
