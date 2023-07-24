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

- Ensure connectivity between the two Virtual machines and install Active Directory 
- Create an Admin/Normal user account in Active Directory 
- Setup Virtual machines for non-administrative user and create additional user
  

<h2>Deployment and Configuration Steps</h2>

<p>

</p>
<p>
Firstly, we will login into client-1 of our remote desktop and ping the second Virtual Machine(DC-1's) private IP. Generating a perpetual ping and enable ICMPv4 in the firewall of DC-1(Domain Controller), logging back in and installing Active Directory Domain Services. Set up a new forset and restart and log back into DC-1. 
</p>
<br />

<p>

</p>
<p>
Afterwards, in Active Directory users and computers we'll create organizaton units. Setting up the DNS settings for Client-1 through the Azure portal, logging back in with the admin user(labuser) as before. 
</p>
<br />

<p>

</p>
<p>
Lastly we will setup remote desktop for Non-administrative user, additionally creating more users and attempt to log into client-1 as one of the user. 
</p>
<br />
