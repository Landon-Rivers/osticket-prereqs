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
<img src="https://i.imgur.com/mqBW4S1.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
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

<p>
<img src="https://i.imgur.com/lYvRvje.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the Installation Files, download and install MySQL 5.5.62
</p>
<br />

<p>
<img src="https://i.imgur.com/z92Zjas.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
On the setup of MySQL 5.5.62 click next and choose Typical Setup and click next.
</p>
<br />

<p>
<img src="https://i.imgur.com/g9tOOOE.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click install.
</p>
<br />

<p>
<img src="https://i.imgur.com/qltWHLy.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
After MySQL 5.5.62 installation is done Launch Configuration Wizard.
</p>
<br />

<p>
<img src="https://i.imgur.com/LArS6o7.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
In MySQL Configuration Wizard choose Standard Configuration and click next. 
</p>
<br />

<p>
<img src="https://i.imgur.com/F5U4hG5.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Check mark Install As Windows Service and click next. 
</p>
<br />

<p>
<img src="https://i.imgur.com/I7c7Lga.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Check mark Modify Security Services, create a root password and click next.
</p>
<br />


<p>
<img src="https://i.imgur.com/PXoMido.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click Execute.
</p>
<br />

<p>
<img src="https://i.imgur.com/yuFqbI7.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click Finish.
</p>
<br />

<p>
<img src="https://i.imgur.com/XBaQeEj.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
After Configuration Wizard is finished setting up Open IIS as an Admin.
</p>
<br />

<p>
<img src="https://i.imgur.com/XC2Ct2i.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Register PHP from within IIS.
</p>
<br />


<p>
<img src="https://i.imgur.com/z8jRT0t.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Reload IIS (Open IIS, Stop and Start the server) located on the right under Action tab.
.</p>
<br />

<p>
<img src="https://i.imgur.com/Zy08ydK.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download osTicket from the Installation Files Folder.
.</p>
<br />


<p>
<img src="https://i.imgur.com/UbwBfnp.png.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/IWk5QOX.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/wv5j0uI.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Extract the zip file and copy “upload” folder to c:\inetpub\wwwroot.
.</p>
<br />

<p>
<img src="https://i.imgur.com/UvUGdyz.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”.
.</p>
<br />

<p>
<img src="https://i.imgur.com/z8jRT0t.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Reload IIS (Open IIS, Stop and Start the server).
.</p>
<br />

<p>
<img src="https://i.imgur.com/EMKhROt.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/y8hMHC7.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to sites -> Default -> osTicket and on the right under browse website click “Browse *:80 and it should send you to osTicket installer page.
.</p>
<br />

<p>
<img src="https://i.imgur.com/H2UgzD8.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Double-click PHP Manager.
.</p>
<br />

<p>
<img src="https://i.imgur.com/y8hMHC7.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click “Enable or disable an extension”
.</p>
<br />

<p>
<img src="https://i.imgur.com/Hp14gly.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Enable: php_imap.dll
.</p>
<br />

<p>
<img src="https://i.imgur.com/8QjlKJB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Enable: php_intl.dll
.</p>
<br />

<p>
<img src="https://i.imgur.com/tssoHK7.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Enable: php_opcache.dll.
.</p>
<br />

<p>
<img src="https://i.imgur.com/Tiqg1Nc.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Refresh the osTicket installer page and observe the changes.
.</p>
<br />

<p>
<img src="https://i.imgur.com/iU94MMz.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/e9E0Lvo.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next step is to rename: ost-config.php

From: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php

To: C:\inetpub\wwwroot\osTicket\include\ost-config.php
.</p>
<br />

<p>
<img src="https://i.imgur.com/3OTcVqx.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Right click ost-config.php under security tab click advanced and Disable inheritance -> Remove All .
.</p>
<br />

<p>
<img src="https://i.imgur.com/X4FaaSm.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now add New Permissions -> Everyone -> All and click apply .
.</p>
<br />


<p>
<img src="https://i.imgur.com/5MJxbhV.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the Installation Files, download and install HeidiSQL.
.</p>
<br />

<p>
<img src="https://i.imgur.com/5MJxbhV.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the Installation Files, download and install HeidiSQL.
.</p>
<br />

<p>
<img src="https://i.imgur.com/q5PaHGo.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open HeidiSQL and create a new session. On the right your usersname is root and your password is the same password you did for wizard configuration in MySQL so be sure to remember it once you login to OSTicket'
.</p>
<br />
