# osticket-prereqs<p align="center">
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

- [Item 1](https://drive.google.com/file/d/1RHsNd4eWIOwaNpj3JW4vzzmzNUH86wY_/view?usp=share_link)
- [Item 2](https://drive.google.com/file/d/1tIK9GZBKj1JyUP87eewxgdNqn9pZmVmY/view?usp=share_link)
- [Item 3](https://drive.google.com/file/d/1snNMtLdCOpMtkCyD4mvl9yOOmvVIp9fP/view?usp=share_link)
- [Item 4](https://drive.google.com/file/d/1s1OsGF3-ioO0_9LYizPRiVuIkb3lFJgH/view?usp=share_link)
- [Item 5](https://drive.google.com/file/d/1_OWh9p7VQLcrB0q_V7qT8yHl0xo5gv7z/view?usp=share_link)
- [Item 6](https://drive.google.com/file/d/1_OWh9p7VQLcrB0q_V7qT8yHl0xo5gv7z/view?usp=share_link)

<img src="https://i.imgur.com/ofKWtIn.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
the very first step in installing osTicket is downloading IIS, in order to do that you have to right click the start button and click on each of the folders that I highlighted(make sure the the boxs are colored in) after that check the box that says CGI.
https
<img src="https://i.imgur.com/KlhRy40.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
/p>
<p>
During this course I had learned that in order to get started with osTicket, first you have to download all the installations listed above. I was givin links by my course careers instructor in order to download all the correct installations.
</p>
<br />

<p>
<img src="https://i.imgur.com/1o13Ecc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After you download the installatons for osTicket you have to enable the three extensions that I highlighted yellow in the image above</p>
<br />

<p>
<img src="https://i.imgur.com/CC5w55v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The next step you have to go to files paste this in the search bar C:\inetpub\wwwroot\osTicket\include then look for the file that says ost-sampleconfig.php and change it to ost-config.php then, right click it go to properties, go to the tab that says security then click on advanced disable all inheritance once you do that press add then select a principal and name it eveyone and give everyone full conrol then click apply.
</p>
<br />

<p>
<img src="https://i.imgur.com/eeioJxs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When you get to the this part you have to to fill out the information that they gave you 
</p>
<br />
