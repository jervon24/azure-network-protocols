<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Network Security Groups (NSGs)</h1>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Command Line

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Windows server 2022

<h2>High-Level Steps</h2>

- Log in to the Virtual Machine
- Create folders and set Permissions
- Acesses certain folders as users


<h2>Actions and Observations</h2>

<p>
<img src=https://i.imgur.com/8Idsgpx.png/>
</p>
Logged in the Domain controller virtual machine and created this four folders to set permissions. Folder “read-access” was shared with “Domain Users” group, Permission was set to “Read”. Folder “write-access”, was shared with the “Domain Users” group and the Permissions was set to “Read/Write” and the folder “no-access” shared with “Domain Admins” and permissions “Permissions: “Read/Write”

<img src=https://i.imgur.com/45fio4x.png/> <img src=https://i.imgur.com/45fio4x.png/> <img src=https://i.imgur.com/45fio4x.png/>


</p>
<br />

<p>
I then logged in to Client-1 run the domain controller folders to test wheather I was able to access some folders. I was not able to access the "no-access" which shows that the permissions worked.
<img src=https://i.imgur.com/C7q7AFb.png/>
</p>
<p>
An Accountant security group was created in active directory
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
