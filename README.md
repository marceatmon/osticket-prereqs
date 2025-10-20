<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create an Azure Virtual Machine in Windows 10
- Log into the Virtual Machine with the Remote Desktop app
- Download and unzip osTicket Installation Files onto VM desktop
- Install/Enable IIS in Windows with CGI
- Install PHP Manager for IIS
- Install the Rewrite Module
- Create the directory C:\PHP
- Unzip the PHP file into the C:\PHP folder
- Install the VC_redist.x86 file
- Install the MySQL file
- Open IIS as an Admin
- Register PHP from within IIS and reload IIS by stopping and starting
- Install osTicket
- Reload IIS again by stopping and starting
- Within IIS -> Enable php_imap.dll -> php_intl.dll -> php_opcache.dll
- Click the Refresh icon on the browswer for the changes to take effect

<h2>Installation Steps</h2>

![image URL](https://github.com/marceatmon/osticket-prereqs/blob/main/Azure.png)
</p>
<p>
A new virtual machine (VM) was created for osTicket in Microsoft Azure.
</p>
<br />

![image URL](https://github.com/marceatmon/osticket-prereqs/blob/main/Remote%20Desktop.png)
</p>
<p>
Once the VM is created, find and copy the public IP address. Open Remote Desktop (RD) app and paste the IP address into the RD app. After clicking Connect, login to the RD connection using the username and password that was created for the VM. Click connect for the VM to load.
</p>
<br />

![image URL](https://github.com/marceatmon/osticket-prereqs/blob/main/osTicket%20Installation%20Files.jpg?raw=true)
</p>
<p>
Download all necessary osTicket installation files as a zip file onto the desktop of the VM using Remote Desktop. Then unzip the files.
</p>
<br />

![image URL](https://github.com/marceatmon/osticket-prereqs/blob/main/Enabling%20PHP%20extensions%20in%20IIS.jpg?raw=true)
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

![image URL](https://github.com/marceatmon/osticket-prereqs/blob/main/OsTicket%20Install.jpg?raw=true)
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

![image URL](https://github.com/marceatmon/osticket-prereqs/blob/main/OsTicket%20Install%20Completed.jpg?raw=true)
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

![image URL](https://github.com/marceatmon/osticket-prereqs/blob/main/Heidi%20post%20install%20config.jpg?raw=true)
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
