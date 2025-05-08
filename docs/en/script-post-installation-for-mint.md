# **Post installation script for Mint**

A post-installation script that installs certain applications, adds some files such as wallpapers, and updates the system in a single click for Mint (all desktop versions).

## **Installed Applications**

### **Applications**

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
- numlockx  
- git  

#### Flatpak (Flathub repository)

- VLC  
- SongRec  
- SoundConverter  
- Warehouse  
- Flatseal  

## **Other**

It updates flatpaks, applications, and the system. You can run the script as many times as needed.

This script also offers the possibility to configure Cinnamon. For more information, see the [Customization Script](#customization-script).

## **Running the Script**

**_PLEASE ENSURE A STABLE AND FAST CONNECTION (min. 2 MB/s)_**

**_THE SCRIPT CAN BE RUN MULTIPLE TIMES_**

To run the program:

- Double-click the file _launch-the-configuration-of-Mint.sh_

- Click _Launch in Terminal_ on the far right

You can enable the _Enable Num Lock_ option in the login screen settings to lock the numeric keypad on the lock screen.

If you only want to run the CINNAMON customization script, go to the _config-lm_ folder and execute the _cinnamon-customization.sh_ file.

## **Customization Script**

CINNAMON customization will:

- Optionally add wallpapers and/or dynamic wallpapers  
- Increase volume limit  
- Change the date and time format:
  - Show the date  
  - Show seconds  

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

### **Mint Customization**

To display the `wallpapers` folder from _~/Images/_ in the wallpaper settings window:

- Right-click on the desktop > change desktop background  
- Click the "+" at the bottom left  
- Go to _Images_  
- Select `wallpapers`  
- Click _Open_ in the bottom right  

If you'd like to further customize Mint, check this [playlist](https://youtube.com/playlist?list=PL-xp5bZmT8148dNSbLTQBhEntfp_HeXfu&si=HTQfktPsC7zkXVnr).

## **Links**

[Repository link](https://github.com/Loanbrwsk1/FR_Script_de_post_installation_Linux)
