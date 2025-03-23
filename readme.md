# Ansible Automation Projects

## Overview

Ansible is a powerful automation tool that simplifies IT infrastructure management by providing a declarative approach to configuration management, application deployment, and orchestration. With its agentless architecture, Ansible enables seamless automation across servers, cloud platforms, and containerized environments, making it an essential tool for DevOps teams.

This repository contains a collection of Ansible automation projects,leveraging various technologies such as Docker, Terraform, AWS, Kubernetes, and Jenkins to showcase the versatility of Ansible in real-world scenarios.

⸻

Projects Included

## 1. Deploying a Node.js Application

This project automates the deployment of a Node.js application on a cloud-based server. Using Ansible, we provision the server, install necessary dependencies, configure user access, and deploy the application efficiently.

Key Features:
- Automates server creation and configuration.
- Installs Node.js and required packages.
- Deploys and runs the application seamlessly.

## 2. Nexus Repository Automation

Nexus is a widely used artifact repository, and this project streamlines its deployment using Ansible. It ensures that the repository is installed, configured, and accessible with minimal manual intervention.

Key Features:
- Automates Nexus installation and setup.
- Configures server permissions and access.
- Ensures proper deployment verification.

## 3. Containerized Application Deployment with Docker

This project integrates Ansible with Docker to deploy containerized applications. It provisions an AWS EC2 instance, installs Docker and Docker Compose, and orchestrates containerized workloads.

Key Features:
- Automates AWS infrastructure setup.
- Installs and configures Docker.
- Deploys applications in containers with Docker Compose.

## 4. Terraform Integration with Ansible

This project demonstrates how Ansible can be used alongside Terraform to manage infrastructure. Terraform provisions cloud resources, while Ansible configures and maintains them dynamically.

Key Features:
- Automates Terraform execution with Ansible.
- Ensures cloud instances are properly configured post-deployment.
- Streamlines infrastructure as code (IaC) workflows.

## 5. Dynamic Inventory Management

Managing dynamic cloud environments requires an efficient way to track resources. This project utilizes Ansible’s dynamic inventory plugin to automatically update and manage cloud instances.

Key Features:
- Dynamically discovers AWS instances.
- Eliminates the need for static inventory files.
- Ensures real-time synchronization of cloud infrastructure.

## 6. Kubernetes Deployment Automation

Kubernetes is a powerful container orchestration platform, and this project leverages Ansible to automate the deployment of applications within a Kubernetes cluster.

Key Features:
- Automates Kubernetes cluster creation on AWS (EKS).
- Deploys applications into Kubernetes namespaces.
- Simplifies cloud-native application management.

## 7. Jenkins Integration for CI/CD Automation

Continuous Integration and Continuous Deployment (CI/CD) are critical for modern DevOps workflows. This project integrates Jenkins with Ansible to automate infrastructure provisioning and application deployment as part of a CI/CD pipeline.

Key Features:
- Automates Jenkins server setup.
- Configures CI/CD pipelines with Ansible.
- Streamlines deployment automation for various environments.

## 8. Structuring Ansible Playbooks with Roles

This project focuses on best practices for managing large Ansible playbooks by breaking them into structured roles, making them modular and reusable.

Key Features:
- Organizes Ansible configurations into roles.
- Enhances maintainability and scalability.
- Encourages best practices in Ansible automation.

⸻

Getting Started

### Prerequisites

To run these projects, ensure the following tools are installed:
- Ansible (pip install ansible)
- Terraform (Download Terraform)
- Docker (sudo apt install docker.io)
- AWS CLI (pip install awscli)
- Kubectl (for Kubernetes-based projects)

Setup & Execution
1. Clone the repository

``` bash
git clone https://github.com/kwenealete/ansible-playbooks-project.git
```

2. Modify the Inventory File

- Edit the inventory file to include target server IPs

3. Run Ansible Playbooks

``` bash
ansible-playbook <playbook-name>.yaml
```

## Why Use Ansible?

### 1. Agentless Automation

Unlike other configuration management tools, Ansible does not require agents on target machines, reducing complexity and overhead.

### 2. Simple & Readable YAML Playbooks

Ansible uses human-readable YAML syntax, making automation scripts easy to understand and maintain.

### 3. Infrastructure as Code (IaC) Compatibility

Works seamlessly with Terraform, AWS, and Kubernetes to provision and configure cloud environments efficiently.

### 4. Scalable & Reliable

Ansible can manage thousands of servers simultaneously, ensuring repeatable and consistent infrastructure deployment.

### 5. Seamless CI/CD Integration

Combining Ansible with Jenkins or GitHub Actions enables fully automated software deployment pipelines.