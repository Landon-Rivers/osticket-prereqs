<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install / Enable IIS in Windows WITH CGI
- PHP Manager for IIS 
- Rewrite Module 
- PHP 7.3.8
- VC_redist.x86.exe
- MySQL 5.5.62
- osTicket v1.15.8
- HeidiSQL

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DB9co5U.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
In Windows features under World Wide Web Services -> Application Development Features check mark the CGI box and click ok to install IIS (Internet        Information Serivices).
</p>
<br />

<p>
<img src="https://i.imgur.com/Zy08ydK.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the Installation Files, download and install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)
</p>
<br />

<p>
<img src="https://i.imgur.com/OcQHgKU.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the Installation Files, download and install the Rewrite Module (rewrite_amd64_en-US.msi).
</p>
<br />

<p>
<img src="https://i.imgur.com/QH0H27O.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create the directory C:\PHP.
</p>
<br />

<p>
<img src="https://i.imgur.com/0B9TBwn.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the Installation Files, download PHP 7.3.8 zip folder and unzip the contents into C:\PHP
</p>
<br />

<p>
<img src="https://i.imgur.com/WNwAHx5.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the Installation Files, download and install VC_redist.x86.exe
</p>
<br />
