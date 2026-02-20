

🚀 Project: Creating an Auto Scaling Group (ASG) in AWS – End-to-End Implementation 
    ----> https://baekid.lovestoblog.com/

Successfully designed and deployed a highly available and scalable architecture using AWS core services.

🔹 Key Concepts & Definitions

🔹 VPC (Virtual Private Cloud)
A logically isolated network in AWS where we launch our resources securely.

🔹 Availability Zone (AZ)
A physically separate data center within a region. Using multiple AZs ensures High Availability.

🔹 Public Subnet
Subnet with a route to the Internet Gateway (IGW). Used for Load Balancers or Bastion hosts.

🔹 Private Subnet
Subnet without direct internet access. Used for application or database servers.

🔹 Internet Gateway (IGW)
Enables communication between VPC and the internet.

🔹 NAT Gateway
Allows private instances to access the internet securely (for updates, patches).

🔹 EC2 (Elastic Compute Cloud)
Virtual servers in AWS.

🔹 Application Load Balancer (ALB)
Distributes incoming traffic across multiple EC2 instances.

🔹 Target Group
A logical group of EC2 instances where the Load Balancer forwards traffic.

🔹 AMI (Amazon Machine Image)
Pre-configured template used to launch EC2 instances.

🔹 Launch Template
Blueprint that defines EC2 configuration (AMI, instance type, security group, etc.).

🔹 Auto Scaling Group (ASG)
Automatically increases or decreases EC2 instances based on demand.

🔹 Architecture Implementation

✔ Created VPC with:

2 Availability Zones

2 Public Subnets

2 Private Subnets

1 Internet Gateway

1 NAT Gateway (zonal)

Configured Route Tables

✔ Launched Public & Private EC2 instances

✔ Created Internet-facing Application Load Balancer

✔ Created Target Groups with health checks

✔ Created Launch Template using AMI

✔ Configured Auto Scaling Group:

Selected 4 subnets across 2 AZs

AZ Distribution: Balanced best effort

Attached existing Target Group

Configured Target Tracking Policy (CPU-based scaling)

🎯 What I Learned From This Project

✅ Designing highly available architecture
✅ Difference between Public & Private subnet routing
✅ How Load Balancer improves fault tolerance
✅ How ASG maintains desired capacity automatically
✅ Importance of Health Checks
✅ Real-time scaling using Target Tracking policy
✅ Cost optimization with dynamic scaling

This hands-on project improved my understanding of AWS Networking, EC2, Load Balancing, and Auto Scaling in real-world scenarios.

💡 Interview Questions Related to This Project

1️⃣ What is the difference between Launch Template and Launch Configuration?
2️⃣ How does Auto Scaling maintain high availability?
3️⃣ What happens if one Availability Zone fails?
4️⃣ Difference between ALB and NLB?
5️⃣ What is Target Tracking Scaling Policy?
6️⃣ Why do we use a NAT Gateway in private subnet architecture?
7️⃣ What is the difference between Desired, Minimum, and Maximum capacity in ASG?
8️⃣ How do health checks work in ALB and ASG?

<img width="1919" height="1025" alt="Screenshot 2026-02-19 202500" src="https://github.com/user-attachments/assets/4855fc71-3f28-47ab-b270-ee16c4f6a7e2" />
----------------------------------------------------------------------------------------------------------------------------------------------------------------
<img width="1919" height="934" alt="Screenshot 2026-02-19 202524" src="https://github.com/user-attachments/assets/462f91e1-a441-4cf5-8d62-e97534180d67" />
----------------------------------------------------------------------------------------------------------------------------------------------------------------
![load](https://github.com/user-attachments/assets/3e56ebb6-aea0-45a2-8899-c3ade3838078)
----------------------------------------------------------------------------------------------------------------------------------------------------------------

<img width="1291" height="655" alt="Screenshot 2026-02-19 202507" src="https://github.com/user-attachments/assets/a8c12210-f61b-4e1a-88e3-a671633668a9" />

