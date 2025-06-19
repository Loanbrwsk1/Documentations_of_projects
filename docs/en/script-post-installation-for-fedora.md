# **Post installation script for Fedora**

A post-installation script that installs certain applications, adds some files such as wallpapers, and updates the system in a single click for Fedora (all desktop versions).

## **Installed Applications**

### **Extensions**

Extensions enhance the Fedora experience. These are installed:

- Dash-to-dock (taskbar on the desktop)

### **Applications**

#### RPM

- aspell-fr  
- amd-ucode-firmware  
- gnome-tweaks  
- file-roller  
- dconf-editor  
- gnome-boxes  
- ShellCheck  
- htop  
- neofetch  
- screenfetch  
- fastfetch  
- inxi  
- nfs-utils  
- sl  
- nyancat  
- ecryptfs-utils  
- cool-retro-term  
- gparted  
- btrfs-assistant  
- git  

#### Flatpak (Flathub repository)

- VLC  
- SongRec  
- SoundConverter  
- ExtensionManager  
- Warehouse  
- Flatseal  

### **RPM Fusion Components**

- rpmfusion-free-appstream-data  
- rpmfusion-nonfree-appstream-data  
- rpmfusion-free-release-tainted  
- rpmfusion-nonfree-release-tainted  

### **Codecs**

- gstreamer1-plugins-base  
- gstreamer1-plugins-good  
- gstreamer1-plugins-bad-free  
- gstreamer1-plugins-good-extras  
- gstreamer1-plugins-bad-free-extras  
- gstreamer1-plugins-ugly-free  
- gstreamer1-plugin-libav  
- gstreamer1-plugins-ugly  
- libdvdcss  
- gstreamer1-plugin-openh264  

## **Others**

Additionally, this script adjusts the DNF configuration to speed up software updates and installations via the command line.

It updates flatpaks, applications, and the system. You can run the script as many times as needed.

This script also offers GNOME configuration. For more details, see [Customization Script](#customization-script).

## **Running the Script**

**_PLEASE ENSURE A STABLE AND FAST CONNECTION (min. 2 MB/s)_**

**_THE SCRIPT CAN BE RUN MULTIPLE TIMES_**

To run the program:

- Right-click the file _launch-the-configuration-of-Fedora.sh_

- Click _Run as a program_

If you only want to run the GNOME customization script, go to the _config-fedora_ folder and execute the _gnome-customization.sh_ file.

## **Customization Script**

GNOME customization includes:

- Optionally adding wallpapers and/or dynamic wallpapers  
- Adding minimize and maximize buttons to windows  
- Increasing volume limits  
- Displaying the calendar in the top panel  
- Changing date and time format:
  - Show the date  
  - Show seconds  
  - Show day of the week  
  - Use 24-hour format  
- Deleting temporary files and trash  
- Disabling folder auto-open when a file is dragged into it  
- Enabling double-click to open files  
- Showing folders before files  
- Disabling highlight of the current line  
- Showing line numbers in the text editor  
- Enabling the Dash-to-Dock extension  

After configuration, aliases will be available. An alias is a shortcut string that runs a long command to save time. Here are the available ones:

| Run           | Executes                        | Example                                                                 |
|:--------------|:--------------------------------|:------------------------------------------------------------------------|
| maj           | sudo dnf upgrade -y             | maj -> system update                                                    |
| install       | sudo dnf install -y             | install **_app_** -> installs the app **_app_**                         |
| remove        | sudo dnf remove -y              | remove **_app_** -> removes the app **_app_**                           |
| fmaj          | flatpak update -y               | fmaj -> flatpak update                                                  |
| fsearch       | flatpak search                  | fsearch **_keyword_** -> search for flatpaks matching **_keyword_**     |
| finstall      | flatpak install flathub -y      | finstall **_ID_** -> install flatpak with ID from flathub              |
| fremove       | flatpak remove -y               | fremove **_ID_** -> remove the flatpak with ID                          |

### **Fedora Customization**

Inside `~/Pictures/`, there's a `screenshots_dynamic_wallpapers` subfolder with previews of the dynamic wallpapers.

To choose a wallpaper:

- Right-click on the desktop

- Click on _Change Background..._

- Choose a wallpaper with a clock icon in the lower-left corner (indicates dynamic)  

If you'd like to further customize Fedora, check this [playlist](https://youtube.com/playlist?list=PL-xp5bZmT8148dNSbLTQBhEntfp_HeXfu&si=HTQfktPsC7zkXVnr).

## **Links**

[Repository link](https://github.com/Loanbrwsk1/EN_Post_installation_script_for_Linux)
