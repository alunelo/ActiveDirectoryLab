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
Logging Into Domain Controller Administrator Account:<br/>
<img src="https://imgur.com/iGezngD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Changing the name of the Internal Network:  <br/>
<img src="https://imgur.com/sOzqUSo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Changing the name of the NAT: <br/>
<img src="https://imgur.com/a01PW36.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configuring the Static IP, Subnet Mask, and DNS Address to the Internal Network:  <br/>
<img src="https://imgur.com/5r2zQaW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Changing PC Name:  <br/>
<img src="https://imgur.com/8UD4MdC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Restarting PC To Initiate Name Change:  <br/>
<img src="https://imgur.com/rYLxolK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installation of Active Directory Services:   <br/>
<img src="https://imgur.com/bzRozRl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating Root Domain Name:   <br/>
<img src="https://imgur.com/i8CIUuy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Active Directory Services Has Finished Installing and The PC Is Restarting:   <br/>
<img src="https://imgur.com/5XuH8IB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Logging into Domain Controller Administrator Account With Domain Services Installed:   <br/>
<img src="https://imgur.com/sGtlLtW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating An Organizational Unit:   <br/>
<img src="https://imgur.com/7wji0IH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Making an ADMINS folder under the "Organizational Unit":   <br/>
<img src="https://imgur.com/hQoKIvN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating An Account In The _ADMINS Group: <br/>
<img src="https://imgur.com/dQtTAGQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Entering Credentials For The New Admin Account: <br/>
<img src="https://imgur.com/k34Vvc2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating Password and Configuring Password Settings:  <br/>
<img src="https://imgur.com/F24qeXG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Making The Account A Member Of Domain Admins: <br/>
<img src="https://imgur.com/ArWzbaP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Logging Into The New Administrator Account:  <br/>
<img src="https://imgur.com/ETnQ2Gq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Routing & RAS Installation Completed:  <br/>
<img src="https://imgur.com/HwGGaCS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Choosing the _Internet_ Interface For NAT Internet Connection:  <br/>
<img src="https://imgur.com/5hYlUa1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
RAS & NAT Successfully Installed:<br/>
<img src="https://imgur.com/ACe1L4A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
DHCP Server Installation Completed:  <br/>
<img src="https://imgur.com/hWRTvBy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating New DHCP Scope: <br/>
<img src="https://imgur.com/nZpfVbN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configuring Start & End IP Address Scope and Subnet Mask:  <br/>
<img src=https://imgur.com/jx5spNw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Setting Default Gateway to 172.16.0.1:  <br/>
<img src="https://imgur.com/VxZjyzB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configuring DNS IP Addess:  <br/>
<img src="https://imgur.com/FQqMk1C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
DHCP Scope Completed:   <br/>
<img src="https://imgur.com/sSuO9Y2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Adding Routing and 172.16.0.1 IP Address:   <br/>
<img src="https://imgur.com/EpEBCSk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Running Windows Powershell ISE as an Administrator:   <br/>
<img src="https://imgur.com/Lc3stUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Opening Powershell Script to Generate Users:   <br/>
<img src="https://imgur.com/uPTUHt6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
Changing Current Directory to The File That Contains Neccessary Files For The Generation of Users:   <br/>
<img src="https://imgur.com/XDwtssD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Adding Myself As a User On The "USERS" Text File So That I Can Use It to Log Into The Client Computer Later:   <br/>
<img src="https://imgur.com/vAr6GIq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Initiating The Script to Run: <br/>
<img src="https://imgur.com/GpCMFmv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
1,042 Users Generated: <br/>
<img src="https://imgur.com/Nj0DVbO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Logged Into The Client Computer:  <br/>
<img src="https://imgur.com/rE56An6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Using "ipconfig /all" Command to Confirm That The Network Configurations Are Running Properly: <br/>
<img src="https://imgur.com/7k5RBzF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Adding CLIENT1 PC to the domain:  <br/>
<img src="https://imgur.com/KOKvFvY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Entering User Account "alo" to Enter The Domain:  <br/>
<img src="https://imgur.com/HJVXk04.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
PC Added to The Domain Successfully:  <br/>
<img src="https://imgur.com/sAPNiVz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Restarting PC to Initiate Changes:   <br/>
<img src="https://imgur.com/Ptt0MDQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
Logging Into LOONDOMAIN Using The "alo" USER Account: <br/>
<img src="https://imgur.com/qPtTEaK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
Used Commands Such As "hostname" and "whoami" to Confirm PC Name and The Account That Is Being Used: <br/>
<img src="https://imgur.com/hBMtOcs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
DHCP Server Confirmation That "CLIENT1" PC Is The Current PC That Received An 8 Day Lease for The IP Address 172.16.0.100:  <br/>
<img src="https://imgur.com/BP6pSXK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
PC Asks for Adminstrator Credentials When Attempting to Run Command PrompT as An Admin on The User PC: <br/>
<img src="https://imgur.com/PLYlhve.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Using Commands Such as "ping" and "tracert" to Ensure That The Network is Running Smoothly:  <br/>
<img src="https://imgur.com/eQYPMOb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
