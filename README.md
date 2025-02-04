
![image](https://github.com/user-attachments/assets/9f67f734-c4aa-48f2-b351-e527d95f7a92)



<h1>osTicket - Prerequisite and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- A working computer
- Remote Desktop app installed
- Microsoft Azure account

<h2>Installation Steps</h2>

1. Using Azure (create an account if needed), create a virtual machine. As a reccomendation, select Windows 10 with 4 vCPUs. This allows the use of a VM and installation of required software. The picture shows part of creating the VM in Azure.
<img src="[A9276982-8A6C-4123-B87A-A72354995706_1_105_c](https://github.com/user-attachments/assets/2c0759c3-d7f0-425a-8f53-a6b6d530b4ac)" >

![image](https://github.com/user-attachments/assets/1ce8a430-56a3-41a3-a6cf-51b104a7c0e7)



2. Sign into the created virtual machine and download the required osTicket files. This includes the osTicket.zip files and IIS (a web server that will be on the OS and serve up OSticket).


![6A3B1C0C-0BC1-44C1-8A41-B3A6577563AF](https://github.com/user-attachments/assets/2d804f18-dae4-4c78-9417-baceb4f8136b)




3.Install and enable IIS in Windows WITH CGI. To enable, go through the following: Start menu> Control panel> Programs> Install or change a program> Turn windows feature on or off. Then check "CGI" and hit ok to activate it.

![695C5C34-832F-4884-BE96-A472994D1685](https://github.com/user-attachments/assets/49d58122-f214-4042-9d8f-c4012dec29f6)



4.Install PHP Manager for IIS. From the installation files,install the Rewrite Module. Then create the directory C:\PHP. Restart the IIS and from there you can open the osTicket website form the IIS into a web browser. The following picture shows the osTicket site opened and the IIS opened on different tabs both in one Virtual operating system.


![BD95EE2D-10E2-42BB-B361-96247F39875D](https://github.com/user-attachments/assets/e276c198-b520-41f4-b4a4-6ef2b0df9b83)


5.Rename the appropriate file by the name of ost-config.php and assign permissions within the file to everyone. Intall heidiSQL through mySQL. This is a open source software or database that alows the osTicket to use a server and function while using throught the Virtual machine. The following picture shows the osTicket website installed and working in a web browser.

![5E1C4ABB-C989-43AD-A992-0C68C5AF4582](https://github.com/user-attachments/assets/b2cf47b5-125b-48fd-8718-65f174a5aa20)


6.After installing the correct software, you can create the neccesary accounts and passwords. This includes and admin user, URL host name setting, and Admin setting. After the info is created and saved, you can sign into the osTicket website. The picture below shows the sign in page for the site that can be used after the accounts are created, and from there osTicket can be explored and used as a ticketing system for a helpdesk or IT related field in a business.
![516BF6FD-FC92-4B62-9C2A-9BF28DB28394](https://github.com/user-attachments/assets/c2074852-e51e-46e0-902b-f5224ce79fb7)


<p>

<img src="" height="80%" width="80%" alt=""/>
</p>
<p>

</p>
<br />

<p>
<img src="" height="80%" width="80%" alt=""/>
</p>
<p>

</p>
<br />
