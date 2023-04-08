<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

1 - Configure Roles
2 - Configure Departments
3 - Configure Teams
4 - Configure Agents
5 - Configure Users
6 - Configure SLA

<h2>Configuration Steps</h2>

1 - Configure Roles
<p> 
<img src="https://i.imgur.com/S7Tpfi0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, go to Admin Panel, click on Agents tab, click on Roles tab, enter name (Supreme Admin) in "Definition" tab, then go to the Permissions tab, select the necessary permissions in the Tickets tab.  Then, go to the Tasks tab and select the necessary tasks.  Finally, go to the Knowledgebase tab, select premade, and click "Add Role".
</p>
<br />

2 - Configure Departments
<p>
<img src="https://i.imgur.com/3Af13VK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Second, go to Admin Panel, click on Agents tab, click on Departments, enter name (System Administrators) under "Department Information", scroll to the bottom and click *Creat Dept.    
</p>
<br />

3 - Configure Teams
<p>
<img src="https://i.imgur.com/Tw9BRoN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, go to Admin Panel, click on Agents tab, click on Teams tab, then click Add New Team, and enter name under Team Information.  Then, click on Members tab, Select Agent, and click Create Team.
</p>
<br />

4 - Configure Agents
<p>
<img src="https://i.imgur.com/Ip1UEvj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Admin Panel, click on Agents tab, click on Agent (sub) tab, then click Add New Agent, and enter email and name under "Account Tab". Go to "Access Tab", Select Department and Select Role in Primary Department, and then go to "Teams Tab" and Select Team.  Add the team and and create.
</p>
<br />

<p>
<img src="https://i.imgur.com/fwQEtJm.png" height="80%" width="80%" alt="Disk Sanitization Step"/>
</p>
<p>
Go to Agent Portal, click on Users tab and click Add User.  Enter email address and full name, then click add user.   
</p>
<br />

5 - Configure SLA
<p>
<img src="https://i.imgur.com/mzsJ0TD.png" height="80%" width="80%" alt="Disk Sanitization Step"/>
<img src="https://i.imgur.com/W9ozkun.png" height="80%" width="80%" alt="Disk Sanitization Step"/>
<p>
Go to Admin Panel, click on Manage tab, click SLA, and click on Add New SLA Plan.  Next, Update SLA Plan: create name, add Grace Period, and select Schedule; click Add Plan.
</P>
<br />

<p>
<img src="https://i.imgur.com/EEvh889.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Configure Help Topics. While in the "Admin Panel", click "Manage" -> "Help Topics" -> "Add New Help Topic". Name the topic "Business Critical Outage", and leave the parent topic as is. Repeat the steps and create more help topics named "Personal Computer Issues", "Equipment Request", and "Password Reset". The osTicket post-installation steps are now complete. 
</p>
<br />

