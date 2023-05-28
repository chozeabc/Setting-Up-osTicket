<p align="center">
<img src="https://i.imgur.com/r7UlOH2.png" alt="osTicket logo"/>
</p>

<h1>Step-by-Step Guide: Creating a Virtual Machine in Azure and Setting Up osTicket</h1>
This tutorial outlines the prerequisites and installation process for osTicket, an open-source help desk ticketing system. It covers the setup of a Virtual Machine in Azure, enabling Internet Information Services (IIS), installation of PHP and additional components, configuration of osTicket, and the setup of the MySQL database.<br />
<h2>Environments and Technologies Used</h2>
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
<h2>Operating Systems Used </h2>
- Windows 10 (21H2)
<h2>Steps:</h2>
- Step 1: Create Azure VM with Windows <br>
- Step 2: Enable IIS on VM <br>
- Step 3: Install PHP and components <br>
- Step 4: Install MySQL with password <br>
- Step 5: Register PHP with IIS <br>
- Step 6: Extract and move osTicket <br>
- Step 7: Enable PHP extensions in IIS <br>
- Step 8: Rename and adjust ost-config.php <br>
- Step 9: Complete osTicket setup <br>
- Step 10: Install and configure HeidiSQL <br>
- Step 11: Finish osTicket setup <br>
<h2>Installation Steps</h2>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Create a Virtual Machine in Azure with Windows 10 OS, 2-4 Virtual CPUs, and a new Virtual Network (Vnet). Connect to the VM.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. Enable Internet Information Services (IIS) on the VM.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Download and install PHP Manager for IIS, Rewrite Module, PHP 7.3.8, and VC_redist.x86.exe.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Download and install MySQL 5.5.62 with the Standard Configuration, setting the password as "Password1."
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5. Register PHP with IIS.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. Download and extract osTicket. Copy the extracted "upload" folder to C:\inetpub\wwwroot and rename it to "osTicket."
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. Enable required PHP extensions in IIS.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
8. Rename ost-sampleconfig.php to ost-config.php and adjust its permissions.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
9. Complete the osTicket setup in the browser, providing the necessary details.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
10. Download and install HeidiSQL. Create a MySQL database called "osTicket" using HeidiSQL.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
11. Continue setting up osTicket in the browser, providing the MySQL database, username, and password.
</p>
<br />
