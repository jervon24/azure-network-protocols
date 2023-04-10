<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Network Security Groups (NSGs)</h1>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Windows server 2022

<h2>High-Level Steps</h2>

- Log in to the Virtual Machine
- Create folders and set Permissions
- Access certain folders as users


<h2>Actions and Observations</h2>

<p>
<img src=https://i.imgur.com/8Idsgpx.png/>
</p>
Logged in to the Domain controller virtual machine and created these four folders the set permissions. Folder “read-access” was shared with “Domain Users” group, Permission was set to “Read”. Folder “write-access”, was shared with the “Domain Users” group and the Permissions was set to “Read/Write” and the folder “no-access” shared with “Domain Admins” and permissions “Permissions: “Read/Write”

<img src=https://i.imgur.com/45fio4x.png/> <img src=https://i.imgur.com/45fio4x.png/> <img src=https://i.imgur.com/45fio4x.png/>


</p>
<br />

<p>
I then logged in to Client-1 to run the domain controller folders to test wheather the folders were accessible. The "no-access" folder did not open which shows that the permissions worked.
<img src=https://i.imgur.com/C7q7AFb.png/>
</p>
<p>
An Accountant security group was created in active directory and the accounting folder was then shared to this security group.The accountant folder was then accessed with a user but since the user is not in the security group, they had no access.
  
  <img src=https://i.imgur.com/6FeAMr7.png/> <img src=https://i.imgur.com/d3z6YGy.png/> <img src=https://i.imgur.com/8nPNwNQ.png/>
</p>
<br />

<p>
The user was then given permissions to access the accounting folder The pictures belows shows now that the user has access to the folder.
  
  <img src=https://i.imgur.com/4LoGpYD.png/> <img src=https://i.imgur.com/gWZA9HH.png/>
</p>
<br />
