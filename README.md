<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
<h1>Configuring osTicket for Efficient Ticket Management</h1>

## Project Summary

This guide illustrates the configuration of osTicket, a robust ticketing system, with a focus on ensuring efficient ticket management.

- **Languages Used:** N/A (Configuration guide for osTicket).
- **Environments Used:** Microsoft Azure (Virtual Machines/Compute) for hosting the Windows 10 Pro virtual machine.
- **Technology/Applications/Services Used:** Microsoft Azure, Remote Desktop Connection, and osTicket.

## Technologies Used

- **Operating System:** Windows 10 Pro (21H2).

<h2>Configuration Steps</h2>

<p>
After installing osTicket, the next phase involves essential configurations to transform it into an effective ticketing system. It's important to note that I'll switch between the Admin and Agent panels, as each panel offers different configurations. To distinguish between them, look at the top right corner of the osTicket screen. If it reads "Agent Panel," I'm using the Admin panel, and vice versa.

![image](https://github.com/itnatepena/post-install-config/assets/147539410/d156d596-cbe2-45b6-aed2-3fce62e7dba6)

</p>

<p>
The first step is to create a new role called "Supreme Admin." While this lab intentionally creates a role with extensive permissions, it's crucial to adapt this to your specific needs. To create this role:
</p>

<p>
1. In the Admin panel, navigate to the Agents menu.
2. Click on "Roles" and create the new role from there.
</p>

![image](https://github.com/itnatepena/post-install-config/assets/147539410/3b52923b-382e-40c2-a68a-86b012179b71)

<p>
Next, a new department will be created for Huamn Resources:
</p>

<p>
1. In the Admin panel, go to the Agents menu.
2. Click on "Departments" to create a new department within osTicket.

![image](https://github.com/itnatepena/post-install-config/assets/147539410/feabc4a3-9f5a-4d53-89c4-1a20175474b4)

</p>

<p>
A new Level II Support Team should be created to complement the Level I Support Team established earlier in osTicket:
</p>

<p>
1. In the Admin panel, visit the Agents menu.
2. Click on "Teams" and add any new teams that need to be created.

Here we added the "Level II Support team" to compliment Level I support.
  
![image](https://github.com/itnatepena/post-install-config/assets/147539410/c543a659-51ae-49e6-ad7f-2f7a5052fb41)

</p>

<p>
New agents will have to be created to handle incoming tickets:
</p>

<p>
1. In the Admin panel, access the Agents menu.
2. Click on "Add New Agent" and create the credentials for each new agent. For instance, Jane and John Doe are created in this lab.
  
![image](https://github.com/itnatepena/post-install-config/assets/147539410/86e326c2-c7f2-44e3-be0a-be55bb1388bf)

</p>

<p>
New users will also be created to submit tickets for agents to handle:
</p>

<p>
1. In the Agents panel, open the Users menu.
2. Click on "Add User" and provide the necessary account credentials for each new user. In this case, Karen and Ken have been created.

![image](https://github.com/itnatepena/post-install-config/assets/147539410/5143ab0d-c697-4ec2-8b95-9ae494ca19fb)

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
  
![image](https://github.com/itnatepena/post-install-config/assets/147539410/7346b4f5-ed76-4c7e-a78b-95baf42e12c2)

![image](https://github.com/itnatepena/post-install-config/assets/147539410/20ba73ea-e3c1-469c-8bca-3e450e4973e4)



</p>

<h2>osTicket Configurations are Complete</h2>

Now that the configurations have been implemented, osTicket is ready to serve as a robust ticketing system. You can create, manage, and prioritize tickets, providing an effective solution for ticket management.
