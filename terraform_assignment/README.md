# Terraform Docker Container Provisioning Guide

This guide explains how to initialize, apply, and manage Terraform configurations to provision Docker containers.

## Steps to Initialize and Apply Terraform

### 1. Initialize the Terraform Working Directory
Run the following command to initialize your Terraform project:
```bash
terraform init
```

### 2. Preview the Terraform Execution Plan
To see what changes Terraform will make, use:
```bash
terraform plan
```

### 3. Apply the Configuration
Apply the configuration to create the Docker container:
```bash
terraform apply
```
When prompted, confirm by typing `yes`.

### 4. Verify
To ensure the container is running, execute:
```bash
docker ps
```
This will list all running containers. Look for the container you provisioned.

### 5. Clean Up
To remove the container and image created by Terraform:
```bash
terraform destroy
```
Confirm the destruction by typing `yes`.

---

By following these steps, you can easily manage Docker containers using Terraform.

