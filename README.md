<h1>Active Directory Home Lab</h1>

<h2>Description</h2>
In this project, I created an Active Directory (AD) home lab environment using Oracle VirtualBox to deepen my understanding of AD and Windows networking. I built a robust infrastructure by setting up a domain, configuring user accounts, and implementing group policies to enforce security settings and standardize user environments. Additionally, I configured a DHCP server for dynamic IP address assignment and established static IP addresses, subnet masks, and a default gateway for the domain host, optimizing overall network management. To streamline the user account creation process, I utilized PowerShell to automate the generation of over 1,000 user accounts from a text file. This project significantly enhanced my practical skills in user identity management and secure networking practices, effectively preparing me for real-world IT challenges.
<br />

<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Active Directory Domain Services</b>
- <b>DHCP Server</b>
- <b>DNS</b>
- <b>Routing and Remote Access</b>


<h2>Environments Used </h2>

- <b>Windows 10</b> 
- <b>Windows Server 2019</b>
- <b>Oracle VirtualBox</b>
<h2>Program walk-through:</h2>

<p align="center">
Locating the network properties on the domain controller account: <br/>
<img src="https://imgur.com/Cybbkda.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Navigated to Network Details to identify the internal network router:  <br/>
<img src="https://imgur.com/IyLboHK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Manually changing the name of the internal network for easier access: <br/>
<img src="https://imgur.com/1B7XUtZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configuring IPv4 settings for configuration:  <br/>
<img src="https://imgur.com/EEUkrLe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Manually assigning the static IP address (172.16.0.1), subnet masket (255.255.255.0), and DNS (127.0.0.1):  <br/>
<img src="https://imgur.com/mvSKJaM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Selecting destination server for domain:  <br/>
<img src="https://imgur.com/HCt6IBP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installation of Domain Services completed:  <br/>
<img src="https://imgur.com/Chkbx9L.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Making a root domain name for the server:   <br/>
<img src="https://imgur.com/zUk4GzH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating a password for the server:   <br/>
<img src="https://imgur.com/c1WUTsp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installation of the domain controller in progress:   <br/>
<img src="https://imgur.com/94gTGCn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installation complete and PC is initiating a restart:   <br/>
<img src="https://imgur.com/5XuH8IB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Logging into DOMAIN controller account:   <br/>
<img src="https://imgur.com/oWfhMZo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Making an ADMINS folder under the "Organizational Unit":   <br/>
<img src="https://imgur.com/5RPvruE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating Administrator Credentials:   <br/>
<img src="https://imgur.com/d7lur53.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
