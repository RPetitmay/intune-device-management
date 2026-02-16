<p align="center">
<img src="https://i.imgur.com/QxC6u2g.jpeg" alt="Traffic Examination"/>
</p>

<h1>Intune Device Management Lab (Windows)</h1>
This lab demonstrates enrolling a Windows device into Microsoft Intune and managing it using compliance policies, configuration profiles, and application deployment.
 <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Intune
- Microsoft Entra ID
- Microsoft 365 Developer Tenant (E5 Sandbox)
- Microsoft 365 Admin Center
- PowerShell
- Notepad/Notes App (Needed for saving usernames, passwords, and other information)

<h2>Operating Systems Used </h2>

- Windows 10 / Windows 11
- Windows Virtual Machine

<h2>List of Prerequisites</h2>

- Basic/General Understanding of Microsoft Intune

<h2>Setup and Usage Proton VPN</h2>
<p>
<img src="https://i.imgur.com/1HCgbw6.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/58at38N.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<h3>Capturing IP Address Information on Personal Computer and Virtual Machine</h3>
<ol>
  <li>
    Before logging into your virtual machine (VM), visit 
    <a href="https://whatismyipaddress.com/" target="_blank">https://whatismyipaddress.com/</a>.  
    Record the IP address details of your local computer, including the city, region, and country.
  </li>
  <li>
    Sign in to your VM and navigate to the same website:  
    <a href="https://whatismyipaddress.com/" target="_blank">https://whatismyipaddress.com/</a>.  
    Again, record the IP address information for the VM, including the city, region, and country.
  </li>
</ol>
<h3>Connecting to VPN Servers and Browsing Websites and IP Addresses</h3>
<p>
<img src="https://i.imgur.com/lydn3pS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<ol>
  <li>
    On your local computer, sign up for the free version of ProtonVPN by visiting  
    <a href="https://account.protonvpn.com/signup?plan=free&language=en" target="_blank">
      https://account.protonvpn.com/signup?plan=free&language=en
    </a>.
  </li>

  <li>
    Within your virtual machine (VM), download and install the ProtonVPN client.
  </li>
<p>
<img src="https://i.imgur.com/6BvXcPg.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
  <li>
    Log in to ProtonVPN at  
    <a href="https://account.protonvpn.com/login" target="_blank">https://account.protonvpn.com/login</a>  
    and connect to a VPN server located in a different country (e.g., Japan).
  </li>
<p>
<img src="https://i.imgur.com/BT7Qd4K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
  <li>
    After connecting, navigate to  
    <a href="https://whatismyipaddress.com/" target="_blank">https://whatismyipaddress.com/</a>  
    and record the displayed IP address details in a text file.
  </li>
<p>
<img src="https://i.imgur.com/D8YT3UH.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
  <li>
    Browse to any websites such as Google, Disney, Amazon or Netflix.  
    Observe whether the displayed language, URL, or site content differs based on the location of your selected VPN server.
  </li>
</ol>
