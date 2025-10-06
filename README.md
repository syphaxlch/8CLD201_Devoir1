# **Azure VM Deployment with Load Balancer and Autoscaling**

## **Overview**
This project automates the deployment of an Azure infrastructure consisting of two Virtual Machines (VMs) behind a **Load Balancer** with **autoscaling** capabilities.  
The configuration is fully managed through **Azure DevOps YAML pipelines**, and the source code is hosted on **GitHub**.  
The infrastructure is deployed using **ARM templates**, with all secrets securely stored in **Azure Key Vault**.

## **Objective**
The main goal of this project is to gain **hands-on experience with YAML pipelines in Azure DevOps** by building a complete CI/CD process to:
- Automatically deploy a scalable infrastructure on Azure  
- Implement load balancing using Azure Load Balancer  
- Enable autoscaling based on CPU utilization  

## **📸 Screenshots**

### Azure DevOps Pipeline – Successful Run
<img src="https://github.com/user-attachments/assets/b1d8e4ea-f31d-4474-8ce9-00ddcf72fe9b" alt="Successful Pipeline" width="60%" />

### Virtual Machines in Azure Portal
<img src="https://github.com/user-attachments/assets/29e03cd1-5471-446f-bd8d-9f5843a39e60" alt="Azure VMs" width="60%" />

### Deployed Website on Azure VMs
<img src="https://github.com/user-attachments/assets/c81ae9f9-aa69-4d2c-80be-095052c625e9" alt="Deployed Website" width="60%" />

## **Project Structure**
The repository contains the following components:
- **ARM Templates** → Define infrastructure (VMs, Load Balancer, autoscaling rules, network, etc.)  
- **PowerShell Script (PS1)** → Automate environment setup and deployment  
- **YAML Files** → Define CI/CD pipelines in Azure DevOps  
- **JSON Files** → Contain deployment parameters and configuration  

---

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
