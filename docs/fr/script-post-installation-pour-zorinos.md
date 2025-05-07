# **Script post installation ZorinOS**

Script qui va installer certains logiciels, rajouter quelques fichiers tels que des fonds d'écran et mettre à jour le système en un seul clic pour ZorinOS (toutes versions desktop).

## **Applis installées**

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

### Flatpak (Dépôt Flathub)

- VLC
- SongRec
- SoundConverter
- ExtensionManager
- Warehouse
- Flatseal

## **Autres**

Mises à jour des flatpaks, des applications et du système. Vous pouvez lancer le script autant de fois que nécessaire.

De plus, ce script offre la possibilité de configurer GNOME. Pour plus d'informations, voir [script de customisation](#script-de-customisation)

## **Lancer le script**

**_VEUILLEZ AVOIR UNE CONNEXION STABLE ET ASSEZ RAPIDE (min. 2 Mo/s)_**

**_LE SCRIPT PEUT ETRE LANCÉ PLUSIEURS FOIS_**

Lancer le programme :

- Clic droit sur le fichier _lancer-la-configuration-de-ZorinOS.sh_

- Appuyez sur _Exécuter comme programme_

Si vous voulez seulement éxécuter le script de customisation de GNOME, allez dans le dossier _config-zorin_ et éxécutez le fichier _gnome-customization.sh_.

## **Script de customisation**

La customisation de GNOME va :

-Augmenter la limite du son

- Afficher le calendrier sur le panneau supérieur

- Modifier le format date et heure :

  - Afficher la date
  
  - Afficher les secondes
  
  - Afficher le jour de la semaine

  - Heure au format 24h
  
- Supprimer les fichiers temporaires et de la corbeille

- Désactiver la surlignement de la ligne actuelle

- Afficher les numéros de ligne dans l'éditeur de texte

Suite à la configuration, des alias seront disponibles. Un alias est une chaine de caractères qui va exécuter une commande longue pour gagner du temps. Voici ceux que vous pourrez utiliser :

|    Exécutez   |        pour effectuer          |                                      Exemple                                          |
|:--------------|:-------------------------------|:--------------------------------------------------------------------------------------|
|   maj         |   sudo apt upgrade -y          |   maj -> mise à jour du système                                                       |
|   install     |   sudo apt install -y          |   install **_app_** -> installe l'application **_app_**                               |
|   remove      |   sudo apt remove -y           |   remove **_app_** -> supprimer l'application **_app_**                               |
|   fmaj        |   flatpak update -y            |   fmaj -> mise à jour de flatpak                                                      |
|   fsearch     |   flatpak search               |   fs **_mot-cle_** -> recherche les flatpak contenant **_mot-cle_**                   |
|   finstall    |   flatpak install flathub -y   |   finstall **_ID_** -> installe le flatpak avec l'identifiant **_ID_** depuis flathub |
|   fremove     |   flatpak remove -y            |   fremove **_ID_** -> supprime le flatpak avec l'identifiant **_ID_**                 |

### **Personnalisation de ZorinOS**

Pour les fonds d'écrans, un dossier wallpapers à été crée dans _~/Images/_

Dans ce même dossier, vous allez trouver un dossier _screenshots_dynamic_wallpapers_ qui contient les aperçus des fonds d'écrans dynamiques.

Vous pouvez choisir un fond d'écran dynamique :

- clic droit sur le bureau

- modifier le fond d'écran

- sélectionnez un fond d'écran avec une horloge en bas à droite de l'image pour sélectionnez un fond d'écran dynamique

Si vous souhaitez personnalisez ZorinOS plus en profondeur, regardez cette [playlist](https://youtube.com/playlist?list=PL-xp5bZmT8148dNSbLTQBhEntfp_HeXfu&si=HTQfktPsC7zkXVnr).

## **Liens**

[Lien du repo](https://github.com/Loanbrwsk1/FR_Script_de_post_installation_Linux)
