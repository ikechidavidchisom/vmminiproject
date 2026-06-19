# Azure Virtual Machine Deployment with ARM Templates

## Overview
This project demonstrates Infrastructure as Code (IaC) in Microsoft Azure using ARM templates. It provisions a Virtual Machine (VM) along with networking resources such as Virtual Network, Subnet, Network Interface, and Public IP. The template is parameterized for reusability and scalability.

## Template Structure
- **Parameters**: Inputs like VM name, location, admin credentials.
- **Variables**: Optional reusable values.
- **Resources**: Definitions for VNet, Subnet, NIC, Public IP, NSG, and VM.
- **Outputs**: Returns the VM’s Public IP address after deployment.

## Usage
1. Login to Azure:
   ```bash
   az login