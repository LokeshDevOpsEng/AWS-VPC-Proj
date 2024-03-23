# Project
AWS VPC Deployment for Secure and Scalable Infrastructure

## Description
VPC Setup: Orchestrated the setup of a tailored VPC architecture, establishing 2 public and 2 private subnets spanning across 2 availability zones within the VPC.

Network Configuration: Configured route tables to ensure efficient traffic routing, seamlessly integrating an Internet Gateway with public subnets to enable secure outbound Internet access.

Security Measures: Implemented stringent security protocols, including the deployment of a NAT Gateway to the private subnets, ensuring secure internet access for instances while maintaining confidentiality.

Auto Scaling Implementation: Leveraged Auto Scaling groups to deploy and manage EC2 instances in private subnets across availability zones, guaranteeing high availability and fault tolerance.

Enhanced Access Control: Implemented a Bastion host within the VPC to securely manage SSH access to instances in private subnets, bolstering overall security posture and enabling remote access.

Application Deployment and Load Balancing: Utilized the Bastion host to deploy applications across instances in private subnets, optimizing resource utilization. Additionally, set up an Application Load Balancer (ALB) across public subnets to evenly distribute incoming traffic among instances, ensuring optimal performance and availability.
![VPC Example Private Subnets](https://docs.aws.amazon.com/images/vpc/latest/userguide/images/vpc-example-private-subnets.png)

