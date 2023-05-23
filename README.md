<p align="center">
<img src="https://i.imgur.com/9s38cqh.png" 
</p>

<h1>How to create your first Virtual Machine in Azure</h1>
This tutorial outlines the prerequisites and installation steps of creating and launching our first virtual machine in Azure.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- An internet connection
- A active Microsoft Azure subscription

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/sCszESe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Firstly enter "Virtual Machines" in the search bar above. Under Services select Virtual Machines
</p>
<br />

<p>
<img src="https://i.imgur.com/tBMzKaa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the Virtual Machines page, select Create and then Azure Virtual Machine. The create a virtual machine page opens.
</p>
<br />

<p>
<img src="https://i.imgur.com/vK780Ke.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the Basics tab, under Project Details, ensure the correct subscription is selected if more than one subscription exists and then choose Create new resource group. Enter myResourceGroup for the name.
</p>
<br />

<p>
<img src="https://i.imgur.com/Uc5v6dJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under Instance details, enter VM1 for the Virtual machine name, and choose your respective region. For this example, choose Windows 10 Pro, version 21H2 - x64 Gen2 for your image. Leave the other options as is. The default size and pricing in this tutorial is only shown as an example. Size availability and pricing are dependent on your region and subscription.
</p>
<br />

<p>
<img src="https://i.imgur.com/8WIVZ59.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under Administrator account, in Username enter azureuser. For password create something safe and secure, as this will be what you use to access your Virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/jD1yv8I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under Inbound port rules > Public inbound ports, choose Allow selected ports and then select HTTP (80), HTTPS (443), and RDP (3389) from the drop down menu. Once that is completed, leave the remaining options as default and then select the Review + create button at the bottom of the page.
</p>
<br />

<p>
<img src="https://i.imgur.com/IfB2Hqq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On the Create a virtual machine page, you can see the details of the virtual machine you are about to create. When you are ready, select Create.
</p>
<br />

<p>
<img src="https://i.imgur.com/RMNLl9w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When the deployment is complete, select Go to resource.
</p>
<br />

<p>
<img src="https://i.imgur.com/IrrPhH1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On the page for your new VM, select the public IP address and copy it to your clipboard.
</p>
<br />

<p>
<img src="https://i.imgur.com/ZAA0Up6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
NEXT STEP
</p>
<br />
