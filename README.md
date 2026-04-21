# ☸️ EKS Deployment Automation | Ansible & Kubernetes

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white)

## 🎯 Overview
This project demonstrates a production-ready automation workflow for deploying applications on **Amazon EKS (Elastic Kubernetes Service)**. It leverages **Ansible** to orchestrate Kubernetes resources, ensuring a repeatable and error-free deployment process.

## 🛠️ Architectural Features
- **Infrastructure as Code (IaC):** Full automation using Ansible playbooks.
- **EKS Auto Mode Integration:** Optimized using AWS-specific annotations for Load Balancer provisioning.
- **High Availability:** Configured with multiple replicas and automated service discovery.
- **Public-Facing Access:** Integrated with AWS Elastic Load Balancing (ELB).

## 🚀 Quick Start
1. **Clone the Repo:**
   ```bash
   git clone https://github.com/MuhammadAbdelkader/eks-ansible-deploy.git
   ```
2. **Execute Deployment:**
   ```bash
   ansible-playbook -i inventory.ini deploy.yml
   ```

## 🧠 Skills Demonstrated
- Cloud Networking (VPC, Subnets, ELB Tagging)
- Configuration Management (Ansible)
- Container Orchestration (Kubernetes)
- Troubleshooting & Debugging Cloud Environments

---
**Maintained by [Mohamed Abdelkader](https://github.com/MuhammadAbdelkader)** *Software & Technical Engineer | Final Year IS Student @ Benha University*
