# aws-vpc-networking-project
Custom AWS VPC with public/private subnets and EC2 web server development
AWS Custom VPC Networking Project
📌 Project Overview
This project demonstrates the design and deployment of a custom Virtual Private Cloud (VPC) in AWS with a public subnet hosting a web server.
The objective was to understand AWS networking fundamentals and implement a fully functional public web server architecture.
🏗 Architecture Components
Custom VPC (10.0.0.0/16)
Public Subnet
Private Subnet
Internet Gateway
Custom Route Tables
Security Groups
EC2 Instance (Amazon Linux)
Apache Web Server
🌐 Network Flow
Internet → Internet Gateway → Route Table → Public Subnet → EC2 Instance
🚀 Deployment Steps
Created custom VPC
Created public & private subnets
Attached Internet Gateway
Configured route tables
Associated public subnet with IGW route
Configured security group (SSH & HTTP)
Launched EC2 instance
Installed Apache web server
Deployed test webpage
🔐 Security Configuration
SSH (Port 22) allowed from "My IP"
HTTP (Port 80) allowed from Anywhere
No public IP assigned to private subnet resources
🧠 Key Lessons Learned
Difference between public and private subnets
Importance of route table association
How to troubleshoot SSH timeout issues
How security groups control inbound traffic
📷 Screenshots
(Add screenshots of:)
VPC configuration
Route table
Security group rules
Running EC2
Live webpage in browser
📌 Future Improvements
Implement Bastion Host architecture


## 📷 Architecture Screenshots

### VPC Configuration
![VPC](screenshots/vpc.png)

### Subnets
![Subnets](screenshots/subnets.png)

### Route Table
![Route Table](screenshots/route-table.png)

### Security Group
![Security Group](screenshots/security-group.png)

### EC2 Instance Running
![EC2](screenshots/ec2.png)

### Live Webpage
![Live Webpage](screenshots/live-webpage.png)



Deploy private EC2
Add Application Load Balancer
Automate deployment using Terraform
