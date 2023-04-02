# post-install-config
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

- Create Role
- Create Departments
- Create Teams
- Create Agents
- Create Users
- Configure Service Level Agreemnets(SLA)
- Create Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/x5Bc2Qd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Begin by creating an IT Manager role. Go to the Admin Panel then click on Agents> Roles> Add New Role. Enter name "IT Manager". Click on permissions and filter throught the tabs Tickets, Tasks, and Knowledgebase. Check all boxes to give your IT Manager full organizational access.
</p>
<br />

<p>
<img src="https://i.imgur.com/MWk4F6r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next create a department. Go to Admin Panel then click on Agents> Departments> Add New Department. Name department System Administrators
</p>
<br />

<p>
<img src="https://i.imgur.com/sea5f1c.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a team. Admin Panel then click on Agents> Teams> Add New Team. Name team Level 2 Support. Add Yourself(or created User) as a team member. Now allow anyone to create tickets. Stay in Admin Panel click Settings> Users> check Registration Required.(From this screen you can also set excessive log in and minutes locked rules)
</p>
<br />

<p>
<img src="https://i.imgur.com/sDmanlc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next step is creating Agents in the system. Stay in Admin Panel click on Agents> Add New Agent. Create a name, email, and username. Then set password. Uncheck password reset email and require password change at next login. click Set
</p>
<br />

<p>
<img src="https://i.imgur.com/3yFbk9x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now create the users. Click on Agent Panel> Users> Add Users. Create two users.
</p>
<br />

<p>
<img src="https://i.imgur.com/NiM6eYZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure the SLAs. Go back to the Admin Panel> Manage> SLA> Add New SLA Plan. Creat 3 different SLA plans. Sev-A, Sev-B, Sev-C. Set the Grace Period to Sev-A=1, Sev-B=4, Sev-C=8.
</p>
<br />
                                                                                                 
<p>
<img src="https://i.imgur.com/LeSX8IQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics. Go to Admin Panel> Manage> Help Topics> Add New Help Topic. Create four topics. Business Critical Outage, Equipment Request, Personal Computer Issues, Password Reset. Post Install Complete,
</p>
<br />

                                                                                            
