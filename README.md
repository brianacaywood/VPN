# VPN
VPN (Virtual Private Network) setup and usage
<p align="center">
<img src="https://images.prismic.io/gatsby-landing-pages/1a68fcb1-42cf-4102-9742-13db46d1aa18_home-section-1.png?auto=format%2Ccompress" alt="VPN Usage"/>
</p>

<h1>Create virtual machine, connect to VPN (Virtual Private Network) using VPN Proton, and observe the IP address changes </h1>
In this tutorial, we observe a virtual machine IP address and location before then after connecting to a Japanese VPN server. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Windows Remote Desktop
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- VPN Proton

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Actions and Observations</h2>

<p>
<img src="https://user-images.githubusercontent.com/131008349/233221880-0a370695-165c-4a5b-877c-8ced25e0dba4.PNG" height="80%" width="80%" alt="Create subscription in Azure"/>
</p>
<p>
Login to Portal.Azure.com and create a VM using Azure. Once you have created the VM, log into it using Remote Desktop Connection by copying and pasting the public IP address into the drop down and connect. After you are inside the VM, go to WhatIsMyIPAddress.com to double check what the IP address is before the VPN (Virtual Private Network) is connected. 
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/131008349/233222100-20366d7c-a68c-4c01-83f6-93e19a609a8a.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Outside the VM, create an account to login into Proton VPN. Once created, go back to the VM, bring up the browser,and visit ProtonVPN.com. Using the login information created, enter it and download the Windows VPN client.
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/131008349/233222305-871a8d99-d45c-47f9-bf65-51b47aa95f2a.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To dowload the VPN client, go to the action menu on the left side of the screen and click on "Downloads" then download the Windows VPN client.  
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/131008349/233222517-4e7fe9db-1e0c-4e24-ae29-c562e9a32bee.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once downloaded, login to the client using your credentials made in the first step.
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/131008349/233223110-924c5dac-a74f-460e-8814-e674ab30265a.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that you're logged in, select a free VPN server location to connect to a server to start your secure connecton. For this example, we selected Japan.  
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/131008349/233223259-f83f673c-5a27-46ba-bbbc-f3c7f6b1d30e.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After you are connected to the VPN, go to your browser and visit WhatIsMyIPAddress.com. Notice that the IP address and location changed now that we are using the VPN. 
</p>
<br />
