<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA

<h2>Configuration Steps</h2>

<p>
  
![Screen Shot 2024-10-13 at 6 39 40 PM](https://github.com/user-attachments/assets/109a2002-5d55-4184-bea5-d56a8749e65f)
![Screen Shot 2024-10-13 at 6 41 41 PM](https://github.com/user-attachments/assets/8a77179b-1e3a-4042-a7fb-ed2410e89ea8)
![Screen Shot 2024-10-13 at 6 42 00 PM](https://github.com/user-attachments/assets/cef090de-bd8b-4244-a627-4133bb9fb3aa)
![Screen Shot 2024-10-13 at 6 44 21 PM](https://github.com/user-attachments/assets/95acd841-a893-428b-87e7-521a78619c86)

<p>

Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin

<br />

<p>
  
![Screen Shot 2024-10-13 at 6 45 57 PM](https://github.com/user-attachments/assets/9687d39f-8792-40c7-9f91-e3ac32c32cf3)
![Screen Shot 2024-10-13 at 6 46 49 PM](https://github.com/user-attachments/assets/91be205a-ef16-4f9b-94f8-353bc1e6fb8d)
![Screen Shot 2024-10-13 at 6 47 59 PM](https://github.com/user-attachments/assets/6c5ba1dd-aa25-47c6-bed4-539a596287f5)


<p>
Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins

<br />

<p>
  
![Screen Shot 2024-10-13 at 6 56 31 PM](https://github.com/user-attachments/assets/ef89975d-3ee2-4d50-9190-4555830bc72a)


</p>
<p>
Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking

</p>
<br />


![Screen Shot 2024-10-13 at 7 01 38 PM](https://github.com/user-attachments/assets/5c9345a6-07e2-4996-946e-6dd7fbdb4102)
</p>

Configure Agents (workers)
Admin Panel -> Agents -> Add New

<br />

![Screen Shot 2024-10-13 at 7 08 51 PM](https://github.com/user-attachments/assets/78da0231-72c8-43f4-bac8-afb5ad8569a6)
![Screen Shot 2024-10-13 at 7 09 08 PM](https://github.com/user-attachments/assets/43c33390-113f-4f5b-bae4-015e4516f813)

</p>
Configure Users (customers)
Agent Panel -> Users -> Add New

<br />
</p>
<p>

![Screen Shot 2024-10-09 at 11 55 21 PM](https://github.com/user-attachments/assets/997d4ebb-0ee7-4852-85ec-8ac2af101d60)
![Screen Shot 2024-10-10 at 12 07 06 AM](https://github.com/user-attachments/assets/1bc45203-c47f-49e2-a40d-32d24f106bfe)
![Screen Shot 2024-10-10 at 12 07 59 AM](https://github.com/user-attachments/assets/eaed2f00-a35a-408e-acf6-426ce3a1e2a0)
![Screen Shot 2024-10-10 at 12 08 55 AM](https://github.com/user-attachments/assets/30c84a2c-2427-4dcc-bfe1-12c1c38268e7)
</p>
<p>
Configure SLA
Admin Panel -> Manage -> SLA

<br />

![Screen Shot 2024-10-10 at 12 10 48 AM](https://github.com/user-attachments/assets/41307f0e-ea69-4104-a95e-f717f8746bb9)
</p>
<p>
Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
<br />


