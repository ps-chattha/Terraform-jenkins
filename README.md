# Terraform Jenkins

This repository contains a basic Terraform script for deploying infrastructure on Azure.

## Overview

This script provisions the following resources within a specified resource group named **"Project4TF"** located in the **"eastus"** region. You can easily modify the resource group name and location to fit your needs.

### Resources Deployed

The Terraform script will create the following Azure resources:

1. Virtual Machine
2. Virtual Network
3. Network Security Group
4. Network Interface
5. Public IP Address
6. Storage Account
7. OS Disk

## Getting Started

### Prerequisites

- [Terraform](https://www.terraform.io/downloads.html) installed on your machine.
- An Azure account. Sign up for a [free account](https://azure.com/free) if you don't have one.

### Clone the Repository

```bash
git clone https://github.com/yourusername/terraform-jenkins.git
cd terraform-jenkins
