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

- Azure Tenant (Organization)
- Subscription
- Resource Group and Virtual Machine
- Virtual Network
- Subnet

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/hUSSPBt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this lab I will demonstrate how to setup, configure and use osTicket. Above is the outline for this lab.
</p>
<br />

<p>
<img src="https://i.imgur.com/7U4wCcp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
<img src="https://i.imgur.com/FOibmLg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, you will need to go to https://portal.azure.com and then click on "resourse groups". Then click on "create resource group", and give the resource group a name. After naming your resource group you will have to click "review + create" at the bottom of the screen. Next, click "create" one additional time and now you should have an active resource group. Examples above.
</p>
<br />

<p>
<img src="https://i.imgur.com/w5qcyq8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/xKQMpli.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, you will need to click "home" and then click "virtual machines", after that you need to click "create" and "Azure virtual machine". You should now be on the same page as seen on the example above. Choose the resource group you just created to be the resource group for your virtual machine, then give your virtual machine a name. After that you will want to choose Windows 10 as your image as well as choosing a size that has either 2 or 4 virtual cpus(vcpus). Now you will need to create a username and password for your virtual machine. Then check the licensing box at the bottom and lastly click "review + create" and then click "create" one additional time. Now you have successfully created a virtual machine. Examples above.
</p>
<br />
<img src="https://i.imgur.com/blQH7CG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/YdQZMlh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Next, you will need to open your virtual machine and copy the public IP address. Now go to start and type in "remote desktop" and then paste the public IP address and click "connect". After that, Click "use another account" then enter the credentials you created. Now you should see a disclaimer that states "The identity of the remote computer cannot be verified. Do you want to connect anyway?" Click "yes" and now you should be on the home screen of the virtual machine. Examples above.
</p>
</p>
<img src="https://i.imgur.com/HAfOW3V.png" height="80%" width="80%" "alt="Disk Sanitization Steps"/>


First, go to your web browser and search for as well as download and install "web platform installer". Next, open web platform installer and search "MySQL", then add "MySQL Windows 5.5". You will also need to search for and add the following "PHP 5.6.31", "PHP 7.0.33 (x86)", "PHP 7.1.29 (x86)", "PHP 7.2.26 (x86)", "PHP 7.3.25 (x86)", " PHP 7.4.13 (x86)" and once you have added all of them, click "install".
