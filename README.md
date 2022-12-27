<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments and Teams
- Configure Agents and Users
- Configure SLAs (Service Level Agreements)
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/cfcEkZV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Roles

- Admin Panel -> Agents -> Roles
- Supreme Admin
</p>
<br />

<p>
<img src="https://i.imgur.com/eGrZdrg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Departments

- Admin Panel -> Agents -> Departments
- System Administrators

Configure Teams

- Admin Panel -> Agents -> Teams
  - Level I Support
  - Level II Support

<br />

<p>
<img src="https://i.imgur.com/qq68PLp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents (workers)

- Admin Panel -> Agents -> Add New
  - Make up name: e.g. Mark
  - Make up name: e.g. Mary
  
Configure Users (customers)

- Agent Panel -> Users -> Add New
  - Make up name: e.g. Sam
  - Make up name: e.g. Sara
</p>
<br />

<p>
<img src="https://i.imgur.com/g8ptsmN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLAs (Service Level Agreements)

- Admin Panel -> Manage -> SLA
  - Sev-A (1 hour, 24/7)
  - Sev-B (4 hours, 24/7)
  - Sev-C (8 hours, business hours)

</p>
<br />

<p>
<img src="https://i.imgur.com/CLjEuiI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics

- Admin Panel -> Manage -> Help Topics
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset
</p>
<br />
