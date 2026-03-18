<h1>Active Directory Home Lab</h1>

<h2>Description</h2>

This lab demonstrates how to deploy a Windows Active Directory environment using Oracle VirtualBox.

The environment includes:

• Windows Server 2019 Domain Controller  
• Active Directory Domain Services (AD DS)  
• DNS and DHCP configuration  
• NAT routing using RRAS  
• Windows 10 client joined to the domain  
• PowerShell automation to create 1000+ users  

This simulates a small enterprise network infrastructure.

<br />

<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b>
- <b>Active Directory Domain Services</b>
- <b>DHCP Server</b>
- <b>DNS Server</b>
- <b>Routing and Remote Access (RRAS)</b>
- <b>Oracle VirtualBox</b>

<br />

<h2>Environments Used</h2>

- <b>Windows Server 2019</b>
- <b>Windows 10</b>
- <b>Oracle VirtualBox</b>

<br />

<h2>Network Architecture</h2>

<p align="center">
<img src="screenshots/network-diagram.png" width="80%">
</p>

<br />

<h2>Program Walk-through:</h2>

<p align="center">

Create Domain Controller Virtual Machine<br/>

<img src="01-create-dc-vm-1.png" width="80%"/>
<br/>
<img src="01-create-dc-vm-2.png" width="80%"/>

<br/><br/>

Install Windows Server 2019<br/>

<img src="02-install-windows-server-1.png" width="80%"/>
<br/>
<img src="02-install-windows-server-2.png" width="80%"/>

<br/><br/>

Configure Static IP Address<br/>

<img src="03-configure-static-ip.png" width="80%"/>

<br/><br/>

Install Active Directory Domain Services<br/>
<img src="04-install-ad-ds-1.png" width="80%"/>
<br/>
<img src="04-install-ad-ds-2.png" width="80%"/>

<br/><br/>

Create Domain<br/>
<img src="05-create-domain-1.png" width="80%"/>
<br/>
<img src="05-create-domain-2.png" width="80%"/>

<br/><br/>

Configure NAT using Routing and Remote Access<br/>
<img src="06-configure-nat-rras-1.png" width="80%"/>
<br/>
<img src="06-configure-nat-rras-2.png" width="80%"/>
<br/>
<img src="06-configure-nat-rras-3.png" width="80%"/>

<br/><br/>

Configure DHCP Scope for Internal Network<br/>
<img src="07-configure-dhcp-scope.png" width="80%"/>
<br /><br />

Create Domain Admin Account<br/>
<img src="08-create-domain-admin-1.png" width="80%"/>
<br/>
<img src="08-create-domain-admin-2.png" width="80%"/>
<br/>
<img src="08-create-domain-admin-3.png" width="80%"/>

<br/><br/>

Create Windows 10 Client Virtual Machine<br/>
<img src="09-create-windows-10-client-vm-1.png" width="80%"/>
<br/>
<img src="09-create-windows-10-client-vm-2.png" width="80%"/>
<br/>
<img src="09-create-windows-10-client-vm-3.png" width="80%"/>

<br/><br/>

Verify Network Connectivity<br/>
<img src="10-verify-network-connectivity-1.png" width="80%"/>
<br/>
<img src="10-verify-network-connectivity-2.png" width="80%"/>
<br/>
<img src="10-verify-network-connectivity-3.png" width="80%"/>

<br/><br/>

Join Windows 10 Client to Domain<br/>
<img src="11-join-client-to-domain-1.png" width="80%"/>
<br/>
<img src="11-join-client-to-domain-2.png" width="80%"/>

<br /><br />

Verify Computer Appears in Active Directory<br/>
<img src="12-verify-computer-in-ad.png" width="80%"/>
<br /><br />

Run PowerShell Script to Generate Users<br/>
<img src="13-run-powershell-user-script-1.png" width="80%"/>
<br/>
<img src="13-run-powershell-user-script-2.png" width="80%"/>
<br/>
<img src="13-run-powershell-user-script-3.png" width="80%"/>

<br/><br/>

</p>

<h2>Skills Demonstrated</h2>

• Active Directory Deployment  
• DNS and DHCP Configuration  
• NAT and Routing  
• Domain User Management  
• PowerShell Automation  
• Virtualized Enterprise Network Setup  

<br />

<h2>Project Outcome</h2>

This lab successfully demonstrates how a corporate Windows domain environment is built and managed. The project simulates real-world enterprise infrastructure where domain users authenticate to centralized services through a Domain Controller.
