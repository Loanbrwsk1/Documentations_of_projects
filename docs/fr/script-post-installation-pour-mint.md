# **Script post installation Mint**

Script de post-installation qui va installer certains logiciels, rajouter
quelques fichiers tels que des fonds d'écran et mettre à jour le système en un
seul clic pour Mint (toutes versions desktop).

## **Applis installées**

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

#### Flatpak (Dépôt Flathub)

- VLC
- SongRec
- SoundConverter
- Warehouse
- Flatseal

## **Autre**

Mises à jour des flatpaks, des applications et du système. Vous pouvez lancer le script autant de fois que nécessaire.

De plus, ce script offre la possibilité de configurer Cinnamon. Pour plus d'informations, voir [script de customisation](#script-de-customisation).

## **Lancer le script**

**_VEUILLEZ AVOIR UNE CONNEXION STABLE ET ASSEZ RAPIDE (min. 2 Mo/s)_**

**_LE SCRIPT PEUT ETRE LANCÉ PLUSIEURS FOIS_**

Lancer la programme:

- Double-cliquez sur le fichier _lancer-la-configuration-de-Mint.sh_

- Cliquez sur _Lancer dans un terminal_ tout à droite

Vous pouvez activer l'option _Activer le verrouillage du pavé numérique_ dans les options de l'écran de connexion (paramètres) pour verrouiller le pavé numérique sur l'écran de verrouillage.

Si vous voulez seulement exécuter le script de customisation de CINNAMON, allez dans le dossier _config-lm_ et éxécutez le fichier _cinnamon-customization.sh_.

## **Script de customisation**

La customisation de CINNAMON va :

- si vous le voulez rajouter des fonds d'écrans et/ou des fonds d'écrans dynamiques

- Augmenter la limite du son

- Modifier le format date et heure :

  - Afficher la date
  
  - Afficher les secondes

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

### **Personnalisation de Mint**

Pour afficher le dossier wallpapers _~/Images/_ dans la fenêtre des fonds d'écran :

- clic droit sur le bureau > modifier l'arrière plan du bureau

- appuyez sur le "+" en bas à gauche

- allez dans _Images_

- séléctionnez wallpapers

- cliquez sur ouvrir en bas à droite

Si vous souhaitez personnaliser Mint plus en profondeur, regardez cette [playlist](https://youtube.com/playlist?list=PL-xp5bZmT8148dNSbLTQBhEntfp_HeXfu&si=HTQfktPsC7zkXVnr).

## **Liens**

[Lien du repo](https://github.com/Loanbrwsk1/FR_Script_de_post_installation_Linux)
