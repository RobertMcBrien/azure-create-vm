<p align="center">

![image](https://github.com/user-attachments/assets/2367d5cb-6e20-4e85-a49e-80f7373e2a3a)

</p>

<h1>Creating a Virtual Machine in Azure</h1>

<h2>Description</h2>
<p>This project demonstrates how to create and set up a virtual machine in Microsoft Azure. We will go on the Microsoft Azure Portal(Virtual Machines/Compute). Then we will learn how to
create a Resource group, create our virtual machine, set up our virtual machine, finish creating/deploying it and then learn how to log in to our newly created virtual machine.
</p>
<h2>Environments Used</h2>

- Windows 10
- Microsoft Azure portal

<h2>Step by step Walkthrough:</h2>

<p>

  ![SelectResourceGroup](https://github.com/user-attachments/assets/c0c4022b-9c30-4579-a671-ef22227bd738)

</p>
<p>
First, we go to the Microsoft Azure website portal. After logging in, we hit the search bar at the top, type in "Resource groups", after clicking on that, we then select create.
</p>
<br />

<p>

  ![RG](https://github.com/user-attachments/assets/22bfb67c-db41-419c-97e7-ec8cb6ad9fe4)


</p>
<p>
The next step consist of naming the resource group and selecting the region for our resource group. Choose an appropriate name for your project, and select the region you are located within.
</p>
<br />

<p>

  ![SelectCreateVM](https://github.com/user-attachments/assets/95ee487d-b4f2-466a-8272-c45bfa51b705)

</p>
<p>
Following the creation of your resource group, you then click the search bar at the top, and type in "virtual machines". Select virtual machines, and then you should make it to this specific page. On this page you will select the create option.
</p>
<br />

<p>

 
 ![VMDetails](https://github.com/user-attachments/assets/70b15062-f406-48c5-b12e-ee842af57a6f)


</p>
<p>
In this step, we set up our project details. First, we ensure our virtual machine is located in the correct resource group. Then, we choose an appropriate name for our machine. Likely relating to its use or purpose. Select the region closest to you, and remember to use the same specific zone for all virtual machines you plan on using together. After that, you will select your image type, aka your server of choice, for example, windows or ubuntu.

</p>
<br />


<p>

![SelectSizenImageVM](https://github.com/user-attachments/assets/565539c2-70c9-477e-9dfe-71faa1979975)


</p>
<p>
In this step we select the VM architecture and the size of the virtual machine. The standard architecture is x64, and the recommended size of the machine should be at least two central processing units and 8 GIB memory. You may have to choose 16 GIB of memory depending on the options available in your zone.
</p>
<br />


<p>

 ![CreateUernameVM](https://github.com/user-attachments/assets/e99762a6-639e-47df-89f1-1e87d3ef251e)


</p>
Next, we will enter in our username and password. I suggest writing this down somewhere, just in case you forget. You will also select your inbound ports, preferably being RDP. Finally, you will confirm you have an eligible windows license with hosting rights.
<p>

</p>
<br />

<p>

![ReviewnCreateVM](https://github.com/user-attachments/assets/8cbdd350-26dd-412f-b17e-69cc85c5e643)



</p>
<p>
In this step, we review our project, and see if it passes the validation process. If, it passes inspection, we can select create. If not, we may have to adjust something. Some users, may have issues with too many Virtual machines, or resource groups being used at the same time, or in the same region. This will vary based on your specific microsoft azure subscription. Make sure you read the specific error message to troubleshoot accordingly. Otherwise, you can create.
</p>
<br />

<p>

 
 ![remotedesktop](https://github.com/user-attachments/assets/f2b68941-96b7-434d-a08b-2a96166bc99e)




</p>
<p>
Bonus! To use the virtual machine, or logon. We simply go to our computer search bar at the bottom left, and type in remote desktop connection. After that, enter the appropriate credentials. Including username, password, and public IP address for our virtual machine, and just like that, we have successfully learned how to log in and use our virtual machine.
</p>
<br />



