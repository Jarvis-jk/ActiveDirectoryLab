<h1>Active Directory Home Lab</h1>



<h2>Description</h2>
This project involved setting up a virtual Active Directory (AD) lab with a Windows Server 2019 VM as a Domain Controller (DC). The DC, equipped with dual NICs, connected to both the internet and a private network. It provided network address translation (NAT) and DHCP services to distribute IP addresses within the private network. A PowerShell script was utilized to create 1000 users in AD. Additionally, a Windows 10 VM was configured as a client, automatically obtaining an IP from the DC and joining the 'mydomain.com' domain, showcasing the practical implementation of a scalable user management system in a virtualized environment.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 


<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Server 2019</b>

<h2>Program walk-through:</h2>

<p align="center">
NIC Set up: <br/>
<img src="https://i.imgur.com/IDDQTp1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Assigning Ip adressing to Server:  <br/>
<img src="https://i.imgur.com/elqAmhk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installed Active directory domian severes and NAT and DHCP: <br/>
<img src="https://i.imgur.com/wY282r1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configured NAT:  <br/>
<img src="https://i.imgur.com/gtgPwKn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configured DHCP:  <br/>
<img src="https://i.imgur.com/JJrWFwO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created Users throught PowerShell script:  <br/>
<img src="https://i.imgur.com/yuf1wK7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Joined Client to Domain and signed in:  <br/>
<img src="https://i.imgur.com/UkSFAjD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
