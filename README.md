# AD-Domain-Controller

<h1>Woking with Active Directory in Windows Server 2022</h1>



<h2>Description</h2>
<b> In this lab I download and configure a Windows Server 2022 instance in VirtualBox. I create a user, set the user as an admin account and connect to the DC.
</b>
<br />
<br />
<h3>Step 1: Download Windows Server 2022 ISO file from Microsoft.</h3>
<br />

<p align="center">
<img width="1368" height="904" alt="Windows Server Snip" src="https://github.com/user-attachments/assets/9861db7c-a180-4f72-9cf5-2d87be8d5419" />
</p>


<br />
<br />
<h3>Step 2: Setting up host-only adapter. For lab purposes, I wanted create a private virtual network for communication exclusively between the host computer and VMs.</h3>
<br />

<p align="center">
<img width="934" height="521" alt="Network Setup" src="https://github.com/user-attachments/assets/dc971c47-c927-4bb9-a5e8-82cb8ff1a07d" />
</p>


<br />
<br />
<h3>To ensure reliable communication between the client PC and the domain controller, I configured a static IP address on the PC.</h3>
<br />

<p align="center">
<img width="818" height="631" alt="Static IP" src="https://github.com/user-attachments/assets/6c794820-aeda-4bb7-85e9-e87d720a18c6" />
<img width="825" height="628" alt="image" src="https://github.com/user-attachments/assets/260c022d-0566-4003-8f1d-f67207a0fd34" />
</p>



<br />
<br />
<h3>Step 3: Adding features for AD Domain Services, DHCP, and Remote Access</h3>
<br />

<p align="center">
<img width="712" height="380" alt="DHCP, Remote Access, AD Domain Services" src="https://github.com/user-attachments/assets/c40bc85b-bd46-40e5-9af0-df567fa50bb1" />
</p>




<br />
<br />
<h3>Step 4: Deploying this server as a domain controller "cybergeek.com"</h3>
<br />
