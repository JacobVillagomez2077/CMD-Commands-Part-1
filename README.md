# CMD-Commands-Part-1
<p align="center">
<img src="https://www.wallpaperflare.com/static/79/573/83/code-minimalism-microsoft-windows-command-lines-wallpaper.jpg"/>
</p>
<p align="center">
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/5a1b3c58-bcc2-48b0-bdb9-93bfc287b09c"/>
</p>
<h1>CMD Virtual Machine Installation Commands</h1>
This tutorial outlines the installation of a virtual machine running Windows 10, then using commands in CMD.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: CMD Commands part 1](https://youtu.be/-1Sw9sHrPPk)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop Connection
- CMD

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Create Resource Group for Virtual Machines
- Create Virtual Machine in Windows
- Log into VM in Windows through Remote Destop Connection  
- Open CMD in the Virtual Machine
- CMD Commands in the command line

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/4d0bee33-04ea-48bf-8d2e-6f764ce8523c"/>
</p>
<p>
First once you are in Azure, click on Resource Groups or you can search it up in the search bar.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/0d1e8141-d7fc-4c1b-84c9-76fed61ed0ce"/>
</p>
<p>
Next we are going to click create resource group
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/388e21ce-cad0-46b8-8bc6-ada943731b97"
<p>
The next page we are going to make sure its under a Azure subscription, then the name of the resource group will be rg-1 and the region in US West US 3
</p>
<br />
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/54a499f6-cce7-4cf2-91e6-c7a2d047c518"
<p>
  
Next we are going to make sure on the top left it says Validation passed with a green check then at the bottom click create and the resource group will be created.
</p>
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/a352f1a3-81bc-4088-a7f8-140ce798c67b"
<p>
  
Then once you go back into the Resource Group you will see that it was created under name and in the top right corner of the page.
</p>
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/d503d5d1-0b3c-44a9-94e6-7046d9d764ab"
<p>
  
Next type in virtual machine in the azure search bar and we are going to create a virtual machine you can click create on the top left or create in the middle of the screen.
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/68f68298-de96-49b3-8f37-1a450bad0a2f"
<p>
  
Now click Azure virtual machine as shown in the image above.
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/68dab5ec-5351-44fb-9d44-6dbd3d873575"
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/ee5d94f2-282d-4055-aaa2-6d3e13a268d3"  
<p>
  
Next click the Resource Group and click rg-1 (Remember this is the one we made)
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/9a403d30-287d-4c32-a7c4-c21071fabe49"
<p>
  
Now under Virtual Machine Name type VM1, Region needs to be US West US 3, Image needs to be Windows 10 Pro version 22H2 x64 Gen2, and the Size needs to be Standard E2s_v3.
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/efb0d977-7b44-49ba-9ded-24fee80137e5"
<p>
  
For Username type labuser and Password can be similar to the special characters, and capitals as shown 907405FIRE$green. After the password you need to check the box by Licensing. 
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/d69be498-b1a9-45e5-9459-17cb185782a8"
<p>
  
Once its done go the Networking tab and make sure virtual network, subnet, and public ip all says (new). 
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/80aef843-8a92-49ce-a305-3c9fc5968012"
<p>
  
Then you can go to review and create, when it passes through it will say Validation passed in the top left then you can press Create at the bottom left to make the Virtual Machine. 
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/a3d69c50-6f22-4d4a-a5ad-576f72e784ce"
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/6bac7907-dc24-49d0-8c6a-0324b767db92" 
  
You know the Virtual Machine is created once it Say Your Deployment is Complete. Then go to search bar and type Virtual Machine and you should see VM1 that we created on the screen overview page.
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/dc481d82-fa7c-4464-8b4e-b48d3c5a8049"
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/f399d089-8d94-45c7-ab6e-76b01e3ee893"
<p>
  
Click VM1 and then go to the right side where the Public IP addresses is and click the copy symbol on the right. Then go to your search bar on your PC and type Remote Desktop Connection and open the app. 
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/5cdbf126-fad9-474d-badb-99e0266fc377"
<p>
  
Next you paste VM1 public IP in the computer section in the Remote Desktop Connection (You can press Ctrl + V to paste the IP address in the computer section). and then type yes to allow the connection
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/8f3eec77-7fe3-49c2-b203-b127da649297"
<p>
  
Then type the user name labuser and the password you made.  
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/32c98164-ecf5-4f43-9e14-df23d7475ab7"
<p>
  
It should look like the image above.
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/71d2c7e6-b51c-4f3d-be91-0c1f0e601fa0"
<p>
  
It should look like the image above.
  
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/62cb58ea-78c3-4068-873b-d662740921d6"
<p>
  
Your screen should load Virtual Machine 1 like the image above.
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/96a12cbb-e2ce-4ed7-b905-f8cd8b3c8019"
<p>
  
Next all of the following click no.
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/313f8b4a-b094-48bd-be8a-e5b272bdcc30"
<p>
  
Then press Yes for the Networks tab that appears on the right side of the Virtual Machine.
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/f5a463bc-fc88-4c9b-9bed-06c5b9511290"
<p>
  
Type Command Prompt in the search bar and press enter to open the app.
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/bc5af93b-9469-4f40-9f65-4a5996fd4f10"
<p>
  
Once the app opens the user should be the one we created labuser.
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/ad0f6aca-b14a-4af4-9ed3-13bc27f7e0a9"
<p>
  
Next click the command line and type ipconfig this is going to find your computer IP address.
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/2cfe3a59-0f31-4fb6-ada5-a33e3f06ad8f"
<p>
  
We can also type ipconfig /all this will show your MAC address and your DNS server.
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/69ef9285-f631-46ab-aca0-6f034b47dda7"
<p>
  
Then type ipconfig /all | findstr DNS this will find a specific string of data of DNS which is in ipconfig to find what you need.
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/ab579151-3e70-42db-885e-95d634e139b0"
<p>
  
We can also give us a new IP address by using ipconfig /release
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/a60290d9-d67a-4aac-9b96-b92413e391a6"
<p>
  
Then type ipconfig /renew this is going to reach out to DHCP server to get a new IP address
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/661aacf2-0f53-4a9b-b5f5-773c9a21274a"
<p>
  
Then type ipconfig /displaydns this shows all the websites and there IP address
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/d56a509f-2520-4ca7-961e-87339f9d8c6b"
<p>
  
After the command it will show all the websites as show above 
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/add6c722-ed40-46fd-b1f1-87febc533f6e"
<p>
  
Next to copy the output of a command to your clipboard type the following ipconfig /displaydns | clip
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/ea212d56-6b53-4511-a0cc-0337031323d4"
<p>
  
To delete your DNS resolver cache on your computer type ipconfig /flushdns in the command line this will remove any old DNS entries
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/20654b02-5bfd-41e5-b8a4-7188fbdb491a"
<p>
  
Next to troubleshoot DNS type nslookup www.google.com this will show www.google.com IP address
<p>
<img src="https://github.com/Jacobvillagomez1/CMD-Commands-Part-1/assets/143027686/fc2d5705-6f49-41da-bd1e-5bc612464e73"
<p>
  
Then finally we can clear the screen of the command line by typing cls
