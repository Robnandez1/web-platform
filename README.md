<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Web Platform Installer: C++ Redistributable, PHP Manager Installation, and MySQL
</h1>






<h2>Environments and Technologies Used:</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used: </h2>

- Windows 10</b> (21H2)
- Mac OSX High Sierra

<h2>Prerequisite:</h2>

- Web Platform Installer: C++ Redistributable, PHP Manager Installation, and MySQL

<h2>Installation Steps:</h2>

<p>
<img src="https://imgur.com/vBAckSa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The Web Platform Installer is used to download multple files needed for a server to work properlly. In this case, I need to add and download PHP Manager, specific versions of PHP files, C++ Redistributable, and MySQL. This is required for osTicket to function properly on Windows 10. For security, a username (root) and password is required to complete the download process. Once all three are downloaded sucessfully, the next step is to download osTicket on Windows 10. Once downloaded, the files on the osTicket Folder must be copied to Files Explorer: thispc\windowsc\inetpub\wwwroot. After pasted, I can open the ISS application to program a live server. On the "sites" tab on IIS, I will find the link that will sucessfully open a web browser of the osTicket application which is named as: localhost/osTicket/Setup/
</p>
<br />

<p>
