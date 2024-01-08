<h1>Active Directory Lab</h1>


<h2>Description</h2>
Explore Active Directory (AD) hands-on! I've created a Windows Server 2019 and Windows 10 virtual environment, setting up AD, DHCP, OUs, groups, and a domain controller.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle Virtual Box</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Windows Server 2019</b>

<h2>Project walk-through:</h2>

<p align="center">
Configured DHCP on Windows Server 2019 for 24-hour leases, enabling connectivity for up to 80 devices in the Active Directory network:  <br/>
<img src="https://i.imgur.com/FauPvUM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created an 'Admin' Organizational Unit (OU), added a user, and granted domain membership. This setup enhances administrative control and streamlines network management within Active Directory: <br/>
<img src="https://i.imgur.com/LeCZpdo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created an 'IT Team' Organizational Unit (OU) in Active Directory, establishing sub-OUs mirroring a real infrastructure. Added users within the OUs to simulate a functional organizational structure:  <br/>
<img src="https://i.imgur.com/4Yz2Xtf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Assigned OU members to a designated group in Active Directory, enhancing network security and resource allocation: <br/>
<img src="https://i.imgur.com/loTLarp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created AD users from a list using a Powershell script:  <br/>
<img src="https://i.imgur.com/vSooVFX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
