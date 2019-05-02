## Other distros
If you choose to install something other than Kubuntu 18.04 then you need to head to the home page of your distro and follow their instructions. I will be providing step by step instructions to install and set up Kubuntu here however.

## Installing Kubuntu 18.04 LTS

### Prerequisites
- An internet connection
- A USB stick with at least 4Gb on it
- A PC or laptop with important files backed up ready to be wiped. 
  - Be advised that installing Linux using these instructions will wipe all the data on your PC or laptop to start fresh. So make sure important data is backed up.
- A PC with an operating system to download and write Kubuntu to the USB.
- Patience.

### Download and Install
1. Head to https://kubuntu.org/getkubuntu/ 
2. Click the Download button for the 32 bit or the 64 bit version of Ubuntu 18.04
    - Make sure you select the correct version, this tutorial is designed for Ubuntu 18.04 LTS specifically
    - https://www.howtogeek.com/67241/htg-explains-what-are-md5-sha-1-hashes-and-how-do-i-check-them/

3. Download and install Etcher at https://www.balena.io/etcher/
    - Select the version for your system.
      - Windows includes a portable and an installed version. Both should work.

4. Launch etcher and write Kubuntu to your USB
   1. Plug in your USB flash drive
   2. launch etcher
   3. select the kubuntu .iso disk image by clicking "select image"
   4. select your USB flash drive
        - When selecting the USB make sure you are selecting the correct device. 
          - Consider just unplugging any other USB storage devices to make sure you selected the correct one
          - Etcher will not under normal circumstances show your local drives as an option so there is no reason to fear accidentally writing to your local disk. 

   5. Click "Flash" and wait for etcher to finish writing to the disk. 
   6. Once complete close etcher and safely remove the flash drive

5. plug the USB into the PC you wish to install kubuntu on.
6. Boot the PC and enter the boot menu
   1. Select your USB drive and press enter to boot from it.
      - Unfortunately this process is very different depending on your PC.
        - If you cannot find the boot menu you will need to search online for the correct procedure to access the boot menu
        - sometimes BIOS configuration is required to enable booting from a USB drive. 
   2. Wait for it to boot
7. Once booted you will be asked to choose between "Tru Kubuntu" and "Install Kubuntu"
   - Try kubuntu will allow you to use and test out kubuntu directly from the USB without affecting your local storage.
   - If you choose this there will be an option to install it as you are testing it out. Useful if you need to get some work done while you wait for the installation. 
     - This is a perk of Linux. Windows and MacOSX do not provide this "Live USB" option.
8. Eventually click "Install Kubuntu"
9. You will be asked if you want to "Download updates while installing" and "Install 3rd party software for graphics etc."
   1.  Select both of these options 
   2.  click next
10. Disk Setup
    1.  You will be shown some options for configuring your local disk storage for the installation
    2.  Select "Guided- use entire disk"
        - WARNING: From here on out you will be wiping all data on your local disk. If you still have sensitive data that hasn't been backed up please shutdown the PC and do so then restart. 
    3. Click "Install Now"
11. Time Zone
    1.  You will be shown an interactive world map
    2.  Click on the region you live in to select your time zone
    3.  You can alternatively choose it from the two drop downs
    4.  Click Continue
12. Select your keyboard layout
    1.  In most cases you will probably be using the default US keyboard. In which case just click continue. 
    2.  If you use a different layout, figure out which it is and select the correct one. 
    3.  Click Continue
13. User Info
    1.  Enter a username
        -  Linux usernames are going to be all lowercase
    2.  Enter a password
    3.  Enter a "computer name"
        -  This is the name your computer will broadcast on the network. If you value your privacy choose a name that will not identify you.
    4. Click Continue
14. Wait for Kubuntu to finish installing
    1.  Once complete it will prompt you to either restart now or continue testing out kubuntu
    2.  Click "restart"
    3.  Once it's shutting down unplug the USB and press enter
        1.  If it gets stuck on the shutdown sequence just reboot the PC manually.
15. Boot into your new system
    1.  Once you've logged in everything should be working.
16. If you require graphics drivers for your tasks head on over to drivers.