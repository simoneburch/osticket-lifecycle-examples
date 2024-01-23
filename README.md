<p align="center">
<img src="https://github.com/simoneburch/osticket-lifecycle-examples/assets/152559137/c76d9b83-23ad-4672-8cf6-cb3d7117d47f" height="50%" width="50%" alt="osTicket graphic"/>
</p>

<h1 align="center">
osTicket - Ticket Lifecycle: Intake Through Resolution</h1>

__This demonstration outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system "osTicket".__

*PLEASE NOTE: The websites that are still being referred to throughout this demo have since been torn down and are now pointing to non-existent spaces on the internet. If you've followed along in the installation and configuration portions then you will see the up-and-running sites for yourself. These are screenshots taken during the exercise. :)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
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

<h3>Intake</h3>

_We'll start as an external user and navigate to the page where a ticket may be created:_
- In your browser, go to the End User Ticket Page (http://localhost/osTicket/).
- Click on "Open a New Ticket".
<p align=center>
<img src="https://i.imgur.com/Udla59t.jpg" height="80%" width="80%" alt="Welcome Page"/>
</p>

- Enter an Email Address and Full Name (this example uses **karen@osticket.com / Karen Karen**)
- Select any Help Topic or one that was created in the previous demo (this example uses **Business Critical Outage**).
- Type a quick Header and a short description under Issue Summary (anything can be typed for demonstration purposes).
- Once done, click "Create Ticket".
<p align=center>
<img src="https://i.imgur.com/40QD7AI.jpg" height="80%" width="80%" alt="PC Issues"/>
<img src="https://i.imgur.com/gg905UJ.jpg" height="80%" width="80%" alt="General Inquiry"/>
</p>

_Create a few more tickets with varying importance:_ 
<p align=center>
<img src="https://i.imgur.com/gsYwMkX.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Uh85P3N.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<hr>

<h3>Assignment and Communication</h3>

_We'll now log in as an Agent and work from the agent's perspective:_

- On the web browser (Microsoft Edge), go to the Help Desk Login Page (http://localhost/osTicket/scp/login.php).
  - Log into the osTicket Help Desk using an Agent account (this example uses username **jane.doe / jane.doe@osticket.com**).
  - Once logged in, you should see the created tickets from the clients.
- Click on any available ticket (this example selects **entire mobile online banking is down**).
<p align=center>
<img src="https://i.imgur.com/IlBoq7U.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

_As an Agent, we can begin working on this ticket._

_The mobile banking site is down which could have a major impact on the company! **Each setting needs to be changed to properly Communicate the Urgency of the issue:**_

- Set Priority from Normal to **Emergency**.
- Assign the department to **System Administrators**.
- Assign a specific person to manage this ticket, **Jane Doe**.
- Change the SLA Plan from Normal to **SEV-A** for this example.
<p align=center>
<img src="https://i.imgur.com/V8WJ5GJ.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/JR8XMOt.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/CvAfVuZ.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Wk23cCI.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/QIbVd0K.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<hr>

<h3>Working the Issue</h3>

_On the overview page, we can see each update within the Ticket Thread. As an Agent, we can communicate using Post Reply bringing status updates to anyone viewing or working on this ticket._
<p align=center>
<img src="https://i.imgur.com/qtVIjs7.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- Under Post Reply, enter your status information.
- Keep the Ticket Status "Open (current)", assuming the issue isn't resolved.
- Click "Post Reply".
<p align=center>
<img src="https://i.imgur.com/P5tLSZ5.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/YvCnXJe.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

_Your message will be sent and posted on the thread to track status changes until resolution._
<hr>

<h3>Resolution</h3>

_Now that the issue has been resolved:_
- Under Post Reply, record a final update.
- Change the Ticket Status to "Resolved".
<p align=center>
<img src="https://i.imgur.com/e1Ac4aR.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/vkOXsXv.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

_Once a ticket is resolved, it is considered "closed", so it should disappear from the Open Tickets page._<br>
_You can find it under the "Closed" tab, where you can see how many tickets were closed and when._
<p align=center>
<img src="https://i.imgur.com/xw9gHmX.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- Continue to work through the remaining tickets and use your best judgment when setting priority or assigning to a department.
<p align=center>
<img src="https://i.imgur.com/N68R5Y9.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<hr>

<h2><p align=center></p></h2>

__<p align=right>Make sure to clean up your resources in Azure :)<br>__
</p>
