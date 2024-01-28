### OS LAB  1

## Getting Started with VMware Workstation

### What is VMware?

VMware is a standalone company that make different kinds of computing and virtualization softwares.

VMware Workstation Player is a software that allows a user to run different Virtual Machines on a single computer over an operating system (can be Windows or Linux OS) .  We will install Ubuntu OS which is distribution of Linux OS in this lab.



#### Step 1: Downloading VMware Workstation Player

Download the VMware Application from the given link: https://customerconnect.vmware.com/en/downloads/details?downloadGroup=WKST-PLAYER-1700&productId=1377&rPId=97014

<img src="C:\Users\saadu\Videos\Captures\VMware Workstation Player - VMware Customer Connect - Brave 1_19_2023 6_44_12 AM.png" style="zoom:50%;" />

Click on the **Download Now** button as per your operating system:

- VMware Workstation 17.0.0 Player for Windows 64-bit Operating Systems (For Windows OS)
- VMware Workstation 17.0.0 Player for Linux 64-bit (For Linux OS)



#### Step 2: Finding and Executing the VM Ware .exe file

Look for the .exe file of VMware in your download folder and execute it.

<img src="C:\Users\saadu\Videos\Captures\Downloads 1_19_2023 6_50_21 AM.png" style="zoom:50%;" />



#### Step 3: Running the Setup File

After running the setup file, install the VMWare Workstation. 

1. Click on the next button to proceed:

![](C:\Users\saadu\Videos\Captures\Screenshot 1_19_2023 6_53_21 AM.png)



2. Accept the license agreement by marking the checkbox and proceed by clicking next: 

   ![](C:\Users\saadu\Videos\Captures\VMware Workstation 17 Player Setup 1_28_2023 6_50_29 PM.png)

3. Browse for the location to save the VM Ware and mark the box that add VM Ware to path variable.

4. After Installation, click on Finish Button.



#### Step 4: Launching VM Ware & Creating a Virtual Machine

1. Launch VM Ware and click on Create a New Machine:

   <img src="C:\Users\saadu\Videos\Captures\VMware Workstation 17 Player (Non-commercial use only) 1_28_2023 7_27_24 PM.png" style="zoom: 80%;" />

2. A new window will open, browse for the ISO file of the OS you want to install:

   ![](C:\Users\saadu\Videos\Captures\VMware Workstation 17 Player (Non-commercial use only) 1_28_2023 7_33_13 PM.png)

3. Customize the hardware allocation for your Virtual Machine as per your system specifications:

   ![](C:\Users\saadu\Videos\Captures\VMware Workstation 17 Player (Non-commercial use only) 1_28_2023 7_50_32 PM.png)

   Recommended settings are:

   - 4 Cores
   - 4 GB RAM
   - 50 GB HDD

4. After finishing the setup, your machine will start booting and start the installation of ISO Files's OS:

   ![](C:\Users\saadu\Videos\Captures\VMware Workstation 17 Player (Non-commercial use only) 1_28_2023 7_51_18 PM.png)

5. Proceed as per simple installation of an OS. 



#### Step 5: Installation of C Compiler:

To run C++ files, we need C++ Compiler. In order to get compiler, Right Click the mouse button and Open Terminal.

![](C:\Users\saadu\Videos\Captures\Ubuntu 64-bit - VMware Workstation 17 Player (Non-commercial use only) 1_29_2023 4_06_44 AM.png)

After opening the terminal, write

sudo apt install build-essential

and execute it.

![](C:\Users\saadu\Videos\Captures\Ubuntu 64-bit - VMware Workstation 17 Player (Non-commercial use only) 1_29_2023 4_07_24 AM.png)

You are now ready to run C++ Files on your Ubuntu OS.