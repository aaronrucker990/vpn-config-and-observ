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


<h1>Observing Configurations</h1>


<h2>Visual 1</h2>

<p>
<img src="https://i.imgur.com/924SVlu.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Once you browse to www.whatismyipaddress.com you can observe the personal IP Addresss and how it shows the current locatation. You also can observe how my location is currently in Dallas, Texas, from my personal computer.

</p>
<br />


<h2>Visual 2</h2>


<p>
<img src="https://i.imgur.com/WwztYA0.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

You now want to create our Windows 10, Virtual Machine. 

Note : If you create a Virtual Machine in Azure it will automatically create your Resouce Group, as long as you click new Resource Group when creating your virtual Machine. 

</p>
<br />

<h2>Visual 3</h2>


<p>
<img src= "https://i.imgur.com/4VdZdCq.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
    
Now when you remote into your Virtual Machine, please take into account that you have to remote into the public IP Address. If you notice in the visual you can see how the public IP Address has a circle around it. 

</p>
<br />


<h2>Visual 4</h2>

<p>
<img src="https://i.imgur.com/qj4IPRc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Once logged in to Remote Desktop use the Public Ip Address from the the Virtual Machine, to remote into your Virutal Machine. 

</p>
<br />


<h2>Visual 5</h2>


<p>
<img src="https://i.imgur.com/2SRR3lt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
    
You should see this a screen similar to the visual once you have successfully logged in to your Virtual Machine.
    
</p>
<br />

<h2>Visual 6</h2>


<p>
<img src= "https://i.imgur.com/d0ArxCU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
    
Now when browsing to www.whatismyipaddress.com your personal IP Addresss should be the location of the Virtual Machine. It should be diferrent from the personal IP Address that you had, before you entered into your Virtual Machine via RDP.

    
</p>
<br />

<h2>Visual 7</h2>

<p>
<img src="https://i.imgur.com/HHr1jfj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
    
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
    
</p>
<br />


<h2>Visual 8</h2>


<p>
<img src="https://i.imgur.com/dYqCSJI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
    
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
    
</p>
<br />

<h2>Visual 9</h2>


<p>
<img src= "https://i.imgur.com/kGSXwad.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
    
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
    
</p>
<br />


<h2>Visual 10</h2>


<p>
<img src= "https://i.imgur.com/2R4HVjp.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


