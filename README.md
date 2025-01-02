<p align="center">
<img src="https://greymatter.com/wp-content/uploads/2021/11/Microsoft-Azure-Logo.png" height="80%" width="80%"/>
</p>

<h1>Azure - Creating Storage Container and uploading files</h1>
This tutorial outlines the creation of of storage container in Azure and how to upload files and edit them.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Azure account

<h2>Creation Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/bf16de6e-d129-4f64-9588-91c1b9f0465d
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log in to azure portal and navigate to resource groups from the home page. In order to create the storage container a resource group is required to the contian the storage container.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Then click "create". Next choose your subscription, name your resource group, and choose a region of your choice. *note!!! use the same region for all items going inside the resource group in the future*
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Towards the top next to "basics" and "Tags" click "review + Create" the click "create" at the bottom
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the search bar search for storage account and click it. Then click create storage account.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The last created subscription and region should already be selected, if not change to the appropriate settings. For the storage account name create a unique name. then for redundancy choose "Locally-redundant Storage (LRS)" for cheap storage. Lastly  clcik "review and create" and then click "create". Wait for the storage account to be deployed.
</p>
<br />
![image](https://github.com/user-attachments/assets/dc2a402e-b283-4169-b26d-988c2eea36ad)
<p>


</p>
<p>
Navigate to your new storage account from the home page and or search for it in the search bar. once inside, in the list down on the left choose data storage > containers
</p>
<br />
