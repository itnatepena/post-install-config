<h1>Configuring osTicket for Efficient Ticket Management</h1>
This guide illustrates the necessary steps to configure osTicket as a reliable ticketing system for streamlined ticket management.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- osTicket 

<h2>Operating Systems Used</h2>

- Windows 10 Pro (21H2)

<h2>Configuration Steps</h2>

<p>
After installing osTicket, the next phase involves essential configurations to transform it into an effective ticketing system. It's important to note that I'll switch between the Admin and Agent panels, as each panel offers different configurations. To distinguish between them, look at the top right corner of the osTicket screen. If it reads "Agent Panel," I'm using the Admin panel, and vice versa.
</p>

<p>
The first step is to create a new role called "Supreme Admin." While this lab intentionally creates a role with extensive permissions, it's crucial to adapt this to your specific needs. To create this role:
</p>

<p>
1. In the Admin panel, navigate to the Agents menu.
2. Click on "Roles" and create the new role from there.
</p>

<p>
Next, a new department will be created for System Administrators:
</p>

<p>
1. In the Admin panel, go to the Agents menu.
2. Click on "Departments" to create a new department within osTicket.
</p>

<p>
A new Level II Support Team should be created to complement the Level I Support Team established earlier in osTicket:
</p>

<p>
1. In the Admin panel, visit the Agents menu.
2. Click on "Teams" and add any new teams that need to be created.
</p>

<p>
New agents will have to be created to handle incoming tickets:
</p>

<p>
1. In the Admin panel, access the Agents menu.
2. Click on "Add New Agent" and create the credentials for each new agent. For instance, Jane and John Doe are created in this lab.
</p>

<p>
New users will also be created to submit tickets for agents to handle:
</p>

<p>
1. In the Agents panel, open the Users menu.
2. Click on "Add User" and provide the necessary account credentials for each new user. In this case, Karen and Ken have been created.
</p>

<p>
Service Level Agreements (SLAs) will need to be established to categorize tickets based on their level of impact:
</p>

<p>
1. In the Admin panel, go to the Manage menu.
2. Click on "SLA" and create any needed SLAs. In this case, SEV-A, B, and C are created to categorize tickets requiring resolution within 1 hour, 4 hours, and 8 hours, respectively.
</p>

<p>
Finally, Help Topics should be created to assist users in selecting an appropriate category that describes their problem:
</p>

<p>
1. In the Admin panel, navigate to the Manage menu.
2. Click on "Help Topics" and then "Add New Help Topic." In this case, I've added categories like Business Critical Outage, Personal Computer Issues, Equipment Reset, and Password Request.
</p>

<h2>osTicket Configurations are Complete</h2>

Now that the configurations have been implemented, osTicket is ready to serve as a robust ticketing system. You can create, manage, and prioritize tickets, providing an effective solution for ticket management.
