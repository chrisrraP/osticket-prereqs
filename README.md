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

- IIS and Management Console
- PHP and Rewrite Module
- MySQL
- HeidiSQL
- osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/chrisrraP/osticket-prereqs/blob/main/Install%20IIS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a virtual machine (VM) that uses Windows 10 OS. Reference https://github.com/chrisrraP/configure-ad to learn how to create virtual machines. Install IIS by right-clicking on the start button, click on "run" and type in "control panel". Select program and features. Select "windows features. Install and enable IIS management console in web management tools. Also, enable CGI and all of Common HTTP Features boxes (located in: world wide web services > application development features.) Install PHP manager. Install rewrite module.
</p>
<br />

<p>
<img src="https://github.com/chrisrraP/osticket-prereqs/blob/main/Configure%20MySQL%20Settings.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a folder in C:\ called "PHP". Install PHP and unzip contents to PHP folder you created. Install VC redist.x86.exe. Install MySqL (typical setup). Launch configuration wizard, select standard and create a name plus password. FYI- You will need to remember them.
</p>
<br />

<p>
<img src="https://github.com/chrisrraP/osticket-prereqs/blob/main/Ost%20Permissions.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://github.com/chrisrraP/osticket-prereqs/blob/main/osTicket%20Installed.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
