<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>

In this tutorial, I will outline the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
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

In Step 1: We create a Resource Group inside Azure.

<p>
<img src="https://i.imgur.com/NLmkO3I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In step 2, we create a Windows 10 Virtual Machine (VM) with 2-4 virtual CPU's inside Azure. We will also allow the Virtual Machine to create a new virtual network (Vnet). We will then create a username and password of our choice. This username and password will be used for the Remote Desktop function we are using to access the virtual machine we just created. 
</p>
<br />

<p>
<img src="https://i.imgur.com/zUJXPhs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In step 3, we open the Remote Desktop Connection app on our computer. A remote desktop is an internet-enabled program or operating system feature that lets someone access a computer from a different location, just as if they were interacting with the device locally. We will be using this to connect to the Virtual Machine we created in Azure. 
</p>
