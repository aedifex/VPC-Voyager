# VPC-Voyager

## Project Overview

VPC-Voyager is a project developed for CYBER 210 at UC Berkeley, focusing on demonstrating network scanning techniques in a cloud computing environment, specifically within an AWS Virtual Private Cloud (VPC). This project explores the application of traditional network scanning tools in a cloud-native setting, highlighting the similarities and differences compared to physical network infrastructures.

## Goals

- **Demonstrate Network Scanning**: Implement and demonstrate various network scanning techniques within an AWS VPC.
- **Explore Cloud Networking**: Delve into TCP/IP and DNS functionalities in a cloud environment.
- **Compare Security Practices**: Analyze the differences between cloud-native and traditional network security practices.
- **Hands-On Cloud Experience**: Provide a practical experience in setting up and securing cloud resources using AWS and Terraform.

## System Setup

The project infrastructure, including the AWS VPC and related network components, is provisioned and managed using Terraform. This setup includes an EC2 instance configured for network scanning exercises.

### Prerequisites

What things you need to install the software and how to install them:

- AWS Account
- Terraform
- SSH Client

### SSH Access

Students will connect to the EC2 instance via SSH for practical exercises. Here's how to get started:

1. **SSH Key Pair**: Ensure you have the `MICS210` SSH key pair provided by the project administrator.
2. **Connecting to the Instance**:
   - Use the following SSH command, replacing `<Public-IP>` with the instance's public IP address:
     ```
     ssh -i "path/to/MICS210.pem" ubuntu@<Public-IP>
     ```
   - If you're using a Windows machine, you might need an SSH client like PuTTY.

### Interacting with the System

Once connected via SSH, students can perform network scanning tasks and explore cloud network functionalities as part of their coursework.

## Contribution

This project is primarily intended for educational purposes within CYBER 210. Contributions, suggestions, and feedback are welcome from all students participating in the course.
