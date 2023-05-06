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

- Connect to the osTicket VM remotely
- Customize the user roles, permissions, and access levels according to your organization's needs
- Create departments and teams for efficient ticket management and collaboration among agents
- Add new agents, assign them to relevant departments and teams, and provide appropriate roles and access permissions
- Create new help topics for different types of issues that customers may face while using your product/service

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/zTYBEg1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The given steps describe the process of creating and resolving support tickets using the osTicket platform. Initially, three tickets are created for different issues, including a business critical outage, personal computer issues, and a general inquiry about a hardware refresh. The tickets are created by providing specific user information, help topics, and issue summaries.
</p>
<br />

<p>
<img src="https://i.imgur.com/XjwBvGq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, the user logs in as an agent and admin to manage and modify access settings for the agent. This involves selecting the appropriate department and role, such as Support and Supreme Admin, and saving the changes. Afterward, the agent logs in again to address the tickets, updating their priority levels, assigning them to agents, and changing their departments as needed.
</p>
<br />

<p>
<img src="https://i.imgur.com/3JD9JSA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For the business critical outage ticket, the agent coordinates with the System Admin team to resolve the issue. The agent updates the ticket with the steps taken to fix the problem, marking it as resolved and transferring it to the Closed tab. Similarly, for the personal computer issues ticket, the agent assigns the ticket to another agent, who then takes the necessary steps to resolve the issue.
</p>
<br />

<p>
<img src="https://i.imgur.com/SL7AKHF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the general inquiry ticket, the agent provides information about the hardware refresh, assigns the ticket to themselves, and marks it as resolved. The agent then logs out and logs in as another agent, who reviews the personal computer issues ticket and updates it with an internal note describing the resolution. The agent logs in as an admin to modify access settings for department members.
</p>
<br />

<p>
<img src="https://i.imgur.com/x8u9vRn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, the agent logs in as another user to resolve the personal computer issues ticket, updating the ticket status and posting a reply. The agent then reviews the Closed tab to confirm the ticket's resolution.
</p>
<br />
