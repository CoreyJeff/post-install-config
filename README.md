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

- Step 1: Configure Roles
- Step 2: Configure Departments
- Step 3: Configure Teams
- Step 4: Allow anyone to create tickets 
- Step 5: Configure Agents
- Step 6: Configure Users
- Step 7: Configure SLA
- Step 8: Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/CoreyJeff/post-install-config/assets/138095936/f2bfee13-8607-4322-9afe-4aaff410f5d8"/>



</p>
<p>
Step 1: Log in to osTicket from the Virtual Machine and from the home page go to the Admin Panel in the upper right corner then go to the Agents Tab and Roles. Add a new role and name it Supreme Admin and go to the Permissions tab next to it and check all the boxes including the (Tasks and Knowledgebase) boxes too.
</p>
<br />

<p>
<img src="https://github.com/CoreyJeff/post-install-config/assets/138095936/38ec5d9e-9533-4b1f-9e9a-ec637e810ce7"/>
"/>
</p>
<p>
Step 2: From the Agents Tab go to Departments and add a new department and name it (System Administrators) and create with the default settings.
</p>
<br />

<p>
<img src="https://github.com/CoreyJeff/post-install-config/assets/138095936/846edaf5-f25d-478c-8169-448dca746c01"
"/>
</p>
<p>
Step 3: You should already be in the Agents tab from there go to Teams and add a new team. Name the team (Level 2 Support) and add the team and add yourself to the team.
</p>
<br />

<p>
<img src="https://github.com/CoreyJeff/post-install-config/assets/138095936/0d543117-cb76-44a4-8367-be4dbe796c0b"
"/>
</p>
<p>
Step 4: Go to settings but make sure you are in the Admin Panel and go to Users and uncheck the Registration Required box.
</p>
<br />

<p>
<img src="https://github.com/CoreyJeff/post-install-config/assets/138095936/bc4bc334-111b-468c-8b3d-c691a36dfede"
"/>
</p>
<p>
Step 5: Go to the Agents Tab and add a new agent. You are going to name this Agent (Jane Doe) and the email will be (jane.doe@osticket.com) and username will be (jane.doe) make the password something easy to remember and uncheck both boxes. Go over one tab to the Access section and set the department and role to the two you just created. Which would be (System Administrators and Supreme Admin). Go to the Teams Tab and change it to the (Level 2 Support Team) and create. Add one more Agent and name him (John Doe) and repeat the steps but this time you will be adding it to the Support Department and a View Only Role and for Extended Access it should be Support too.
</p>
<br />

<p>
<img src="https://github.com/CoreyJeff/post-install-config/assets/138095936/018be898-11ca-4915-ac87-9ae5331e3f71"
"/>
</p>
<p>
Step 6: Switch from the Admin Panel to Agent in the upper right corner and go to the Users Tab and add a new user. You are going to name this user (Karen Karen) and the email will be (karen@osticket.com). Add another user and repeat the steps but name it (Ken).
</p>
<br />

<p>
<img src="https://github.com/CoreyJeff/post-install-config/assets/138095936/d1e303a7-8b2a-4f3a-9304-01b3851c56fb"
"/>
</p>
<p>
Step 7: Go back to the Admin Panel in the upper right and go to the Manage Tab and click SLA. Add a new SLA Plan and name it Sev-A keep the Grace Period at 1hr and change the Schedule to 24/7 and create. Add anthother SLA and name it Sev-B change the Grace Period to 4 hrs and the Schedule to 24/7. Create one more SLA plan and name it Sev-C and make the Grace Period 8hrs and the Schedule Buisness Hours and create.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 8: Stay in the Manage panel and go to Help topics right under the Dashboard Tab. Add a Help Topic and name it Buisness Critical Outage and add. Add one more and name it Personal Computer Issues and save the changes.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
These were the main post installation configuration steps. Now you should be ready to play around in the app as a Agent and a User and learn how to create and resolve tickets from customers. I hope this really helped you out
</p>
<br />
