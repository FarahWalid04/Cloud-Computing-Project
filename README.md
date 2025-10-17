Simplified File-Sharing Web Application on AWS

📖 Overview

This project demonstrates how to build a simplified file-sharing web application using Amazon Web Services (AWS).
It integrates core AWS services—VPC, EC2, S3, IAM, and Internet Gateway—to provide a secure, scalable, and cloud-native file-storage system.
The web app was built with Flask (Python) and deployed on an EC2 instance connected to an S3 bucket for file storage.

☁️ Key Features

Upload and download files through a simple web interface
Secure storage on Amazon S3 with IAM-based access control
Flask backend hosted on Amazon EC2
Custom Virtual Private Cloud (VPC) setup for isolation and routing
Internet Gateway and Route Tables for external access
Subnet and security group configurations for network management

🧱 AWS Services Used

Amazon VPC:	Created a virtual private network for hosting resources securely
Subnets & Route Tables:	Structured network traffic and routing rules
Internet Gateway:	Enabled public internet access for the EC2 instance
Amazon S3	Stored: user-uploaded files
IAM Roles & Policies:	Controlled access between EC2 and S3
Amazon EC2:	Hosted the Flask web application

💻 Tech Stack

Frontend: HTML, CSS
Backend: Python (Flask)
Cloud Provider: AWS
Storage: Amazon S3
Networking: VPC, Subnets, Internet Gateway, Route Tables
Access Management: IAM Roles and Policies

🚀 Deployment Steps (Summary)

Create AWS VPC, Subnet, Route Table, and Internet Gateway
Set up S3 bucket (sya7-s3-bucket) for file storage
Create IAM policy and role to allow EC2 access to S3
Launch EC2 instance and attach the IAM role
Deploy Flask app on EC2 and connect it to S3
Access the web app through the EC2 public IPv4 address

👩‍💻 Team Members

Farah Walid: AWS Account Setup, Testing & Documentation
Nour Essam:	Web App Development
Basmala Hossam: El-Din	EC2 & IAM Setup
Rodina Mohamed:	S3 & File Handling
Mariam Ahmed:	VPC Configuration & Testing

🔗 Demo Links

🌐 Live Demo: http://34.228.158.194
📂 Project Drive: View on Google Drive
