# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
### Name: SANJUSHRI A
### Reg No: 212223040187
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## **Design Steps:**

### **Step 1: Install  VirtualBox**

### **Installation Steps:**
1. Download the **Windows hosts** `.exe` file from the official VirtualBox website.  
2. Run the installer and follow the on-screen instructions.  
3. Once installed, launch VirtualBox to verify the installation.


### **Step 2: Install Kali Linux on VirtualBox**
🔗 **Download Kali Linux VM**: [Click Here](https://www.kali.org/get-kali/#kali-virtual-machines)  

### **Installation Steps:**
1. Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).  
2. Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM. 
3. Go to Settings > Storage, click Empty under Controller: IDE. 
4. Select Graphical Install, follow the prompts to set language, location, username, and password.
5. Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.


### **Step 3: Install Sleuth Kit (CLI-based Forensic Tools)**
🔗 **Download Sleuth Kit**: [Click Here](https://sleuthkit.org/download.php)  

### **Installation Steps:**
1. Download the **Windows ZIP package** from the official website.  
2. Extract the ZIP folder and move it to a suitable directory (e.g., `C:\sleuthkit`).  
3. Add the **bin folder** to Windows PATH:
   - Open **Control Panel** → **System** → **Advanced System Settings**.  
   - Click **Environment Variables** → Edit **Path**.  
   - Add the Sleuth Kit `bin` folder path and save changes.  
4. Verify installation by running:
   ```sh
   fls -version

## OUTPUT:
**VIRTUAL BOX:**

<img width="953" height="785" alt="Screenshot 2025-08-17 165318" src="https://github.com/user-attachments/assets/ad744be3-74e4-48ce-ad28-ff865a9a2448" />




**KALI LINUX:**

<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/3371d342-ace1-42d7-8b07-bf5bff0d9c7c" />




**SLEUTH-KIT:**

<img width="962" height="643" alt="image" src="https://github.com/user-attachments/assets/bb388221-1474-4b1c-9761-66819543612f" />




## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
