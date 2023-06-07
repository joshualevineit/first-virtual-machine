<p align="center">
<img src="https://i.imgur.com/9s38cqh.png" 
</p>

<h1>How to create your first Virtual Machine in Azure</h1>
This tutorial outlines the prerequisites and installation steps of creating and launching our first virtual machine in Azure.<br />

<h2>Why use an Azure Virtual Machine?</h2>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- An internet connection
- An active Microsoft Azure subscription

<h2>Installation Steps</h2>

<h3>STEP 1</h3>
</p>
From your search bar enter "portal.azure.com" to reach the Azure homepage.
<p>
<img src="https://i.imgur.com/CBi1pwC.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 2</h3>
<p>
Firstly enter "Virtual Machines" in the search bar above. Under Services select Virtual Machines.
<p>
<img src="https://i.imgur.com/sCszESe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 3</h3>
<p>
In the Virtual Machines page, select Create and then select Azure Virtual Machine. The create a virtual machine page opens.
<p>
<img src="https://i.imgur.com/tBMzKaa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 4</h3>
<p>
In the Basics tab, under Project Details, ensure the correct subscription is selected if more than one subscription exists and then choose Create new resource group. Enter myResourceGroup for the name.
<p>
<img src="https://i.imgur.com/vK780Ke.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 5</h3>
Under Instance details, enter VM1 for the Virtual machine name, and choose your respective region. For this example, choose Windows 10 Pro, version 21H2 - x64 Gen2 for your image. Leave the other options as is. The default size and pricing in this tutorial is only shown as an example. Size availability and pricing are dependent on your region and subscription.
<p>
<img src="https://i.imgur.com/Uc5v6dJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 6</h3>
Under Administrator account, in Username enter azureuser. For password create something safe and secure, as this will be what you use to access your Virtual machine.
<p>
<img src="https://i.imgur.com/8WIVZ59.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 7</h3>
Under Inbound port rules > Public inbound ports, choose Allow selected ports and then select HTTP (80), HTTPS (443), and RDP (3389) from the drop down menu. Once that is completed, leave the remaining options as default and then select the Review + create button at the bottom of the page.
<p>
<img src="https://i.imgur.com/jD1yv8I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 8</h3>
On the Create a virtual machine page, you can see the details of the virtual machine you are about to create. When you are ready, select Create.
<p>
<img src="https://i.imgur.com/tfx3MHD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 9</h3>
When the deployment is complete, select Go to resource.
<p>
<img src="https://i.imgur.com/K8lVkFY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 10</h3>
On the page for your new VM, select the public IP address and copy it to your clipboard.
<p>
<img src="https://i.imgur.com/WNRPo70.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 11</h3>
For Windows users, open Remote Desktop Connection and paste the public IP address for your new VM here. For users on MAC, you may want to download Microsoft Remote Desktop on the MAC App Store for this step, once downloaded paste the public IP address for your new VM here and select Connect.
<p>
<img src="https://i.imgur.com/tdMBGeB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 12</h3>
Next you will be asked to enter your credentials (username and password) to access your VM, enter your info and select OK.
<p>
<img src="https://i.imgur.com/fu3J2eE.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 13</h3>
You may recieve a certificate warning during the sign-in process. Click yes to create the connection.
<p>
<img src="https://i.imgur.com/3T3yzYP.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 14</h3>
Congratulations! You have created your first Virtual Machine in Microsoft Azure. This is a sample of what your VM will look like once you have signed in. The blue bar at the top of the page containing your VM's IP address is the most clear indicator to know when you are inside of your VM vs your actual PC.
<p>
<img src="https://i.imgur.com/PjZJ8o5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
