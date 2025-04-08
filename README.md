<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Creating and Working Tickets</h1>
This tutorial outlines the working of tickets from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Objectives</h2>

- Creating and working tickets as end users
- Observing all the ticket properties and responding to them as help desk professionals

<h2>Creating and Working Ticket Steps</h2>

<p>
<b> Ticket 1 </b>
  
As an end-user, create a ticket. You can create any mock scenario for the lab, I will be using the "Entire mobile/online banking system is down". <br />
1. Open the browser and create the ticket as an end user. We will use the "Karen" account that we created. Fill in "Contact Info", "Help Topic", "Issue Summary" and "Description" sections, then click create ticket. (URL http://localhost/osTicket).  <br />
2. Open a new tab in the browser, login to the osTicket Helpdesk login page as Helpdesk Agent "John". You should notice the new ticket when you login under "Open" tickets (URL http://localhost/osTicket/scp/login.php).
3. Click into the ticket, read the issue summary and description and observe the properties and set these properties to the ticket:
- Update SLA Plan: Choose "Sev-A", as it is a high priority issue. And we will write "Large Impact! Customers unable to do online banking".
- Update Assigned to: Choose "Online Banking". This will assign the ticket to the online banking department.
- Update Help Topic: To "Report a Problem: Business Critical Outage"
When you refresh the ticket info has been updated with the property changes you just made.
4. Log out of the Helpdesk login page. And login in again this time as "Jane". You will see the ticket under "Open" within Tickets. Click into the Ticket and work it to completion as Jane
5. Change Assigned To Property: Jane Doe
6. Go to the Post reply section. I will reply to the ticket with a theory of the probably cause and investgate further to verify that is the cause. I will respond with:
- "I suspect the problem might be related to the recent update. We tested it sufficiently, but I am going to look into it further and roll it back if that caused the issue". Post the reply, refresh the ticket and you should see that it has been updated in the ticket history.
- So in this mock scenario I will pretend I am a helpdesk agent and investigate further. From my investiogation I have verified that the cause was an update that was rolled out overnight which caused the system to go offline.
7. Post another reply:
  - "It was determined that the root cause was the recent update. We rolled it back, notified the vendor and are waiting for a proper fix. Online banking should be up and running". Post the reply.
8. Change Ticket Status to "Resolved" and click close. You should notice that under Open within the Tickets page the table should be empty as it has been moved to "Closed Tickets"
  


</p>
<p>
<img src="https://i.imgur.com/0qRZ4N3.png"/>
<img src="https://i.imgur.com/uFZ987b.png"/>
<img src="https://i.imgur.com/LeB0Djd.png"/>
<img src="https://i.imgur.com/hWCAyzD.png"/>
<img src="https://i.imgur.com/Dny9vYp.png"/>
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
