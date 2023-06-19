<p align="center">
<img src="https://i.imgur.com/9s38cqh.png" 
</p>

<h1>How to create your first Virtual Machine in Azure</h1>
This tutorial outlines the prerequisites and installation steps of creating and launching your first virtual machine in Azure.
<br />

<h2>Why use an Azure Virtual Machine?</h2>

Azure Virtual Machines are computer-like entities that exist on the Internet. They allow you to do things on a computer without physically owning one. With Azure Virtual Machines, you can use different types of software and run programs just like you would on a regular computer. They are great for hosting websites and allowing you to create your own online space, storing and analyzing data, and even running game servers. It's like having a virtual computer that you can customize and use for all sorts of tasks and projects and it is all accessible through the Internet.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection

<h2>Operating Systems Used </h2>

- Windows 10</b>

<h2>List of Prerequisites</h2>

- An internet connection
- An active Microsoft Azure subscription

<h2>Installation Steps</h2>

<h3>STEP 1</h3>
<p>
From your search bar type <strong>"portal.azure.com"</strong> to reach the Azure homepage.
<p>
<br>
<img src="https://i.imgur.com/CBi1pwC.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 2</h3>
<p>
From the Azure homepage type <strong>"Virtual Machines"</strong> in the search bar above. Under <strong>Services</strong> select <strong>Virtual Machines</strong>.
<p>
<br>
<img src="https://i.imgur.com/sCszESe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 3</h3>
<p>
In the Virtual Machines page, click <strong>Create</strong> and then select <strong>Azure Virtual Machine</strong>.
<p>
<br>
<img src="https://i.imgur.com/tBMzKaa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 4</h3>
<p>
In the <strong>Basics</strong> tab, under <strong>Project Details</strong>, ensure the correct subscription is selected. *Only applicable if more than one subscription exists* Then, choose <strong>Create new</strong> resource group and give your new resource group a name, (ex.myResourceGroup).
<p>
<br>
<img src="https://i.imgur.com/vK780Ke.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 5</h3>
Under <strong>Instance details</strong> give your VM a name, (ex. VM1). Next, choose your respective region. Finally, choose an Image type for your VM (ex. Windows 10 Pro, version 21H2 - x64 Gen2). The size and pricing in this tutorial is only shown as an example. Size availability and pricing are dependent on your region and subscription. Leave the other options as is and continue to the next step.
<p>
<br>
<img src="https://i.imgur.com/Uc5v6dJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 6</h3>
Under <strong>Administrator account</strong>, create a username you will use to login to your VM, for example "azureuser". For password create something safe and secure.
<p>
<br>
<img src="https://i.imgur.com/8WIVZ59.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 7</h3>
Under <strong>Inbound port rules > Public inbound ports</strong>, choose <strong>Allow selected ports</strong> and then select <strong>HTTP (80)</strong>, <strong>HTTPS (443)</strong>, and <strong>RDP (3389)</strong> from the drop down menu.
<p>
<br>
<img src="https://i.imgur.com/jD1yv8I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 8</h3>
Next, under <strong>Licensing</strong> click the box confirming you have a Windows 10 or 11 license with hosting rights. Once that is completed select the <strong>Review + create</strong> button at the bottom of the page
<p>
<br>
<img src="https://i.imgur.com/rvussy8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 9</h3>
On the Create a virtual machine page, you can see the details of the virtual machine you are about to create. When you are ready, select <strong>Create</strong>.
<p>
<br>
<img src="https://i.imgur.com/tfx3MHD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 10</h3>
When the deployment is complete, select <strong>Go to resource</strong>.
<p>
<br>
<img src="https://i.imgur.com/K8lVkFY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 11</h3>
On the page for your new VM, select the <strong>Public IP address</strong> and copy it to your clipboard.
<p>
<br>
<img src="https://i.imgur.com/WNRPo70.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 12</h3>
For Windows users, open <strong>Remote Desktop Connection</strong> and paste the public IP address for your new VM here. For users on MAC, you may want to download Microsoft Remote Desktop on the MAC App Store for this step, once downloaded paste the public IP address for your new VM here and select <strong>Connect</strong>.
<p>
<br>
<img src="https://i.imgur.com/tdMBGeB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 13</h3>
Next you will be asked to enter your credentials (username and password) to access your VM, enter your info and select <strong>OK</strong>.
<p>
<br>
<img src="https://i.imgur.com/fu3J2eE.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 14</h3>
You may recieve a certificate warning during the sign-in process. Click <strong>Yes</strong> to create the connection.
<p>
<br>
<img src="https://i.imgur.com/3T3yzYP.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>STEP 15</h3>
Congratulations! You have created your first Virtual Machine in Microsoft Azure. <strong>This is a sample of what your VM will look like once you have signed in.</strong> The blue bar at the top of the page containing your VM's IP address is the most clear indicator to know when you are inside of your VM vs your actual PC.
<p>
<br>
<img src="https://i.imgur.com/PjZJ8o5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
