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

- Configure Roles, Departments, and Teams
- Configure Agents and Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>

![Screen Shot 2024-01-01 at 14 09 44](https://github.com/TheTechPrince/post-install-config/assets/128175325/aead3d79-cd67-41ac-a10e-5d38b62ab622)

</p>
<p>
In this image, I configured Roles, Departments, and Teams to begin our workflow. After creating these roles I updated Agents and Users to have the corresponding permissions on their profiles. 

</p>
<br />

<p>

![Screen Shot 2024-01-01 at 14 20 06](https://github.com/TheTechPrince/post-install-config/assets/128175325/f5ede587-557a-4bc8-925b-f7cca8532e4b)



</p>
<p>
In this portion, I reviewed and configured the SLA expectation by using the tiers below:

  - SEV-1 (1 hour, 24/7)
  - SEV-2 (4 hours, 24/7)
  - SEV-3 (8 hours, business hours)
</p>
<br />

<p>

![Screen Shot 2024-01-01 at 14 38 35](https://github.com/TheTechPrince/post-install-config/assets/128175325/f1e79a0f-8a2e-465c-ad70-4b857dafc96a)

  
</p>
<p>
Finally, I updated the Help topics to ensure we had a baseline to help users with FAQ. These topics are the following: 

  - Business Critical Outage
  - Password Reset
  - Personal Computer Issues

</p>
<br />
