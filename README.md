<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial provides a guide to the post-installation setup of the open-source help desk ticketing system, osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h1>STEPS FOR OSTICKET POST-INSTALLATION CONFIGURATIONS</h1>
<h2>1. Configure Role: "Supreme Admin"</h2>
Set up a role named “Supreme Admin” and grant it every permission for both tickets and tasks.<br>
<br>Role: A role defines a set of permissions and responsibilities assigned to a user or group within the system.

<h2>2. Create Department: "SysAdmins"</h2>
Configure a “SysAdmins” department that will later be assigned to future agents.<br>
<br>Department: A department is a group or category used to organize tickets based on specific areas of support or business functions.

<h2>3. Create Team: "Online Banking"</h2>
Set up a team called “Online Banking”, which will be assigned to specific agents across different departments.<br>
<br>Teams: A team is a group of agents assigned to manage and resolve tickets within a specific department or across multiple departments.

<h2>4. Add Agents: Jane Doe and John Doe</h2>
Configure two agents, Jane Doe and John Doe, and assign each agent to a different department: one to the SysAdmins department and the other to the Support department.<br>
<br>Agent: An agent is a user responsible for managing and responding to support tickets. Agents are assigned to specific departments or teams to handle tasks.

<h2>5. Configure User: Ken</h2>
Set up a user named Ken within the agent panel to submit tickets and interact with support staff.<br>
<br>User: A user is a person who submits support tickets to request assistance or report issues.

<h2>6. Define SLAs</h2>
Configure three different SLAs (Service Level Agreements) based on severity levels, and assign different grace periods and schedules for response and resolution times.<br>
<br>SLA: SLAs define the expected response and resolution times for support tickets based on predefined rules and priorities.

<h2>7. Set Up Help Topics</h2>
Configure various help topics to guide users in selecting the appropriate category for their support tickets.<br>
<br>Help Topics: Help topics are predefined categories that help users select the correct subject for their support tickets, improving ticket organization.

<h2>8. Assign SLAs to Tickets and Help Topics</h2>
Link the configured SLAs and help topics to specific ticket types and user submissions to ensure that tickets are routed correctly and handled according to defined service levels.
