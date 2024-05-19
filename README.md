<h1>Active Directory LAB</h1>


<h2>Description</h2>
Welcome to my Active Directory Lab project on GitHub! I made this project to demonstrate my proficiency with Active Directory as a cybersecurity enthusiast. I've created a sandbox environment using virtual machines (VMs) that mimics real-world situations, showcasing my expertise in Active Directory deployment, management, and security.
<br />


<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Windows Server </b>
- <b>Oracle VM Virtual Box Manager</b>

<h2>Achievement</h2>

- <b>Setting Up Virtual Environment:
The tutorial begins with setting up a virtual environment using VirtualBox. This includes downloading VirtualBox, the ISO files for Windows Server and Windows Client, and creating virtual machines for both the domain controller (Windows Server) and the client.
</b>

- <b>Networking Configuration:
Network settings are configured within VirtualBox to ensure proper communication between the virtual machines. This involves setting up an internal network for communication between the domain controller and the client.
</b>

- <b>Installing Windows Server:
The Windows Server is installed on the domain controller virtual machine. This includes configuring settings such as memory allocation and network adapters.
</b>

- <b>Configuring Windows Server:
After installation, various configurations are performed on the Windows Server, including renaming the machine, configuring network adapters, setting up DHCP, and enabling Active Directory Domain Services.
</b>

- <b>Promoting Server to Domain Controller:
The Windows Server is promoted to a domain controller, and a new forest is created.
</b>

- <b>Configuring DHCP and NAT:
  DHCP and NAT services are configured on the domain controller to manage IP addresses and enable internet access for internal clients.
</b>

- <b>Creating User Account:
  An admin account is created within Active Directory Users and Computers to facilitate logging into the domain.
</b>

<h2>Program walk-through:</h2>

<p align="center">
Over view of VM manager and DC setup:  <br/>
<img src="https://imgur.com/eWj0Njo" height="80%" width="80%" alt="Active Directory lab"/>
<br />
<br />
Installing Windows Server:  <br/>
<img src="https://imgur.com/gkwbuuB" height="80%" width="80%" alt="Active Directory lab"/>
<br />
<br />
Configuring Windows Server:  <br/>
<img src="https://imgur.com/XPkrzac" height="80%" width="80%" alt="Active Directory lab"/>
<br />
<br />
Promoting Server to Domain Controller:  <br/>
<img src="https://imgur.com/NAT8yag" width="80%" alt="Active Directory labs"/>
<br />
<br />
Configuring DHCP and NAT: DHCP and NAT services are configured <br/>
<img src="https://imgur.com/qfKF924" width="80%" alt="Active Directory lab"/>
<br />
<br />
Creating a domin name  <br/>
<img src="https://imgur.com/OuuT2dt" alt="Active Directory lab"/>
<br />
<br />
User Profile created on olayemilab Domain  <br/>
<img src="https://imgur.com/tOaQofI" alt="Active Directory lab"/>
<br/>
<br />
Client 1 successfully added to olayemilab Domain  <br/>
<img src="https://imgur.com/8kxbobd" alt="Active Directory lab"/>
<br/>
Client 1 updated to Domain name  <br/>
<img src="https://imgur.com/kU88gs7" alt="Active Directory lab"/>
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
