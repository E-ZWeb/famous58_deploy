# Hardware Drivers

## Drivers on Linux
The linux kernel by default on most distributions has all the necessary drivers and software to run on your hardware.
Therefore very little work should have to be done to setup your hardware. The exceptions are few.

### Graphics Cards
  - This is the main exception to the rule. Graphics card vendors typically keep their documentation hidden from developers so the Linux Kernel Doesn't contain drivers for AMD and Nvidia graphics cards by default. 
  - Recently however AMD has started pushing code for their graphics cards to Linux
    - Most new AMD graphics cards do not require additional drivers.
### Network Cards
- There are a few exotic Wifi cards which require additional drivers to be installed. However since this is such a rare occurence now it will not be covered in depth. If you do encounter an issue just google the model with the keywords "driver linux". Each card will likely be a special case. 

### Other
- For anything else you encouter driver issues with just google the hardware model with the keywords "driver linux". You are likely to find a solution.


## Nvidia Graphics Drivers

### Do you need them?
- You only need to install the proprietary nvidia drivers if you use applications that use the GPU heavily. 
  - Games
  - Graphics Editing
  - Video Editing
  - etc.

- A good way to find out if you need them is to just use your system as you normally would.
  - If you encounter no issues then you probably don't need the drivers. The default drivers should suffice. 
  - If you do however encounter graphics issues you should install them. 

### How to install them

#### On Kubuntu
    - If you chose kubuntu as your distro then it's quite easy

1. Open the applications menu in the bottom left. 
2. Search for "Driver Manager"
3. Open the "Driver Manager" application
4. Wait for it to scan for your hardware. 
5. It should show some options for drivers. 
6. Select the one labaled "NVIDIA driver" with the latest version number.
   - It will usually say "(recommended)" next to the best option
7. Click "Apply"
8. Wait for it to finish applying
9. Wait for it to reload
10. It will provide an prompt to restart.
    1.  Click it and restart your PC
11. Now your graphics drivers should be installed and working.
    1.  To ensure it worked search for "Nvidia X server settings" in the applications menu
    2.  If the installation worked it should appear and when you open it it should look something like this. 

12. Consider installing Steam and playing Dota 2 to test out the graphics driver.
    - The reason for using Dota 2 is because it uses many features of the drivers making it a good way to test.
    - If you have a powerful card Dota 2 should run smoothly with no issues. 

- If you do encounter issues you need to seek support from Nvidia.
  - Nvidia is responsible for making these drivers available to you as a consumer. 


#### On other distros
- Most distros provide detailed instructions to setup graphics drivers
- for most Ubuntu derivatives like kubuntu it should be a similar process as above.

#### I need newer graphics drivers than what I found in the driver manager. 

- If you are a serious gamer or use graphically intense software you may want to have the absolute latest drivers.
- Ubuntu handbook provides the most up-to-date instructions to install an additional software source for Nvidia graphics drivers. http://ubuntuhandbook.org/index.php/2019/03/install-nvidia-418-43-g-sync-support-ubuntu-18-04/


#### Additional help
- If you have issues with the drivers consider looking for a solution and if you can't find anything report your issue on the nvidia linux forums
  - https://devtalk.nvidia.com/default/board/98/