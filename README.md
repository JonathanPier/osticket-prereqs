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
- Registering PHP Manager with IIS
- Install OsTicket
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
<img width="748" height="524" alt="image" src="https://github.com/user-attachments/assets/22e63d9e-64f2-49f1-8a2d-3f2a7b7582fd" />
</p>
<p>
The file VC_redist.x86.exe is an installer for the Microsoft Visual C++ Redistributable for 32-bit (x86) applications. The x86 designation is important because it refers to the architecture of the application that needs the runtime, not necessarily the architecture of the Windows operating system. A 64-bit version of Windows can run 32-bit applications through its compatibility system. Therefore, a 64-bit Windows computer can still require the x86 Visual C++ Redistributable if the PHP installation or another application is a 32-bit application.

The reason this matters when installing PHP is that PHP itself, or one of its components, may depend on particular Visual C++ runtime libraries. If the appropriate runtime is not available, Windows may be unable to start PHP or load one of its DLL files. Instead of PHP working normally, the administrator may receive an error indicating that a DLL is missing, that the application cannot start, or that a required runtime component could not be found.</p>
<br />


<h2>Install MySQL </h2>
<p>
<img width="593" height="400" alt="image" src="https://github.com/user-attachments/assets/731a48d6-7bb0-4f12-8c18-0c14fd9290db" />
</p>
<p>
When installing osTicket, one of the most important components that must be installed and configured is a database management system such as MySQL or MariaDB. MySQL is needed because osTicket is a database-driven web application. Although PHP is responsible for executing the osTicket application, PHP by itself is not designed to permanently store and organize all of the information that a help-desk system needs. MySQL provides the database environment where osTicket can store, retrieve, update, and manage its information. Without a functioning database, osTicket cannot properly operate as a ticket-management system</p>
<br />


<h2>Registering PHP Manager with IIS</h2>
<p>
<img width="629" height="610" alt="image" src="https://github.com/user-attachments/assets/b377d7c5-316d-4fd7-b7f7-2bec17f2e31b" />
</p>
<p>
When installing a PHP-based application such as osTicket on a Windows server, several different software components must work together. One of the most important components is IIS, or Internet Information Services, which is Microsoft's web server platform for Windows. PHP is the programming environment used to execute PHP applications, while IIS is responsible for receiving web requests from users and delivering websites to their browsers. PHP Manager for IIS provides a convenient way to configure and manage PHP within the IIS environment. Registering PHP Manager with IIS is important because it allows IIS and PHP to be properly configured to work together and gives administrators a practical interface for managing PHP installations.


<h2>- Install OsTicket</h2>
<p>
<img width="1083" height="573" alt="image" src="https://github.com/user-attachments/assets/96520b49-f9d8-4426-ae3b-c16c61a5e453" />
</p>
<p>
When installing osTicket on a web server, one of the most important steps is uploading the osTicket application files to the server. This step is necessary because osTicket is a web-based application made up of many files containing the program's code, configuration files, images, stylesheets, JavaScript files, and other resources required for the help-desk system to operate. Installing PHP, IIS, and MySQL creates the environment that osTicket needs to run, but these components do not contain osTicket itself. The osTicket files must therefore be placed on the web server so that IIS and PHP can access and execute them.
