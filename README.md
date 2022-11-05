<p align="center">
<img src="https://i.imgur.com/hx4TXLv.jpg" height="80%" width="80%" alt="VPN logo"/>
</p>    
    
<h1>Configuring and Observing a VPN within a Virtual Envoirment</h1>
This tutorial outlines the implementation of Configuring and Observing a VPN within a Virtual Envoirment.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- VPN

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Configation of Steps</h2>

Section 1

(Create Virtual Machine in Azure)
1. Browse to https://whatismyipaddress.com/ and take note of this in a text file
2. Create a Resource Group
3. Create a Windows 10 Virtual Machine in another geographic location (try a different country)
   
Section 2

 1. Log into the VM with Remote Desktop
 2. Browse to https://whatismyipaddress.com/ and take note of this in a text file
 
(Sign up for ProtonVPN and test the VPN connection)

4. On your actual computer, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en  
5. Back within your VM, download the Proton VPN client
    1. Login to the VPN and choose a VPN server in yet another country (such as Japan)
    2. Browse to https://whatismyipaddress.com/  and take note of this in a text file
6. Try browsing to Google, Disney, and/or Amazon and see if there is anything different about the sites in relation to the location of your VPN server. For example, the language or URL may be different

Section 3

(Clean up Azure resources)

7. Delete the resource group you created in Section 1
8. Ensure the resources/Resource Group has been deleted.


<h2>Observations Made on Configurations</h2>


<h2>Visual 1</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


<h2>Visual 2</h2>


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<h2>Visual 3</h2>


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
