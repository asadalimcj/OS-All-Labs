### OS LAB  2

## Installing g++ for executing C  & C++ files

#### Step 1 : Opening The Terminal

**Right Click** on the desktop and select **"Open Terminal"**.

![](C:\Users\saadu\Videos\Captures\opent terminal.png)

#### Step 2 : Updating Existing Packages and Dependencies

Now in the command line interface, write `sudo apt update` and hit **Enter Key** to execute the command.

> `sudo apt update` updates the package index with the latest version information from all configured sources. This includes package names, dependencies, and other package information used by apt to manage packages.

![](C:\Users\saadu\Videos\Captures\Ubuntu 64-bit - VMware Workstation 17 Player (Non-commercial use only) 1_31_2023 1_46_52 AM.png)

It will take some time to download and install the updates.

#### Step 3 : Installing the "build-essential" Package

After successful execution of the previous command, write `sudo apt install build-essential` in the terminal and hit **Enter Key**.

> The `build-essential` package actually belongs to Debian. It is not a piece of software in itself. It contains a list of packages that are required to create a Debian package (deb). These packages are libc, gcc, g++, make, dpkg-dev etc. 

![](C:\Users\saadu\Videos\Captures\build-essential.png)

It will take some while to download and install. After installation, you are able to run C++ files.

## Checking g++ version

In order to check g++ version, write `g++ --version` in the terminal and hit **Enter Key**. 

![](C:\Users\saadu\Videos\Captures\Ubuntu 64-bit - VMware Workstation 17 Player (Non-commercial use only) 1_31_2023 2_58_01 AM.png)



------

#### Creating, Editing and Executing C++ File

#### 1. Creating C++ File

**Right Click** the mouse button on **Desktop** and select **Show Desktop In Files**.

A new window will open as follows: 

![](C:\Users\saadu\Videos\Captures\Ubuntu 64-bit - VMware Workstation 17 Player (Non-commercial use only) 1_31_2023 3_02_56 AM.png)

 Now open the terminal and write `mkdir filename` , press **Enter Key** to make a new folder. The "filename" is the name of the new folder made.  

> mkdir stands for “**make directory**.” With mkdir , you can also set permissions, create multiple directories (folders) at once, and much more.

![](C:\Users\saadu\Videos\Captures\Ubuntu 64-bit - VMware Workstation 17 Player (Non-commercial use only) 1_31_2023 3_11_46 AM.png)

Now write `cd filename` to navigate through the folder.

> `cd` command offers several ways to navigate and change the working directory using the terminal window.

![](C:\Users\saadu\Videos\Captures\Ubuntu 64-bit - VMware Workstation 17 Player (Non-commercial use only) 1_31_2023 3_17_08 AM.png)

Here, we have navigated through the NewFolder. 

In order to create a new file, write `touch filename.type` . In our case, we will name it hello.cpp .

![](C:\Users\saadu\Videos\Captures\Ubuntu 64-bit - VMware Workstation 17 Player (Non-commercial use only) 1_31_2023 3_24_29 AM.png) 

A new .cpp file with the title "hello" will be created inside NewFolder.

#### 2. Editing the .cpp file

Linux provides two editors

1. Nano
2. Gedit

##### 1. For Nano Editor

To open file in Nano editor, we use `nano filename.type` command.  After typing `nano hello.cpp` , the file will open and we will be able to edit it.

![](C:\Users\saadu\Videos\Captures\Ubuntu 64-bit - VMware Workstation 17 Player (Non-commercial use only) 1_31_2023 3_30_55 AM.png)

Press **Ctrl+S** and then press **Y** to save the file.

##### 2. For Gedit Editor

Similarly to open file in gedit editor, we use `gedit filename.type` command. 

![](C:\Users\saadu\Videos\Captures\Ubuntu 64-bit - VMware Workstation 17 Player (Non-commercial use only) 1_31_2023 3_36_12 AM.png)

Press **Ctrl+S** to save the files.

#### 3. Compiling the .cpp File

- To make preprocessed, assembly and machine file of the .cpp program, type `g++ hello.cpp --save-temps` and press **Enter Key**. It will create `.ii` , `.s` and `.o` files.

  ![](C:\Users\saadu\Videos\Captures\Ubuntu 64-bit - VMware Workstation 17 Player (Non-commercial use only) 1_31_2023 3_48_40 AM.png)

##### Reading Different Type of Files:

- For reading preprocessed file, type `cat filename.ii` and press **Enter Key**. 
- For reading assembly file, type `cat filename.s` and press **Enter Key**.
- For reading machine file, type `cat filename.o` and press **Enter Key**.

#### Executing .cpp File

To execute the .cpp file, simply type `g++ filename.cpp -o filename.exe`. It will convert the C++ program file (.cpp) to executable file(.exe).

![](C:\Users\saadu\Videos\Captures\Ubuntu 64-bit - VMware Workstation 17 Player (Non-commercial use only) 1_31_2023 3_59_27 AM.png)

To run the exe file, use `./filename.exe` command.