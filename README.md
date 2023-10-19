<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%"alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<!-- <h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com) -->

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
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<h3 align="center">Configure Roles</h3>
<br />
<p>

</p>
<p>
  Supreme Admin:
</p>
<p>
  <img src="https://github.com/Yosheeda/testpostinstall/blob/main/1.ConfigureRoles1.png?raw=true" height="75%" width="100%" alt="Definitions"/>
  <img src="https://github.com/Yosheeda/testpostinstall/blob/main/1.ConfigureRoles2.png?raw=true" height="75%" width="100%" alt="Permissions"/>
  <img src="https://github.com/Yosheeda/testpostinstall/blob/main/1.ConfigureRoles3.png?raw=true" height="75%" width="100%" alt="More Permissions"/>
  <img src="https://github.com/Yosheeda/testpostinstall/blob/main/1.ConfigureRoles4.png?raw=true" height="75%" width="100%" alt="Even More Permissions"/>
</p>
Admin Panel -> Agents -> Roles.

Supreme Admin:
<br />
<br />
<h3 align="center">Configure Departments</h3>
<br />
<p>

</p>
<p>
  
</p>
<p>
  <img src="https://github.com/Yosheeda/testpostinstall/blob/main/2.Configuredepartments.png?raw=true" height="75%" width="100%" alt="System Administrators"/>
  
</p>
Admin Panel -> Agents -> Departments.

System Administrators:
<br />
<br />
<h3 align="center">Configure Teams</h3>
<br />
<p>
  
</p>
<p>
  Level II Support:
</p>
<p>
  <img src="https://github.com/Yosheeda/testpostinstall/blob/main/3.Configureteams.png?raw=true" height="75%" width="100%" alt="Level II Support"/>
</p>
Admin Panel -> Agents -> Teams.
<br />
<br />
<h3 align="center">Allow anyone to create ticket</h3>
<br />
<p>
 
</p>
<p>
  <img src="https://github.com/Yosheeda/testpostinstall/blob/main/4.Allowanyonetocreateticket.png?raw=true" height="75%" width="100%" alt="ticket creations"/>
</p>
Admin Panel -> Settings -> User Settings.

Make sure "Require registration and login to create tickets" is not selected:
<br />
<br />
<h3 align="center">Configure Agents (workers)</h3>
<br />
<p>
  Admin Panel -> Agents -> Add New.
</p>
<p>
  Jane Doe:
</p>
  <img src="https://github.com/Yosheeda/testpostinstall/blob/main/5.confiureAgents1.png?raw=true" height="75%" width="100%" alt="agent one access"/>
<p>
  John Doe:
</p>
<p>
  <img src="https://github.com/Yosheeda/testpostinstall/blob/main/5.confiureAgents2.png?raw=true" height="75%" width="100%" alt="agent two"/>
  <img src="https://github.com/Yosheeda/testpostinstall/blob/main/5.confiureAgents3.png?raw=true" height="75%" width="100%" alt="agent two access"/>
</p>
<h3 align="center">Configure Users (customers)</h3>
<br />
<p>
  Agent Panel -> Users -> Add New.
</p>
<p>
  Ken User:
</p>
  <img src="https://github.com/Yosheeda/testpostinstall/blob/main/6.configureusers.png?raw=true" height="75%" width="100%" alt="user access"/>
<p>
  Repeat the same above for Karen User.
</p>
<br />
<br />
<h3 align="center">Configure SLA</h3>
<br />
<p>
  Admin Panel -> Manage -> SLA.
</p>
<p>
  Sev-A (1 hour, 24/7).
</p>
<p>
  Sev-B (4 hours, 24/7).
</p>
<p>
  Sev-C (8 hours, business hours):
</p>
<p>
  <img src="https://imgur.com/iEDAviR.png" height="75%" width="100%" alt="sev one"/>
  <img src="https://imgur.com/VUWAyAw.png" height="75%" width="100%" alt="sev two"/>
  <img src="https://imgur.com/z1UfzW5.png" height="75%" width="100%" alt="sev three"/>
</p>
<br />
<br />
<h3 align="center">Configure Help Topics</h3>
<br />
<p>
  Admin Panel -> Manage -> Help Topics.
</p>
<p>
  Business Critical Outage.
</p>
<p>
  Personal Computer Issues.
</p>
<p>
  Equipment Request.
</p>
<p>
  Password Reset.
</p>
<p>
  <img src="https://imgur.com/e3IIzN2.png" height="75%" width="100%" alt="business critical outage"/>
  <img src="https://imgur.com/EgtpYIv.png" height="75%" width="100%" alt="personal computer issues"/>
  <img src="https://imgur.com/IsqwOcU.png" height="75%" width="100%" alt="equipment request"/>
  <img src="https://imgur.com/lcmVwuq.png" height="75%" width="100%" alt="password reset"/>
</p>
<br />
<br />
<p>
  With this we have finally configured osTicket.
</p>
<p>
 
</p>
