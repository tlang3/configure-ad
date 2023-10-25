<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create Domain Controller VM and Client VM in Azure
- Use same resource group for both VMs
- Ensure both VMs are in same Vnet
- Ensure connectivity between Client VM and Domain Controller VM
- Install Active Directory
- Create an Admin and Normal User account in AD
- Join Client VM to your domain
- Setup Remote Desktop for non-admin users on Client VM
- Create additional users and attempt to login to Client VM with one of the users


<h2>Deployment and Configuration Steps</h2>

1. Create Domain Controller VM and Client VM in Azure

   ![Screenshot (7)](https://github.com/meganhoose/configure-AD/assets/142938638/46b103a5-14aa-47d4-b586-799c640a498c)


2. Use same resource group for both VMs


3. Ensure both VMs are in the same Vnet


4. Install Active Directory

   
![start to install active directory](https://github.com/meganhoose/configure-AD/assets/142938638/ec352f27-c614-43bc-9fa8-194dd8be6070)



5. Create an Admin and Normal User account in AD

   ![create jane doe admin](https://github.com/meganhoose/configure-AD/assets/142938638/0243d0ec-9f02-4239-abcd-400fa2b77027)


6. Join Client VM to your domain

   ![join client-1 to the domain](https://github.com/meganhoose/configure-AD/assets/142938638/fc7c4086-25df-4d6a-9d0a-57631c2a12b4)


7. Setup Remote Desktop for non-admin users on Client VM


8. Create additional users and attempt to login to Client VM with one of the users

   ![login to client one with random user bal qer](https://github.com/meganhoose/configure-AD/assets/142938638/54d4270a-4171-4277-8296-b36c0f6846a0)


