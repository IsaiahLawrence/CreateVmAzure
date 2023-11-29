<p align="center">
<img src="https://i.imgur.com/aG7Bdgt.jpg" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Creating a Virtual Machine in Azure </h1>

<p>In this short tutorial I'll show you how to create a Virtual Machine in Azure and gain remote access into it which I will refer to as RDP (Remote Desktop Connection) </p>


<h2>Environments and Technologies Used</h2>
- Azure
- Windows 10 (22h2)

<h2>Steps</h2>

-Navigate to portal.azure.com 
![image](https://github.com/IsaiahLawrence/CreateVmAzure/assets/152194351/86b85284-2003-4288-b720-c0f683be790d)

- Select Virtual Machines and click create Azure Virtual Machine
![image](https://github.com/IsaiahLawrence/CreateVmAzure/assets/152194351/d170ed1e-60a1-4cdf-8414-f03e30c022f8)

- Name your virtual machine and choose your image which is just your (OS)
![image](https://github.com/IsaiahLawrence/CreateVmAzure/assets/152194351/e398827f-92f7-4370-8b5c-d8852dd915aa)


- Scroll down choose your size I recommend at least 2 vcpus also you'll create your username and password for the virtual machine here *Remember what you put here we will need that information to RDP into it
- You'll also notice that a port is preselected for us (3389) that is the port that allows us remote access. *make sure you check the licensing box as well at the very bottom*
![image](https://github.com/IsaiahLawrence/CreateVmAzure/assets/152194351/35faeddf-9521-48e3-9b55-c8c20eea6213)

- Click review+ create we won't worry about setting up the disks or networking today, azure will take care of that for us you should see a page like this.
![image](https://github.com/IsaiahLawrence/CreateVmAzure/assets/152194351/2d82ddbd-29ef-4e43-9b5f-760852346961)

- Click create, your screen should change and say deployment in progress.
- Wait for it to complete
- Once completed click go to resource
![image](https://github.com/IsaiahLawrence/CreateVmAzure/assets/152194351/aaf565ba-c27a-4895-bd54-b488f3fedad2)

- Now on this Page we can see our VMs IP address we will copy it to clipboard.
![image](https://github.com/IsaiahLawrence/CreateVmAzure/assets/152194351/56102a0f-79a4-4aaa-90cc-a5cdfc16cd7e)

- Now we have our VMs Ip copied we'll press the windows key and that'll bring up our start menu. In the search bar type "rdp"
- An app called Remote Desktop Connection should appear this is where we paste in our IP
![image](https://github.com/IsaiahLawrence/CreateVmAzure/assets/152194351/4cb67ea5-0ccf-4104-9a2a-a733007a3f2d)

- Connect and you may be prompted to sign in under your actual user we don't want to do that, it will not work
- Under that you'll see more choices click that, then use a different account
- Enter your username and password you made when creating the virtual machine
- If done correctly you'll see this
![image](https://github.com/IsaiahLawrence/CreateVmAzure/assets/152194351/1088b8a2-e82a-4011-b64f-93b4bf8f9c3e)

-Choose yes, a new screen will appear and it'll have the IP address you copied up top

- Congrats! You just created a VM and RDP into it. After going through the privacy settings you should see this
![image](https://github.com/IsaiahLawrence/CreateVmAzure/assets/152194351/9c7299c5-0c7f-4d2e-a5b6-f16cbf261fa5)


- Now you're on a computer on your computer! You can surf the web, create files, watch videos.

- That's how you create a VM in Azure and RDP into it.





  

   

