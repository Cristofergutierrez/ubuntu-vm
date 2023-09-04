<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/76/Ubuntu-logo-2022.svg/1920px-Ubuntu-logo-2022.svg.png" alt="Ubuntu logo"/>
</p>

<h1>Ubuntu Virtual Machine- Prerequisites and Installation</h1>
This tutorial outlines the installation of Ubuntu Virtual Machine in a local host environment using Proxmox.<br />


<h2>Environments and Technologies Used</h2>

- Proxmox (Virtual Machines/Compute)
- Remote Desktop
- ssh

<h2>Operating Systems Used </h2>

- Ubuntu 22.04</b> (21H2)

<h2>List of Prerequisites</h2>
- Proxmox running in a local host<br>
- Ubuntu iso image 

<h2>Installation Steps</h2>

<p>
<img src="https://imgur.com/ZKM9rdo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Inside proxmox click on Create VM on the top right of the screen
</p>
<br />

<h2>Setup the Virtual Machine</h2>

<p>
<img src="https://imgur.com/IupEIHi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Name your VM and give it an ID number<br>
2. Select the dowloaded ubuntu iso image<br>
3. Based on your local machines specs choose what you want to share with the virtual machine. ex: 2 vcpu 4gb ram 32gb storage<br> 
4. Click Start after created and then Finish
</p>
<br />

<h2>Install</h2>
<p>
<img src="https://imgur.com/rPhqHSC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select the Virtual machine you just created and go into the console to open the Ubuntu GUI, then click Install Ubuntu.
</p>
<br />

<p>
<img src="https://imgur.com/3OIfRKz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Continue with the installion steps. create a username and password and restart when finished.
</p>

<p>
<img src="https://imgur.com/q5ZwF33.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Congrats! Ubuntu 22.04 is now running on a virtual machine on your local computer
</p>
<br />

