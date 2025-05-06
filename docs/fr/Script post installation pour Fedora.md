# Script de post installation pour Fedora

Script de post-installation qui va installer certains logiciels, rajouter quelques fichiers tels que des fonds d'écran et mettre à jour le système en un seul clic pour Fedora (toutes versions desktop).

## Applis installées

### Extensions

Les extensions sont utiles pour avoir une meilleur approche de Fedora.
Celles-ci sont installées :

- Dash-to-dock (barre des tâches sur le bureau)

### Applications

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
- cool-retro-term gparted
- btrfs-assistant
- git

#### Flatpak (Dépôt Flathub)

- VLC
- SongRec
- SoundConverter
- ExtensionManager
- Warehouse
- Flatseal

### Composants RPM Fusion

- rpmfusion-free-appstream-data
- rpmfusion-nonfree-appstream-data
- rpmfusion-free-release-tainted
- rpmfusion-nonfree-release-tainted

### Codecs

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

## Autres

De plus, ce script ajuste la configuration de DNF pour rendre plus rapide les mises à jour et les installations de logiciels en lignes de commande.

Mises à jour des flatpaks, des applications et du système. Vous pouvez lancer le script autant de fois que nécessaire.

De plus, ce script offre la possibilité de configurer GNOME. Pour plus d'informations, voir [Script de customisation](#script-de-customisation).

## Lancer le script

**_VEUILLEZ AVOIR UNE CONNEXION STABLE ET ASSEZ RAPIDE (min. 2 Mo/s)_**

**_LE SCRIPT PEUT ETRE LANCÉ PLUSIEURS FOIS_**

Lancer le programme :

- Clic droit sur le fichier "lancer-la-configuration-de-Fedora.sh"

- Appuyez sur "Exécuter comme programme"

Si vous voulez seulement éxécuter le script de customisation de GNOME, allez dans le dossier config-fedora et éxécutez le fichier gnome-customization.sh

Suite à la configuration, des alias seront disponibles. Un alias est une chaine de caractères qui va exécuter une commande longue pour gagner du temps. Voici ceux que vous pourrez utiliser :

|    Exécutez   |        pour effectuer          |                                      Exemple                                          |
|:--------------|:-------------------------------|:--------------------------------------------------------------------------------------|
|   maj         |   sudo dnf upgrade -y          |   maj -> mise à jour du système                                                       |
|   install     |   sudo dnf install -y          |   install **_app_** -> installe l'application **_app_**                               |
|   remove      |   sudo dnf remove -y           |   remove **_app_** -> supprimer l'application **_app_**                               |
|   fmaj        |   flatpak update -y            |   fmaj -> mise à jour de flatpak                                                      |
|   fsearch     |   flatpak search               |   fs **_mot-cle_** -> recherche les flatpak contenant **_mot-cle_**                   |
|   finstall    |   flatpak install flathub -y   |   finstall **_ID_** -> installe le flatpak avec l'identifiant **_ID_** depuis flathub |
|   fremove     |   flatpak remove -y            |   fremove **_ID_** -> supprime le flatpak avec l'identifiant **_ID_**                 |

## Script de customisation

La customisation de GNOME va :

- si vous le voulez rajouter des fonds d'écrans et/ou des fonds d'écrans dynamiques

- Rajouter les boutons minimiser et maximiser sur les fenêtres

- Augmenter la limite du son

- Afficher le calendrier sur le panneau supérieur

- Modifier le format date et heure :

  - Afficher la date
  
  - Afficher les secondes
  
  - Afficher le jour de la semaine
  
  - Heure au format 24h
  
- Supprimer les fichiers temporaires et de la corbeille

- Désactiver l'ouverture du dossier lorsqu'un fichier est glissé dedans

- Activer le double-clic

- Afficher les dossiers avant les fichiers

- Désactiver la surlignement de la ligne actuelle

- Afficher les numéros de ligne dans l'éditeur de texte

- Activer l'extension Dash-to-Dock

### Personnalisation de Fedora

Pour les fonds d'écrans, un dossier wallpapers à été crée dans ~/Images/

Dans ce même dossier, vous allez trouver un dossier screenshots_dynamic_wallpapers qui contient les aperçus des changements fonds d'écrans dynamiques.

Vous pouvez choisir un fond d'écran dynamique :

- clic droit sur le bureau

- Modifier l'arrière plan...

- sélectionnez un fond d'écran avec une horloge en bas à gauche de l'image pour sélectionner un fond d'écran dynamique

Si vous souhaitez personnalisez Fedora plus en profondeur, regardez cette [playlist](https://youtube.com/playlist?list=PL-xp5bZmT8148dNSbLTQBhEntfp_HeXfu&si=HTQfktPsC7zkXVnr).

## Liens

[Lien du repo](https://github.com/Loanbrwsk1/FR_Script_de_post_installation_Linux)
