# 🚀 Deploy a High-Availability Web App using CloudFormation

This project demonstrates the deployment of a highly available web application using AWS CloudFormation. It automates the provisioning of infrastructure components, including networking resources, EC2 instances, and load balancing, to ensure scalability and fault tolerance.

## 🧰 Key Features

- **Infrastructure as Code**: Utilizes CloudFormation templates to define and provision AWS resources, promoting consistency and repeatability.
- **High Availability**: Implements multi-AZ deployment strategies to ensure application availability even in the event of an AZ failure.
- **Scalability**: Configures Auto Scaling groups to dynamically adjust the number of EC2 instances based on traffic demands.
- **Load Balancing**: Sets up an Application Load Balancer to distribute incoming traffic across multiple EC2 instances, enhancing performance and reliability.
- **Security**: Defines security groups and IAM roles to control access to resources and adhere to the principle of least privilege.

## 📂 Repository Contents

- `final-project-starter.yml`: CloudFormation YAML template for defining the infrastructure.
- `server-parameters.json`: JSON file containing parameters for the CloudFormation stack.
- `project diagram.png`: Visual representation of the infrastructure architecture.

## 🌐 Accessing the Application

After deployment, the application can be accessed via the provided Load Balancer URL:

**Load Balancer URL**: `IacPr-WebAp-1BWIF9ZGP6G00-1535725605.us-west-2.elb.amazonaws.com`
