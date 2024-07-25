<p align="center">  
<img src="https://i.imgur.com/J4ZSpnZ.png" alt="Proton VPN Logo"/>
</p>

<h1>VPN Setup and Usage (using Proton VPN) (Azure)</h1>
This tutorial outlines the implementation and usage of a virtual private network (specifically Proton VPN) within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to implement a virtual private network on a virtual machine within Azure Compute](https://www.youtube.com/watch?v=bHzikQ493xY))

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Virtual Private Network Lab Steps</h2>

- Step 1: Browse to https://whatismyipaddress.com/ and take note of the IP Address.
- Step 2: Create a Windows 10 Virtual Machine inside of Azure, login and browse to https://whatismyipaddress.com/ again and take note of the IP Address.
- Step 3: On the actual computer, sign up for the free version of Proton VPN.
- Step 4: Back within the VM, download Proton VPN client, login to the VPN and choose a VPN server in another country, browse to https://whatismyipaddress.com/ again and take note of 
  the IP Address.
- Step 5: Try browsing to Google, Disney, and/or Amazon (or any website) and see if there is anything different about the sites in relation to the location of the VPN server. For 
  example, the language or URL may be different.

<h2>VPN Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/tpRiiL9.png" height="80%" width="80%" alt="What's my IP Address?"/>
</p>
<p>
In this step, we browsed to https://whatismyipaddress.com/ and took note of the IP Address that was shown .
</p>
<br />

<p>
<img src="https://i.imgur.com/toeil8G.png" height="80%" width="80%" alt="What's my IP Address? - part 2"/>
<img src="https://i.imgur.com/Dm6PDJ0.png" height="80%" width="80%" alt="What's my IP Address? - part 2a"/>
</p>
<p>
In this step, we created a Windows 10 Virtual Machine inside of Azure, logged in, and browsed to https://whatismyipaddress.com/ again and took note of the IP Address.  It showed a different IP Address than the first IP Address from step 1.
</p>
<br />

<p>
<img src="https://i.imgur.com/kSbGMaT.png" height="80%" width="80%" alt="Sign up for Proton VPN."/>
</p>
<p>
In this part of the lab, on the actual computer,  we signed up for the free version of Proton VPN.
</p>
<br />

<p>
<img src="https://i.imgur.com/XvA1xoP.png" height="80%" width="80%" alt="What's my IP Address? - part 3"/>
<img src="https://i.imgur.com/iil6DcI.png" height="80%" width="80%" alt="What's my IP Address? - part 3a"/>
<img src="https://i.imgur.com/hvHYBx7.png" height="80%" width="80%" alt="What's my IP Address? - part 3b"/>
<img src="https://i.imgur.com/32pX4Jf.png" height="80%" width="80%" alt="What's my IP Address? - part 3c"/>
<img src="https://i.imgur.com/4er4Bzm.png" height="80%" width="80%" alt="What's my IP Address? - part 3d"/>
</p>
<p>
In this part of the lab, we logged back within the VM, downloaded Proton VPN client, logged in to the VPN and chose a VPN server in another country (the Netherlands), browsed to https://whatismyipaddress.com/ again and took note of the IP Address.  It showed a third different IP Address than the previous other two.
</p>
<br />

<p>
<img src="https://i.imgur.com/xZMcZyS.png" height="80%" width="80%" alt="Observing Info Browsing inside of VPN"/>
</p>
<p>
In the last part of this lab, while browsing inside of the VPN that is connected to the Netherlands, we observed a difference while browsing the Microsoft Start Page.  All of the words shown in Dutch, the language of the Netherlands, instead of in English.
</p>
<br />
