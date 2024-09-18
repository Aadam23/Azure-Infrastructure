<h1>Azure-Infrastructure</h1>
<b>Virtual Network (VNet)</b>
<br />
<br />

<p>This project demonstrates the creation of a basic cloud infrastructure using <b>Microsoft Azure</b>. It involves setting up a Virtual Network (VNet), creating Subnets, configuring Network Security Groups (NSGs) to control traffic, and deploying a Virtual Machine (VM). The infrastructure is designed to simulate a small-scale cloud environment suitable for web hosting, testing, or learning.</p>



<h2>Overview</h2>
<p>This project focuses on creating a small-scale cloud infrastructure using Microsoft Azure. It demonstrates the implementation of a Virtual Network (VNet) with subnets, Network Security Groups (NSGs) for traffic control, and the deployment of a Virtual Machine (VM) within the network.
By configuring this setup, I was able to simulate a secure and scalable cloud environment, which can be used for basic server hosting or web application deployment. I also configured security rules to manage network traffic, ensuring safe access via RDP and SSH.</p>


<h2>Architecture Diagram</h2>
<p align="center"><img width="956" alt="Screenshot 2024-09-18 at 3 47 14 PM" src="https://github.com/user-attachments/assets/46890678-90bc-41a7-a9f0-eaaf4f989a73"></p>
<br>
<br>


<h2>Architecture</h2>

The architecture consists of:
- **Virtual Network (VNet)**: A network to manage traffic and connectivity between Azure resources.
- **Subnets**: A segmentation of the VNet for better security and organization.
- **Network Security Group (NSG)**: A firewall that controls inbound and outbound traffic.
- **Virtual Machine (VM)**: A cloud-based server running either Windows or Linux.
<br />


<h2>Utilities and Tools Used</h2>

- <b>Azure Portal:</b> Central hub for managing and configuring Azure services, such as Azure Functions, Cosmos DB, and Storage Accounts.
- <b>Azure Resource Group:</b> A container that holds related resources for an Azure solution, simplifying resource management and organization.

- <b>Virtual Network (VNet):</b> To create a secure and isolated network for your Azure resources. It allows different Azure services to communicate with each other securely. The VNet is where the VM resides and operates.
- <b>Subnet:</b> A sub-segment of the VNet to organize and isolate resources further. It helps in grouping resources logically and applying policies at a finer level.
- <b>Network Security Group (NSG):</b> To control the inbound and outbound traffic to resources in your Azure VNet. The NSG acts as a firewall, enforcing rules for traffic based on the source, destination, and protocol.
- <b>Virtual Machine (VM):</b> To host a web server or other applications. The VM is the central compute resource that you access remotely, configure, and run services on.
- <b>Public IP Address:</b> Assigned to the VM to allow external access via the internet. This IP address is used for RDP or SSH connections and for hosting web content if necessary.
- <b>Remote Desktop Protocol (RDP)/ Secure Shell (SSH):</b> To connect to and manage your VM. RDP is used for connecting to Windows VMs, while SSH is used for Linux VMs.
- <b>Azure Monitor:</b> To track the performance and health of your resources, such as the VM and network. It helps you monitor usage, set up alerts, and log activities for troubleshooting.
- <b>Azure Network Watcher:</b> Provides insights into the networking aspect of your project. It monitors the flow of traffic and helps in diagnosing network issues.
<br />

<h2>Objectives</h2>
- Set up and configure a Virtual Network (VNet) and Subnets.
- Create and associate a Network Security Group (NSG) with appropriate rules.
- Deploy and configure a Virtual Machine (VM) within the VNet.
- Securely connect to the VM via RDP or SSH.
<br />
<br />

<h2>Steps</h2>

1. **Create a Virtual Network (VNet)** with subnets for organizing the network structure.
2. **Configure Network Security Group (NSG)** to manage traffic rules, allowing RDP/SSH access.
3. **Deploy a Virtual Machine (VM)** with a public IP address for remote access.
4. **Test connectivity** by accessing the VM using RDP (Windows) or SSH (Linux).
<br />
<br />



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
</html>
