<h1>Installing Windows Server 2016 OS (Domain Controller)</h1>


<h2>Description</h2>
<p>This is the initial step of this project. I will first create a virtual machine on the software called Oracle VirtualBox and then rename the VM as "Windows Server 2016". I will then install the Windows Server 2016 operating system inside of the VM.</p>


<br />

<h2>Step-by-Step Walk-Through:</h2>


<p align="center"> 
STEP 1: <br/>
<img src="https://i.imgur.com/AV5utKx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> </p>


<p align="center">This is the first step of this project. I have installed the software ORACLE VIRTUALBOX, which allows me to install and manage virtual devices on my laptop. The use of this software allows me to create a small network where I create a domain that includes a server and some clients.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 2: <br/>
<img src="https://i.imgur.com/QJ3768b.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> </p>


<p align="center">In this step I click where it says “NEW”. This function will allow me to add a virtual client inside the software “VirtualBox”. In this case, I will try to add “Windows Server 2016” which will be used for active directory, to create a domain and manage all clients on the domain.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 3: <br/>
<img src="https://i.imgur.com/97ybWrN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> </p>


<p align="center">In this step I add details about the virtual machine that I want to add and configure it with the appropriate needs. As you can see, I’ve filled all of the informations required for this virtual machine. I’ve included the name with “Windows Server 2016” and selected the version as “Windows 2016 (64-bit)”. After this is done, I proceeded by click on the button “Next”. As you can see, I haven’t selected an ISO image to run the Operating System of Windows, I will add it once I run the actual Virtual Machine.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 4: <br/>
<img src="https://i.imgur.com/B376im9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> </p>


<p align="center">In this step, I've assigned RAM memory and CPU for the virtual machine, as well as the amount of hard disk storage it will receive. I've allocated 2GB of RAM, which is the minimum required to run a Virtual Machine, as well as 2 CPU cores, which will allow the Virtual Machine to perform tasks efficiently. I then proceeded to set up the actual storage for the Virtual Machine; 32 GB of storage is more than sufficient for this lab-based project. After everything was completed, I clicked the "Next" option to add the Virtual Machine.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 5: <br/>
<img src="https://i.imgur.com/GRMn16p.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> </p>


<p align="center">As you can see, I've successfully added a virtual machine into the lab-based project. The next thing to do will be to launch the Virtual Machine and load an ISO so that it can execute an operating system.</p>

<br />


<p align="center"> 
<img src="https://i.imgur.com/bpliGZ1.png" height="50%" width="50%" alt="Disk Sanitization Steps"/> </p>


<p align="center">I click the "START" button, which allows me to start the virtual machine. As you can see, I was greeted with an error message indicating that there is no "Operating System" to boot the virtual machine.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 6: <br/>
<img src="https://i.imgur.com/StLqrW0.png" height="50%" width="50%" alt="Disk Sanitization Steps"/> </p>


<p align="center">To overcome the previously mentioned issue, I must select an ISO to boot the system of the Virtual Machine. To select the ISO, I clicked the small arrow icon on the right side, followed by the small "Folder" icon at the bottom. After choosing the "Folder" icon, I'll be able to choose an ISO.</p>

<br />

<p align="center"> 
<img src="https://i.imgur.com/P3owG3c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> </p>

<p align="center">I got directed to my actual ISO file, and I selected it. I obtained the ISO file for free from Google and saved it in my "Downloads" folder. This ISO contains the operating system that will enable the Virtual Machine to run Windows Server 2016.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 7: <br/>
<img src="https://i.imgur.com/y3AXOJM.png" height="50%" width="50%" alt="Disk Sanitization Steps"/> </p>


<p align="center">As you can see, the ISO file has been selected and is ready to be mounted on the Virtual Machine. In this stage, I'll click the "Mount and Retry Boot" option, which will enable the Virtual Machine to boot with the new Operating System.</p>

<br />

<p align="center"> 
<img src="https://i.imgur.com/mXA8jNJ.png" height="70%" width="70%" alt="Disk Sanitization Steps"/> </p>


<p align="center">The new operating system has been successfully loaded on the virtual machine. As you can see, the Virtual Machine is booting up the Windows operating system.</p>

<hr width="100%" size="2">


<br />

<p align="center"> 
STEP 8: <br/>
<img src="https://i.imgur.com/BZ1ZMPT.png" height="70%" width="70%"/> </p>


<p align="center">The Virtual Machine has been successfully loaded with the Windows operating system. As you can see, I'm on the initial setup page, where I can configure the VM based on my requirements. In this instance, I click the "NEXT" button to proceed to the next step.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/yV20weV.png" height="70%" width="70%"/> </p>


<p align="center">It's asking me which version of Windows to select. In this instance, I selected the second option. The reason for this is that the second option contains a GUI interface, which makes it easier for me to navigate the OS. I did not select the first choice because it lacks a GUI and will make it more difficult for me to manage the Virtual Machine. After selecting the version to install, I clicked "NEXT" to move on to the next stage.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/Dyf6B6N.png" height="70%" width="70%"/> </p>


<p align="center">It's asking me to choose the type of installation to execute. There are just two options: "upgrade" or "custom install" the OS. In this case, I opt for the second option because I am interested in installing the OS rather than upgrade it.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/mVOUcnw.png" height="70%" width="70%"/> </p>


<p align="center">In this phase, it asks where I would like to install Windows. As you can see, I just have one hard drive, "DRIVE 0", and it has 32GB of free space. In this instance, I click "DRIVE 0" and move on to the next stage.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/GbG21Vk.png" height="70%" width="70%"/> </p>


<p align="center">Finally, the Operating System (OS) is being installed, as shown in the image above. The installation procedure will progress through several stages, and once completed, I will be given the choice to move to the next step.</p>











