<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/QIk0fOY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/vKYseKM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/tJyCXwM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</h2>STEP 1: LOGIN TO OSTICKET AS AN END USER</h2>

  - Go to localhost/osticket/
  - Select "Open a New Ticket"
  - Create three new tickets
  - Karen - Business Critical Outage
  - Ken - Personal Computer Issues
  - Karen - General Inquiry
</p>
<br />

<p>
<img src="https://i.imgur.com/3LTW6SH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
<img src="https://i.imgur.com/ExGX3Me.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</h2>STEP 2: LOGIN TO OSTICKET AS ADMIN</h2>

  - Admin Panel --> Agents --> Jane Doe --> Access --> Select "Support" Dept and make her Supreme Admin for Support --> Save Changes
  - Then Logout of osTicket and sign back in as Jane Doe
  - Now we should be able to view the tickets as Jane Doe
</p>
<br />

<p>
<img src="https://i.imgur.com/ab16Myg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</h2>STEP 3: CONFIGURE TICKET</h2>

  - Select the ticket "Entire mobile banking is down" 
  - Set the priority to "Emergency" and Assign ticket to Jane Doe. 
  - Set SLA to SEV-A 
  - Change the department to Systems Administrators
</p>
<br />
