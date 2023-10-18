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

- Step 1 Enable Internet Information Services in (I.S.S)
- Step 2 Install Web Platform Installer  
- Step 3 Install MySQL and set up the username and password
- Step 4 Install C++ Redistributable
- Step 5 Configure permissions and install OS Ticket

<h2>Installation Steps</h2>

<p>
  <img src="https://i.imgur.com/hQgxQyt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First things first, let's enable IIS with CGI and Common HTTP Features and install the IIS Management Console. During the installation process, make sure to tick the checkboxes for CGI and Common HTTP Features in the World Wide Web Services -> Application Development Features section. Additionally, enable the IIS Management Console in the Internet Information Services -> Web Management Tools section. We need these features to get things rolling smoothly.
</p>
<br />

<p>
<img src="https://i.imgur.com/L12z1dh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next up, it's time to download and install the PHP Manager for IIS. You can find the installation file (PHPManagerForIIS_V1.5.0.msi) and get it set up. Don't forget to also download and install the Rewrite Module (rewrite_amd64_en-US.msi) to enhance our URL rewriting capabilities. To keep things organized, let's create a directory named "C:\PHP" on our system. We'll need it later.

Now, it's time to grab PHP version 7.3.8. You can find the installation files and specifically look for the zip file named php-7.3.8-nts-Win32-VC15-x86.zip. Once downloaded, extract its contents into the "C:\PHP" directory we just created.

For the smooth functioning of PHP, we need to install the Visual C++ Redistributable package. Grab the VC_redist.x86.exe file from the installation files and run it to complete the installation process.
<br />

<p>
<img src="https://i.imgur.com/Yopl5KW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installation is complete and ready to browse to login page.
<br />
