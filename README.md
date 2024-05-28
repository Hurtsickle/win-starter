## win-starter
A personal guide to installing Windows 10 and setting up.

#Installing Windows on a USB with a Windows PC
- Navigate to https://www.microsoft.com/en-us/software-download/windows10%20
- Download the installation media
- Run the installation media found in your Downloads folder
- Proceed with installation as normal

#Installing Windows on a USB with a Linux and MacOS
- Navigate to https://www.microsoft.com/en-us/software-download/windows10%20
- Download the .iso file for Windows 10
- Navigate to https://etcher.balena.io/ and install Etcher
- Run Etcher and choose your USB drive
- Drag and drop the .iso file into the left side or click on "Flash from file" to choose the .iso in your installed directory.
- Click "Flash" and wait until it's finished


#Installing Windows 10
- Insert your USB in your Computer or Laptop before turning it on
- Spam your motherboard manufacturer's boot key upon startup (Search up your laptop brand or Motherboard brand or refer to my list below/)
- Select your USB which should be shown in the boot menu
- Proceed with Windows 10 installation
  - If you have any drives you would like to clear, you can format them during installation or delete all the partitions in the drive.
- After it has finished you should boot into the Windows 10 setup screen with Cortana greeting you.

#Windows 10 setup
- I prefer to set up my Windows 10 system by removing my Wi-Fi dongle which allows me to select "I don't have internet". This makes it so that Windows doesn't bombard me with tons of bloatware and updates before I even get into my system.
- I would recommend deselecting every option where Microsoft asks for permissions to things such as location data and handwritting data.

#My instant to-do list:
- VC Redist 2013
- VC Redist 2015-2022 package
- .NET 8
- Turn off mouse acceleration (Search "Change the mouse pointer display or speed" and uncheck "Enhance Pointer Precision".)
- Disable Game Mode and Game bar (Windows+I > Gaming > Disable Game bar > Game Mode > Disable Game Mode
- Re-enable the Internet in-order to install required Windows Updates (Install your GPU drivers before this if you can by using another USB or disconnecting the USB and connecting it to another PC to download, this just makes it so Windows won't have to install the basic display driver.)
- Install the GPU driver
- Change my refresh rate to the highest possible (Windows+I > System > Display > Scroll-down to "Advanced Display Settings" > Refresh rate (Only available after you install your GPU drivers).
- Restart PC when required as some Windows updates require you to restart.
- (Optional) I personally use TransluscentTB for every Windows system in order to make my Taskbar transparent found here: https://github.com/TranslucentTB/TranslucentTB
- (Optional) Declutter the Taskbar (Right click the taskbar and disable Cortana, Task View, Search > Hidden, News and interests > Turn off.)
- (Optional) Reduce the space the Taskbar takes (Windows+I > Personalisation > Taskbar > Use small taskbar buttons.)






#Manufacturer Boot Keys
- HP = Esc/F9
- Dell = F12
- Asus = Esc/F8/Del
- Acer = F12
- MSI = F11
- Gigabyte = F12
- ASrock = Esc/F11
- Lenovo = F12
