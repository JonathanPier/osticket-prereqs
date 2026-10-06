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

- What is an OsTicket ? 
- Install PHP Manager for IIS
- Install VC redist.x86.exe
- Install MySQL 
- Assign Permission: ost-config.php
- Install HeidiSQL

<h2>OsTicket</h2>

<p>
<img width="508" height="324" alt="image" src="https://github.com/user-attachments/assets/a942fc53-56c4-418a-8c88-a6e377d24679" />
<img width="573" height="260" alt="image" src="https://github.com/user-attachments/assets/d3f5866d-ffd2-4a07-885f-5a849592d5b7" />

</p>
<p>
osTicket is an open-source customer support and help-desk ticketing system that allows organizations to manage customer questions, technical support requests, incidents, and service issues in one centralized location. Instead of handling support requests entirely through email or phone calls, an organization can use osTicket to create, organize, assign, track, and resolve support tickets. Installing osTicket requires a web server, PHP, and a MySQL-compatible database such as MariaDB or MySQL. 


<h2>Install PHP Manager for IIS</h2>

<p>
<img width="596" height="614" alt="image" src="https://github.com/user-attachments/assets/10fd0cb5-301e-4674-a492-d6b94c3dba64" />

</p>
<p>
A PHP manager is a software tool or administrative interface that helps system administrators, developers, and hosting providers install, configure, manage, and monitor PHP on a computer or web server. PHP is a server-side programming language commonly used to create dynamic websites and web applications. Because PHP has many configuration options and can have multiple versions installed on the same server, managing PHP manually can sometimes become complicated. A PHP manager simplifies these tasks by providing a centralized way to control PHP versions, settings, extensions, and other PHP-related features.</p>
<br />


<h2>Install VC redist.x86.exe</h2>
<p>
<img width="431" height="555" alt="image" src="https://github.com/user-attachments/assets/f19acd7e-c7df-47a5-8fa3-32ab15810b4a" />
</p>
<p>
The file VC_redist.x86.exe is an installer for the Microsoft Visual C++ Redistributable for 32-bit (x86) applications. The x86 designation is important because it refers to the architecture of the application that needs the runtime, not necessarily the architecture of the Windows operating system. A 64-bit version of Windows can run 32-bit applications through its compatibility system. Therefore, a 64-bit Windows computer can still require the x86 Visual C++ Redistributable if the PHP installation or another application is a 32-bit application.

The reason this matters when installing PHP is that PHP itself, or one of its components, may depend on particular Visual C++ runtime libraries. If the appropriate runtime is not available, Windows may be unable to start PHP or load one of its DLL files. Instead of PHP working normally, the administrator may receive an error indicating that a DLL is missing, that the application cannot start, or that a required runtime component could not be found.</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
