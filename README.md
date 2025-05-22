# NAME:T.KAVINAJAI
# REGISTER NO: 212223100020
# Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration
## AIM:
To install Autopsy on Kali Linux and analyze disk images, files, and folder configurations for digital forensic purposes.


# DESIGN STEPS:
# Step 1: Install VirtualBox
🔗
Installation Steps:
1.Download the Windows hosts .exe file from the official VirtualBox website.
2.Run the installer and follow the on-screen instructions.
3.Once installed, launch VirtualBox to verify the installation.

# Step 2: Install Kali Linux on VirtualBox
🔗 Download Kali Linux VM: Click Here

Installation Steps:
1.Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).
2.Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM.
3.Go to Settings > Storage, click Empty under Controller: IDE.
4.Select Graphical Install, follow the prompts to set language, location, username, and password.
5.Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.

# Step 3: Install Autopsy (GUI-based Forensic Tool)
🔗 Download Autopsy: Click Here

Installation Steps:
Download the Autopsy Windows Installer from the official website.
Extract the ZIP file and open the bin folder.
Run autopsy.exe and set up a new forensic case for analysis.

# Step 4: Install Sleuth Kit (CLI-based Forensic Tools)
🔗 Download Sleuth Kit: Click Here

Installation Steps:
1.Download the Windows ZIP package from the official website.
2.Extract the ZIP folder and move it to a suitable directory (e.g., C:\sleuthkit).
3.Add the bin folder to Windows PATH:
4.Open Control Panel → System → Advanced System Settings.
5.Click Environment Variables → Edit Path.
6.Add the Sleuth Kit bin folder path and save changes.
7.Verify installation by running:
```
fls -version
```
# Step 5: Create & Configure a Virtual Hard Disk (VHD) in Windows
1.Press Win + X, Select Disk Management.
2.Click Action > Create VHD.
3.Choose a location and set a disk size (e.g., 10GB+).
4.Select Fixed Size or Dynamically Expanding and click OK.
5.In Disk Management, find your new disk (marked as "Not Initialized") -> Right-click the new disk → Initialize Disk → Select MBR.
6.Right-click Unallocated Space → New Simple Volume → Format the disk -> Click next → Finish.

# OUTPUT:
# VIRTUAL BOX:
![image](https://github.com/user-attachments/assets/4b3df5c5-a43f-4e09-8d65-cd5515eaef79)

# VIRTUAL Machine(Kali Linux)
![image](https://github.com/user-attachments/assets/a3a398fa-205c-4904-9b61-49a7840fcf7b)

# AUTOPSY
![image](https://github.com/user-attachments/assets/3035d437-c444-4858-b28c-1279f3e598c8)

# Sleuth kit
![image](https://github.com/user-attachments/assets/72d0dc59-a398-4f64-acff-b533e9e36c25)

# creation of virtual hard disk:
![image](https://github.com/user-attachments/assets/da2d1208-66e3-4806-abe1-54d82b396da2)



# analysis of images:
![image](https://github.com/user-attachments/assets/aa3f5fdd-5bfa-4820-8f38-e44ad8cffedc)

# click on os account:
![image](https://github.com/user-attachments/assets/e6190e38-1216-4d25-b028-3cf78a97b393)

# GENERATE REPORTS:
![image](https://github.com/user-attachments/assets/da330137-aff5-4562-8506-b20cf7ca4ae0)
![image](https://github.com/user-attachments/assets/3d8c7959-6575-4750-bdb9-247bb6d8caf2)
![image](https://github.com/user-attachments/assets/f0c3b447-a6fa-4e1e-a33e-ddfaadeabe56)






## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
