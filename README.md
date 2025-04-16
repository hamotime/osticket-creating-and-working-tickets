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
<b> TICKET 1 </b>
  
As an end-user, create a ticket. You can create any mock scenario for the lab, My scenario is: 

"The Entire mobile/online banking system is down for a company".

1. Open a browser and create a ticket as an end user (URL http://localhost/osTicket). We will use the "Karen" account. Fill in the following sections and click create ticket:
- Contact Info
- Help Topic
- Issue Summary
- Description sections

2. Open a new tab in the browser, login to the osTicket Helpdesk login page as Helpdesk Agent "John". You should notice the new ticket when you login under "Open" tickets (URL http://localhost/osTicket/scp/login.php).
3. Click into the ticket, read the issue summary and description and observe the properties and set these properties to the ticket:
- Update SLA Plan: Choose "Sev-A", as it is a high priority issue. And we will write "Large Impact! Customers unable to do online banking".
- Update Assigned To: Choose "Online Banking". This will assign the ticket to the online banking department.
- Update Help Topic: "Report a Problem: Business Critical Outage". Include the note: "No customers able to access online banking!" When you refresh the ticket you will see the ticket history has been updated with the changes you made.
4. Log out of the Helpdesk login page. Re-login with the "Jane" account. You will see the ticket under "Open" within "Tickets". Click into the ticket and work it to completion as Jane.
5. Change "Assigned To" property: Jane Doe
6. Go to the Post reply section. I will reply to the ticket with a theory of the probable cause and investgate further to verify if this is the cause. I will respond with:
- "I suspect the problem might be related to the recent update. We tested it sufficiently, but I am going to look into it further and roll it back if that caused the issue". Post the reply, refresh the ticket and you should see that it has been updated in the ticket history.
- In this mock scenario I will pretend I am a helpdesk agent and take the next step and investigate further. I discover and verify that the cause was an update that was rolled out overnight which caused the system to go offline.
7. Post another reply in the ticket:
  - "It was determined that the root cause was the recent update. We rolled it back, notified the vendor and are waiting for a proper fix. Online banking should be up and running". Post the reply. You will notice in the ticket history all of the changes that were made by "Jane" and "John"
8. Change Ticket Status to "Resolved" and click close. You should notice that under "Open" within the "Tickets" page the table should be empty as it has been moved to "Closed" within "Tickets".
</p>
<p>
<img src="https://i.imgur.com/0qRZ4N3.png" height="80%" width="80%" alt="Ticket 1 Steps"/>
<img src="https://i.imgur.com/uFZ987b.png" height="80%" width="80%" alt="Ticket 1 Steps"/>
<img src="https://i.imgur.com/LeB0Djd.png" height="80%" width="80%" alt="Ticket 1 Steps"/>
<img src="https://i.imgur.com/hWCAyzD.png" height="80%" width="80%" alt="Ticket 1 Steps"/>
<img src="https://i.imgur.com/Dny9vYp.png" height="80%" width="80%" alt="Ticket 1 Steps"/>
<img src="https://i.imgur.com/3eir3Gb.png" height="80%" width="80%" alt="Ticket 1 Steps"/>
<img src="https://i.imgur.com/Kxlw3r3.png" height="80%" width="80%" alt="Ticket 1 Steps"/>
<img src="https://i.imgur.com/TYngNLg.png" height="80%" width="80%" alt="Ticket 1 Steps"/>
<img src="https://i.imgur.com/bIMoRxh.png" height="80%" width="80%" alt="Ticket 1 Steps"/>
<img src="https://i.imgur.com/07yzoCF.png" height="80%" width="80%" alt="Ticket 1 Steps"/>
<img src="https://i.imgur.com/54NoWxR.png" height="80%" width="80%" alt="Ticket 1 Steps"/> 
<img src="https://i.imgur.com/ASHYYER.png" height="80%" width="80%" alt="Ticket 1 Steps"/>
<img src="https://i.imgur.com/SjZawnx.png" height="80%" width="80%" alt="Ticket 1 Steps"/>
<img src="https://i.imgur.com/5nu0wFP.png" height="80%" width="80%" alt="Ticket 1 Steps"/>
<img src="https://i.imgur.com/GqKtZml.png" height="80%" width="80%" alt="Ticket 1 Steps"/>
<img src="https://i.imgur.com/nYmxA08.png" height="80%" width="80%" alt="Ticket 1 Steps"/>
</p>
<br />

<p>
<b> TICKET 2 </b>

Ticket Scenario: "The Accounting department needs an adobe upgrade, broken?". I purposely made the issue summary vague which require us to get clarification when working the ticket

1. Create a ticket as an end user (URL http://localhost/osTicket). We will use "Ken" this time. Fill out the form, if uncertain refer to Step 1 in Ticket 1.
2. Login to the Helpdesk login page as John. You will see the newly created ticket, click into it and observe the issue and it's properties.
- When reading the issue you can notice the issue title and explaination are conflicting. The adobe software might not need to be upgraded it just can't be used for whatever reason. This requires us to investigate further. In this mock scenario I reply to Ken and ask "What exactly do you mean by many people in the accounting department can't use their adobe software"? I pretend he has contacted me back stating "Only 2 people in the account department are unable to use Adobe Reader". Clarification here has allowed us to specifically identify the problem. We can proceed to the next step.
3. In ticket, Update "SLA Plan" property. Change to Sev-C and I will include the note: "2 people in the accounts department are unable to open Adobe Reader."
4. In ticket, Update "Assigned To" property. Change to "John Doe". We will take the ticket to completion as only John this time.
5. Post a Reply to the ticket. "Customer states only 2 people in the accounting department are unable to open and use Adobe reader. I have asked the customer to conduct restarts, he will call back after lunch."
  - I will pretend lunch has finished, the customer got back to me and said the restart worked and there are no problems anymore.
6. Post a Reply to the ticket. "Customer states that restart fixed issue for both users".
7. Change ticket Status to "Resolved" and include note: "Restart fixed the issue for both user." Click close. The Open tickets section should be empty as the ticket has been moved to close. In my screenshot you will see a ticket called "osTicket Installed!" You can ignore this as it was the default ticket created when installed osTicket ticket. 
</p>
<p>
<img src="https://i.imgur.com/sL7rFBF.png" height="80%" width="80%" alt="Ticket 2 Create Ticket"/>
<img src="https://i.imgur.com/1Ggnhuf.png" height="80%" width="80%" alt="Ticket 2 Update SLA Plan"/>
<img src="https://i.imgur.com/T7yk4ba.png" height="80%" width="80%" alt="Ticket 2 Update Assigned To"/>
<img src="https://i.imgur.com/ftyRPgO.png" height="80%" width="80%" alt="Ticket 2 Post a Reply 1"/>
<img src="https://i.imgur.com/Tk3g2zc.png" height="80%" width="80%" alt="Ticket 2 History Screenshot"/>
<img src="https://i.imgur.com/gTsekfa.png" height="80%" width="80%" alt="Ticket 2 Resolved 1"/>
<img src="https://i.imgur.com/3yuQaaj.png" height="80%" width="80%" alt="Ticket 2 Resolved 2"/>
<img src="https://i.imgur.com/0xUq5KJ.png" height="80%" width="80%" alt="Ticket 2 Open Tickets Empty"/>
</p>
<br />

<p>
<b> TICKET 3 </b>

Ticket Scenario: "CFO's laptop will no longer turn on" with explanation: "Laptop won't power on when pressing the power button."

1. Create a ticket as an end user (URL http://localhost/osTicket). We will use "Karen" this time. Fill out the form, if uncertain refer to Step 1 in Ticket 1.
2. Login to the Helpdesk page as John and open the ticket (URL http://localhost/osTicket/scp/login.php).
3. Change the following properties:
- Priority: High (I didn't change this property in the previous tickets as I have already defined SLAs for priority. Showing this option for the purpose of the lab.)
- SLA Plan: Sev-B with note "May re-classify after getting more info."
- Assigned To: John
4. As we are dealing with the CFO in this mock scenario. I might call the CFO or Karen directly and ask if they want me to come over to have a look at the laptop. I will pretend that I called Karen and she said I can go and have a look at the laptop and troubleshoot. Using troubleshooting methodology I determine that the issue is the power adapter not charging the battery. I request a replacement power adapter, the battery now charges and the laptop turns on.
5. Post a Reply to the ticket. "CFO's laptop was not charging due to faulty charger, purchased new charger, now successfully charging".
6. Change Ticket to "Resolved" and include note "Charger was faulty and could not charge the dead battery". Close ticket.
</p>
<p>
<img src="https://i.imgur.com/kl3Xdil.png" height="80%" width="80%" alt="Ticket 3 Steps"/>
<img src="https://i.imgur.com/q8RzcBU.png" height="80%" width="80%" alt="Ticket 3 Steps"/>
<img src="https://i.imgur.com/C2UlYSQ.png" height="80%" width="80%" alt="Ticket 3 Steps"/>
<img src="https://i.imgur.com/ZrO9B1q.png" height="80%" width="80%" alt="Ticket 3 Steps"/>
<img src="https://i.imgur.com/6LOB0rX.png" height="80%" width="80%" alt="Ticket 3 Steps"/>
<img src="https://i.imgur.com/WV7wfk2.png" height="80%" width="80%" alt="Ticket 3 Steps"/>
<img src="https://i.imgur.com/ZMzRb0A.png" height="80%" width="80%" alt="Ticket 3 Steps"/>
<img src="https://i.imgur.com/GXVuhS3.png" height="80%" width="80%" alt="Ticket 3 Steps"/>
<img src="https://i.imgur.com/9PReolw.png" height="80%" width="80%" alt="Ticket 3 Steps"/>
<img src="https://i.imgur.com/CTRE5XW.png" height="80%" width="80%" alt="Ticket 3 Steps"/>
</p>
<br />
