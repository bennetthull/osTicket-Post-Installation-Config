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

- Configure Roles (for grouping permissions)
- Configure Departments 
- Configure Teams
- Configure Agents and Users
- Configure SLAs and Help Topics (for when users create tickets)

<h2>Configuration Steps</h2>

<p>
<img width="469" alt="Screenshot 2025-01-24 at 9 47 33 AM" src="https://github.com/user-attachments/assets/8578f74a-723d-44e4-b32e-236a94762f16" />
</p>
<p>
I first configured roles by going to the "Roles" section in the Admin Panel. I created a Supreme Admin role that had access to everything. Then I configured departments for ticket visibility (Help Desk vs SysAdmins vs Networking) in the "Departments" section in the Admin Panel. Lastly, I configured teams (so I can pull Agents from different departments) in the "Teams" section in the Admin Panel.
</p>
<br />

<p>
<img width="468" alt="Screenshot 2025-01-24 at 10 11 56 AM" src="https://github.com/user-attachments/assets/8cc6fcc5-e5a0-425d-9f47-3a946093c1f9" />
</p>
<p>
Next I created 2 agents in different departments with different permissions in the "Agents" section of the Admin Panel. Then I created a User in the "Users" section of the Agent Panel. 
</p>
<br />

<p>
<img width="469" alt="Screenshot 2025-01-24 at 10 25 10 AM" src="https://github.com/user-attachments/assets/a7313cec-2099-4916-bb7f-a13efb6c6ae0" />
</p>
<p>
Here I configured SLAs (service level agreements) in the Admin Panel. I set 3 different severity levels and configured their grace periods based on that. Lastly, I generated some help topics in the Admin Panel. 
</p>
<br />
