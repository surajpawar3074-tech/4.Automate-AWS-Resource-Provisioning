
# Automate AWS Resource Provisioning using Boto3

##  Project Overview
This project demonstrates how to **automate AWS infrastructure provisioning using Python scripts** instead of manual console operations.

Using Boto3, the script automatically:
- Creates an S3 bucket
- Generates a key pair
- Configures a security group
- Launches an EC2 instance
- Deploys a simple web server

---

##  Objective
To eliminate manual AWS setup by:
- Automating infrastructure creation
- Reducing human errors
- Saving time using Infrastructure as Code (IaC)

---

##  AWS Services Used

- AWS IAM – Provides permissions to access AWS services  
- :contentReference[oaicite:1]{index=1} – Launches virtual server  
- :contentReference[oaicite:2]{index=2} – Stores objects (bucket creation)  
- :contentReference[oaicite:3]{index=3} – Python SDK to interact with AWS  

---

##  Architecture Flow

Python Script → Boto3 → AWS Services (S3 + EC2 + Security Group)

---

##  Features

- ✅ Fully automated infrastructure setup  
- ✅ Dynamic EC2 instance launch  
- ✅ Auto web server deployment using User Data  
- ✅ Public IP retrieval for access  
- ✅ Error handling (existing resources)  

---

1.S3 bucket:

<img width="1122" height="299" alt="Screenshot 2026-04-29 151105" src="https://github.com/user-attachments/assets/bcda9517-78c7-478f-b707-5be9af21f5de" />

2.EC2 instances:

<img width="1272" height="239" alt="image" src="https://github.com/user-attachments/assets/1c97f5c1-b980-4648-95f4-2c587d2b9000" />

Output:

<img width="1049" height="185" alt="Screenshot 2026-04-29 151356" src="https://github.com/user-attachments/assets/2bb85878-7fb0-4954-9393-c0b2a592d6d1" />
