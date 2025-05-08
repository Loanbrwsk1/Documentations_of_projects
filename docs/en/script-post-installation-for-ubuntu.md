# **Post installation script for Ubuntu**

A script that installs certain applications, adds some files such as wallpapers, and updates the system in a single click for Ubuntu (all desktop versions).

## **Installed Applications**

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
- git  

### Flatpak (Flathub repository)

- VLC  
- SongRec  
- SoundConverter  
- ExtensionManager  
- Warehouse  
- Flatseal  

## **Other**

It updates flatpaks, applications, and the system. You can run the script as many times as needed.

This script also offers the possibility to configure GNOME. For more information, see the [Customization Script](#customization-script).

## **Running the Script**

**_PLEASE ENSURE A STABLE AND FAST CONNECTION (min. 2 MB/s)_**

**_THE SCRIPT CAN BE RUN MULTIPLE TIMES_**

To run the program:

- Right-click on the file _launch-the-configuration-of-Ubuntu.sh_

- Click _Run as a program_

If you only want to run the GNOME customization script, go to the _config-ubuntu_ folder and execute the _gnome-customization.sh_ file.

## **Customization Script**

GNOME customization will:

- Increase volume limit  
- Change the date and time format:
  - Show the date  
  - Show seconds  
  - Show the day of the week  
  - Use 24-hour format  
- Delete temporary and trash files  
- Disable current line highlighting  
- Show line numbers in the text editor  

After configuration, aliases will be available. An alias is a shortcut string that runs a long command to save time. Here are the available ones:

| Run           | Executes                        | Example                                                                 |
|:--------------|:--------------------------------|:------------------------------------------------------------------------|
| maj           | sudo apt upgrade -y             | maj -> system update                                                    |
| install       | sudo apt install -y             | install **_app_** -> installs the app **_app_**                         |
| remove        | sudo apt remove -y              | remove **_app_** -> removes the app **_app_**                           |
| fmaj          | flatpak update -y               | fmaj -> flatpak update                                                  |
| fsearch       | flatpak search                  | fsearch **_keyword_** -> search for flatpaks matching **_keyword_**     |
| finstall      | flatpak install flathub -y      | finstall **_ID_** -> install flatpak with ID from flathub              |
| fremove       | flatpak remove -y               | fremove **_ID_** -> remove the flatpak with ID                          |

### **Ubuntu Customization**

For wallpapers, a `wallpapers` folder is created in _~/Images/_.

Inside it, you'll find a _screenshots_dynamic_wallpapers_ folder with previews of dynamic wallpapers.

To choose a dynamic wallpaper:

- Right-click on the desktop  
- Change the wallpaper  
- Select a wallpaper with a clock icon in the bottom right (indicates dynamic)  

If you'd like to further customize Ubuntu, check this [playlist](https://youtube.com/playlist?list=PL-xp5bZmT8148dNSbLTQBhEntfp_HeXfu&si=HTQfktPsC7zkXVnr).

## **Links**

[Repository link](https://github.com/Loanbrwsk1/EN_Post_installation_script_for_Linux)
