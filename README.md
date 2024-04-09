# OnePlus-7t-Rooting
Follow the steps if your phone's build numver is Oxygen OS 11.0.9.1.HD65AA  

# Disclaimer  
* This project doesn't encourage or promot any illegal activities!   
* Follow this at your own risk.  
* Take backup of all data before jump.

# Requirements
* A Windows 10 PC/Laptop
*  OnePlus 7t device
* Type-c cable (OnePlus Compatible)

# Download Drivers & Tools
* adb & fastboot
* Platform tools 
* Magisk Manager v25.2
* boot.zip

# Check Device Info  
![Screenshot](https://github.com/hmonojit/OnePlus-7t-Rooting/assets/164205830/dcb0091a-b558-4898-a6e9-816db1e78613)

# Unlocking Bootloader (it will format your device)  
* IN PHONE  
Settings > About phone > Build number (7 times)  
Settings > System > Developer Options > Turn on OEM unlocking > USB debugging

* IN PC/Laptop  
Unzip Platform tools  
Open cmd in Platform tools folder  
> /adb devices  
> /adb reboot bootloader  
> /fastboot devices  
> /fastboot oem unlocking

* IN PHONE  
Select Unlock The Bootloader using volume down  
Press power button to unlock (Be Patience)  
Complete the set-up process  
Enable Developer Option and USB debugging like last time
Unzip boot.zip to get boot.img
Copy Magisk Manager and boot.img from PC/Laptop > Past in Android Download  
Install Magisk Manager v25.2 > Open > Tap on Install> Select and Patch a File > Select boot.img > LET'S GO  
Copy magisk_patched-xxxxx.img to PC/Laptop  

* IN PC/Laptop
Open cmd in Platform tools folder  
> /adb device   
> /adb reboot bootloader    
> /fastboot flash (drag and drop magisk_patched-xxxxx.img)    
Press the power button (Patience)

holler! Download root checker apk and subscribe me.  

# Check to install Kali Nethunter in OP7T (Coming Soon)
