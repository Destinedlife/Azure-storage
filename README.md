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

![step 1](https://github.com/user-attachments/assets/73da8860-c4e9-4522-86ef-8f126658069f)

<p>
Log in to azure portal and navigate to resource groups from the home page. In order to create the storage container a resource group is required to the contian the storage container.
</p>
<br />

![step 3](https://github.com/user-attachments/assets/1f7e7d71-ab8b-45ea-b13d-0610f211c4a8)
![step 4](https://github.com/user-attachments/assets/a9d2d886-aaaf-4337-8885-0b2601628d2b)


<p>
Then click "create". Next choose your subscription, name your resource group, and choose a region of your choice. *note!!! use the same region for all items going inside the resource group in the future*
</p>
<br />

![step 5](https://github.com/user-attachments/assets/e88893a8-be87-456d-8377-522c1374343f)

<p>
Towards the top next to "basics" and "Tags" click "review + Create" the click "create" at the bottom
</p>
<br />

![step 6](https://github.com/user-attachments/assets/f2f11379-79a7-45b6-aca3-8348fb4d6b33)

<p>
In the search bar search for storage account and click it. Then click create storage account.
</p>
<br />

![step 7](https://github.com/user-attachments/assets/c1397275-177d-4de7-bc38-4740fc35c6e6)

<p>
The last created subscription and region should already be selected, if not change to the appropriate settings. For the storage account name create a unique name. then for redundancy choose "Locally-redundant Storage (LRS)" for cheap storage. Lastly  clcik "review and create" and then click "create". Wait for the storage account to be deployed.
</p>
<br />

![step 8](https://github.com/user-attachments/assets/d24cacc1-831d-42bc-824a-19aecbc21ba5)

<p>
Navigate to your new storage account from the home page and or search for it in the search bar. once inside, in the list down on the left choose data storage > containers. Then click "+ container"
</p>
<br />

![image](https://github.com/user-attachments/assets/ae4f6006-9754-4675-8e18-79c18b150446)

<p>
  Give the container a name and click create. Now your storage cloud storage has been created. Click on your new storage container and click upload to upload a new file.
</p>
<br />
