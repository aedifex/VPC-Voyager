# VPC-Voyager

## Project Overview

VPC-Voyager is a project developed for CYBER 210 at UC Berkeley, focusing on demonstrating network scanning techniques in a cloud computing environment, specifically within an AWS Virtual Private Cloud (VPC). This project explores the application of traditional network scanning tools in a cloud-native setting, highlighting the similarities and differences compared to physical network infrastructures.

## Goals

- **Demonstrate Network Scanning**: Implement and showcase various network scanning techniques within an AWS VPC. Utilize tools like Nmap and Wireshark, demonstrating their application in a cloud-native environment.

- **Explore Cloud Networking**: Investigate TCP/IP and DNS functionalities in the context of AWS. Understand how cloud networking leverages these fundamental protocols and how it differs from traditional network infrastructures.

- **Compare Security Practices**: Examine the differences and similarities between security practices in cloud-native environments and traditional network setups, focusing on aspects like firewalls, intrusion detection, and security groups.

- **Hands-On Cloud Experience with IaC**: Gain practical experience in deploying and managing cloud resources using AWS. Utilize Terraform as a key tool for Infrastructure as Code, enabling efficient, repeatable, and scalable infrastructure deployment. This approach not only streamlines the provisioning process but also introduces best practices in cloud resource management.

- **Infrastructure as Code (IaC) with Terraform**: Emphasize the use of Terraform for defining, deploying, and modifying cloud infrastructure in a codified manner. This method ensures consistency across environments, simplifies change management, and enhances collaboration among team members.

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
