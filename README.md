@@ -0,0 +1,58 @@
Basic Virtual Machine Setup Description:
Step 1: Download and Install VirtualBox or VMware
  VirtualBox: Download and install VirtualBox from the official website.
 
Step 2: Create a New Virtual Machine
1.	VirtualBox:
  o	Open VirtualBox and click on the "New" button.+
  o	Enter a name for your virtual machine, select the type and version of the operating system you want to install, and click "Next".
  o	Allocate memory (RAM) for the virtual machine and click "Next".   
  o	Create a virtual hard disk and specify its size and location, then click "Create".   
Step 3: Install the Operating System
  1.	VirtualBox:
    o	Select the newly created virtual machine and click "Start".  
    o	Mount the ISO file of the operating system when prompted and follow the installation instructions.
Step 4: Set Up a Basic Environment for Running Applications
  1.	Install Additional Drivers:
    •	 Install any additional drivers required for hardware compatibility.      
    •	In the terminal we’ll use the Ubuntu drivers command to manage and install drivers     
    •	If you want to install drivers automatically you can run the command – sudo ubuntu-drivers install     
    •	If you want to install a specific driver you can use the install command followed – sudo ubuntu-drivers install driver-name
    •	You can also install proprietary drivers in Ubuntu 22.04LT 
    •	In the virtual machine but if you have a Nvidia graphics card installed on your machine for example drivers will appear like
 
Step 5: Install Google Chrome using Command Prompt (CMD)
  1.	Open Command Prompt as Administrator:
    o	Press Win + X and select "Command Prompt (Admin)" or "Windows PowerShell (Admin)".
  2.	Download the Chrome Installer:
    o	In the Command Prompt, type the following command to download the Chrome installer using powershell:
     -- powershell -command "Invoke-WebRequest -Uri 'https://dl.google.com/chrome/install/latest/chrome_installer.exe' -OutFile 'chrome_installer.exe'"
  
  
  3.	Run the Chrome Installer:
    o	After the download is complete, run the installer using the following command:
      --start chrome_installer.exe
  
  4.	Follow the Installation Instructions:
    o	The Google Chrome installer will open. Follow the on-screen instructions to complete the installation.
Step 6: Install Necessary Software
    •	For installing the software – sudo apt install and my package name
   
 
