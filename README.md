# Challenge: Creating a Virtual Machine in Microsoft Azure

## Challenge Overview

This challenge will guide you through the basic steps of creating and configuring a Virtual Machine (VM) in Microsoft Azure. You will learn how to deploy a VM, select its configuration, and understand key Azure concepts such as resource groups, regions, and networking.

## Objectives

- Understand the process of creating a Virtual Machine in Azure.
- Learn about essential VM configuration options (size, OS, authentication).
- Organize resources using resource groups and tags.
- Gain hands-on experience with the Azure Portal.

## What You Will Do

1. **Azure Account Setup**
   - Sign in to the [Azure Portal](https://portal.azure.com).
   - If you don’t have an account, create a free Azure account.

2. **Create a Resource Group**
   - Go to "Resource groups" and click "Create".
   - Enter a name and select a region to organize your resources.

3. **Deploy a Virtual Machine**
   - Click on "Create a resource" and select "Virtual Machine" under the "Compute" category.
   - Fill in the required details:
     - **Resource Group:** Select your resource group.
     - **Virtual Machine Name:** Choose a unique name.
     - **Region:** Select the Azure region closest to you.
     - **Image:** Choose the operating system (e.g., Windows Server, Ubuntu).
     - **Size:** Select the VM size (e.g., Standard_B1s for testing).
     - **Authentication:** Set up username/password or SSH key.
   - Configure additional settings as needed (networking, disks, etc.).
   - Click "Review + create" and then "Create" to deploy the VM.

4. **Access and Manage Your VM**
   - Once deployed, go to the VM resource page.
   - Use the "Connect" option to access your VM via RDP (Windows) or SSH (Linux).
   - Start, stop, or restart your VM from the Azure Portal.

5. **Organize and Locate Your VM**
   - Assign tags to your VM (e.g., `environment:test`, `owner:yourname`).
   - Use the "All resources" view and filters to locate your VM by name, type, or tag.

## Example Steps

1. **Log in to Azure Portal:**  
   [https://portal.azure.com](https://portal.azure.com)

2. **Create a Resource Group:**  
   - Navigate to "Resource groups" > "Create".
   - Name your group and select a region.

3. **Create a Virtual Machine:**  
   - Click "Create a resource" > "Compute" > "Virtual Machine".
   - Fill in the required fields and select your options.
   - Click "Review + create" and then "Create".

4. **Connect to Your VM:**  
   - Go to your VM resource.
   - Click "Connect" and follow the instructions for RDP or SSH.

## Tips

- Choose a VM size that fits your needs and budget.
- Use SSH keys for Linux VMs for better security.
- Always assign your resources to a resource group for easier management.
- Use tags to organize and search for your VMs.

## Resources

- [Azure Virtual Machines Documentation](https://learn.microsoft.com/en-us/azure/virtual-machines/)
- [Quickstart: Create a Linux VM in the Azure portal](https://learn.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-portal)
- [Quickstart: Create a Windows VM in the Azure portal](https://learn.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-portal)
- [Azure Free Account](https://azure.microsoft.com/en-us/free/)
