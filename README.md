<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/results?search_query=How+To+Configure+osTicket%2C+post-installation)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/mwn1RnK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Roles
Admin Panel -> Agents -> Roles
Supreme Admin
Roles as shown above
so we can creat new roles and set permissions and tasks for it..
</p>
<br />

<p>
<img src="https://i.imgur.com/2mnldiC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Departments
Admin Panel -> Agents -> Departments
System Administrators

</p>
<br />

<p>
<img src="https://i.imgur.com/fgEBwD8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams
Admin Panel -> Agents -> Teams
Level I Support
Level II Support

</p>
<br />
<p>
<img src="https://i.imgur.com/7dEiC8r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allow anyone to create tickets
Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets

</p>
<p>
<img src="https://i.imgur.com/ojpjaNg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane,
John.
and assign them to teams..
</p>
<p>
<img src="https://i.imgur.com/6rxKzRG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Users (customers)
Agent Panel -> Users -> Add New
Karen,
Ken

</p>
<p>
<img src="https://i.imgur.com/OoGOYWY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)

</p>
<p>
<img src="https://i.imgur.com/uvJN3N5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset

</p>

