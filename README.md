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

- Create a Domain Controller and Client VM
- Add Client to Domain
- Step 3
- Running IP Config to see changes made to the Client VM after being added to the domain

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/PVz5YZI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We set up our Domain Controller ruuning Windows Server 22 and the Client VM running Windows 10 PRO. Once that was completed, we then configured and enabled
our Remote Desktop so that we could log into both our VMs to begin the lab.
</p>
<br />

<p>
<img src="https://i.imgur.com/gwQf85A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
DNS Servers
</p>
<br />

<p>
<img src="https://i.imgur.com/Os1qnVJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
IP Config
</p>
<br />
