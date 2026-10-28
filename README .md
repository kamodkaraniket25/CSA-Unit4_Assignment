
# Project Title

A brief description of what this project does and who it's for

# AWS EC2 Windows Instance Setup

This project documents the step-by-step process to launch and connect to a Windows EC2 instance on AWS.

## 🔧 Services Used
- Amazon VPC
- Subnets & Route Tables
- Security Groups
- EC2 Instance (Windows Server)
- Elastic IP
- RDP Connection

## 🚀 Setup Steps
1. Create VPC and Subnet
2. Configure Security Group (Allow RDP - Port 3389)
3. Launch EC2 Windows Instance
4. Assign Elastic IP
5. Connect via RDP using decrypted password

   ## 📸 Architecture Diagram
![AWS Architecture Diagram](architecture-diagram.png)
[ User Laptop ] --RDP--> [ Elastic IP ] --> [ EC2 Windows Instance ]
                                     |
                                     v
                                [ Security Group (RDP 3389 allowed) ]
                                     |
                                     v
                                [ Public Subnet ] --> [ VPC ]

### EC2 Instance Running


## 📁 Files Included
- Setup Guide
- Architecture Diagram
- Notes

## 👤 Author
Namit Srivastava  
Aspiring Cloud Support Engineer  
[LinkedIn Profile]-www.linkedin.com/in/namit-srivastava-4587b6164
