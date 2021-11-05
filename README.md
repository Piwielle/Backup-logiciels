# Backup-logiciels


## Navigateurs
 - [**Google Chrome**](#google-chrome)
 - [**Microsoft Edge**](#microsoft-edge)
 - [**Mozilla Firefox**](#mozilla-firefox)
## Installation de jeux
 - [**Steam**](#steam)
 - [**Epic Games Store**](#epic-games-store)
 - [**Uplay**](#uplay)
## Paramètres de jeux
 - [**CS:GO**](#cs-go)
 - [**Valorant**](#valorant)
 - [**R6S**](#r6s)
 - [**Fortnite**](#fortnite)
 - [**League of Legends**](#league-of-legends)
 - [**PUBG**](#pubg)
 - [**Apex Legends**](#apex-legends)
 - [**CoD: Warzone**](#cod-warzone)
 - [**Minecraft**](#minecraft)
## Logiciels
 - [**MSI AFterburner**](#msi-afterburner)
 - [**OBS Studio**](#obs-studio)

# Navigateurs

## Google Chrome
Être connecté avec un compte Google, et avoir synchronisé les favoris. Paramètres -> Services Google/synchronisation -> Gérer les contenus que vous synchronisez, puis choisir ce qui vous intéresse. Vos favoris, extensions, thèmes, onglets, etc seront ensutie synchronisés.
<details>
  <summary>Exemple image (cliquer)</summary> 
  
  ![sync chrome](https://i.imgur.com/Xu7gh0t.png)
</details>

## Microsoft Edge
Être connecté avec un compte Microsoft, et avoir synchronisé les favoris.
paramètres -> Synchroniser
<details>
  <summary>Exemple image (cliquer)</summary> 
  
![sync edge](https://i.imgur.com/mHULZFB.png)
</details>

## Mozilla Firefox
Être connecté avec un compte Mozilla, et avoir synchronisé les favoris.
Options -> Sync
<details>
  <summary>Exemple image (cliquer)</summary> 
  
![sync firefox](https://i.imgur.com/01w20de.png)
</details>

## Note
Si vous ne souhaitez pas vous connecter aux navigateurs, il est est aussi possible d'exporter vos favoris, de les sauvegarder quelque part, puis de les ré importer après. Par exemple pour Chrome, MAJ + CTRL + O pour ouvrir le gestionnaire de favoris, puis utiliser le menu en haut à droite (les 3 petit points verticaux) pour exporter les favoris.

# Installation de jeux

## Steam
Il est possible de déplacer facilement et librement des jeux de Steam. Pour ce faire, il faut que la destination soit un dossier steam.

Paramètres -> Téléchargements -> Dossiers Steam

Une fois dans ce menu, vous pouvez créer autant de dossiers Steam que vous voulez, à l'endroit que vous voulez.
On peut ensuite simplement déplacer des jeux d'un dossier Steam à un autre.

Clic droit sur un jeu -> Propriétés -> Fichiers locaux -> Déplacer le dossier d'installation
<details>
  <summary>Exemple GIF (cliquer)</summary> 
  
![steam déplacer](https://i.imgur.com/j7t6fbL.gif)
</details>

Pour sauvegarder absolument tous les réglages des jeux et les sauvegardes, il faut aussi sauvegarder le dossier userdata qui est situé dans le dossier de Steam.  
L'empacement par défaut est **C:\Program Files (x86)\Steam** mais vous l'avez peut-être installé ailleurs.
<details>
  <summary>Exemple GIF (cliquer)</summary> 
  
![userdata](https://i.imgur.com/KnLhM1X.gif)
</details>

## Epic Games Store
L'Epic games store étant très mal fait, il n'y a pas de méthode simple pour déplacer un jeu. Il existe cependant une méthode pour le faire.
- Faire un backup du jeu en question (dossier d'installation par défaut : **C:\Program files\Epic Games**)
- Désinstaller le jeu sur l'Epic games store
- Réinstaller le jeu sur l'Epic games store, là ou vous voulez qu'il soit.
- Attendre que le téléchargement commence, laisser passer 2-3%
- Annuler l'installation.
- Aller dans le dossier de destination, là ou vous voulez que le jeu soit
- Copier le backup du jeu dans ce dossier (en disant oui si il vous demande de remplacer des fichiers)
- Relancer l'installation dans l'Epic games launcher
- Il devrait vérifier les fichiers, puis considérer le jeu comme installé.
<details>
  <summary>Exemple GIF (cliquer)</summary> 
  
![EGS](https://i.imgur.com/iaOgkDl.gif)
</details>

## Uplay
Uplay permet assez facilement de déplacer et localiser des dossiers de jeux. Pour backup un jeu il suffit de cliquer sur le jeu -> propriétés -> ouvrir le dossier. Une fois dans l'exporateur de fichiers, la combinaise de touche **ALT+HAUT** vous permettra de remonter d'un cran. On peut ensuite prendre le dossier du jeu, et le copier ailleurs.
Pour récupérer un jeu qu'on a back, il suffit de cliquer sur ce jeu dans le launcher, puis sur "localiser le jeu installé", juste en dessous du bouton télécharger.
<details>
  <summary>Exemple GIF (cliquer)</summary> 
  
![Imgur](https://github.com/Piwielle/Backup-logiciels/blob/main/9llPPWntqb.gif)
</details>

# Paramètres de jeux : 

## CS GO
Pour CS:GO, tous les paramètres seront sauvegardés si vous faites une sauvegarde du dossier du jeu, et du dossier **userdata** de Steam, comme indiqué dans [Steam](#steam)  
Si vous souhaitez savoir exactement quels sont les dossiers à récupérer (pour emmener sa config en LAN, par exemple), il vous faut : 
- le dossier **"cfg"** de **C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo** (ou autre dossier d'installation)
- le dossier **"730"** de **C:\Program Files (x86)\Steam\userdata\STEAMID**. Pour connaître votre STEAMID, vous pouvez utiliser le site https://steamidfinder.com/. Rentrez votre profil, et la ligne **steamID3** correspondra à un dossier de **userdata**.
Récuperez ces deux dossiers, remettez les à leur place sur un autre PC, et vous aurez votre config complète.
## Valorant
Les paramètres de Valorant étant tous synchronisés en ligne, y'a rien à backup.  
Ceci dit, on est pas à l'abri d'un bug, alors je vous suggère **fortement** de prendre 2 minutes pour noter exactement vos réglages, sensi, etc. Sauvegarder ça dans une note de Google Keep (ou équivalent) est un moyen simple de ne jamais les perdre.
## R6S
Les paramètres de R6S sont situés dans le dossier **C:\Users\NOM D'UTILISATEUR\Documents\My Games**. Vous pouvez accéder directement au dossier sur n'importe quel PC en appuyant sur les touches **windows + R** puis en collant 
- **%USERPROFILE%\Documents\My Games**  

Une fois dans ce dossier, récupérez le fichier **GameSettings.ini** (ou sauvegardez même le dossier complet "My Games", c'est jamais perdu).

## Fortnite
Comme Valorant, certains paramètres de Fortnite sont censés être sauvegardés dans le cloud (les keybinds, notamment).  
Pour les paramètres graphiques du jeu, vous pouvez backup le fichier **GameUserSettings.ini** situé dans
- **%localappdata%\FortniteGame\Saved\Config\WindowsClient** (appuyez sur les touches **windows + R** puis coller ce chemin pour y accéder)

## League of Legends
Les paramètres de league of legends sont les fichiers "**game.cfg**" et "**PersistedSettings.json**" dans le dossier
- **C:\Riot Games\League of Legends\Config**
Il faudra les sauvegarder quelque part, puis les remettre dans ce dossier après une réinstallation.

/!\ Il faudra temporairement mettre ces fichiers en **lecture seule** (clic droit sur le fichier -> propriétés) pour la première fois que vous allez lancer le jeu, pour qu'ils s'appliquent. Une fois les paramètres appliqués, vous pouvez aller enlever le mode lecture seule. Il est important de l'enlever, sans quoi vous ne pourrez plus changer vos settings.

## PUBG
Le fichier de paramètres à sauvegarder est le "**GameUserSettings.ini**", il est situé dans le dossier
- **%localappdata%\TslGame\Saved\Config\WindowsNoEditor** (appuyez sur les touches **windows + R** puis coller ce chemin pour y accéder)

Il faudra le sauvegarder avant de réinstaller, puis le remettre dans le dossier après réinstallation du jeu (il faudra lancer le jeu une première fois avant de remplacer le fichier).

## Apex Legends
POur sauvegarder les fichiers de ce jeu, sauvegardez tous les fichiers et dossiers dans
- **%userprofile%\Saved Games\Respawn\Apex**

Une fois le jeu réinstallé, il faudra remettre tous les dossiers et fichiers au même endroit.

## COD Warzone
La majorité des settings sont censés être sauvegardés en ligne. Cependant, vous pouvez récupérer le fichier "**config.cfg**" situé dans le dossier
- **%userprofile%\Documents\Call of Duty Modern Warfare\players**

Il faudra le sauvegarder avant de réinstaller, puis le remettre dans le dossier après réinstallation du jeu (il faudra lancer le jeu une première fois avant de remplacer le fichier).

## Minecraft
Le plus simple pour Minecraft reste de sauvegarder le dossier entier de Minecraft, qui contient vos mondes, shaders, resources packs, etc. Pour faire ça, il faudra sauvegarder le dossier entier "**.Minecraft"** situé dans
- **%appdata%**

Il faudra le sauvegarder avant de réinstaller, puis le remettre dans le même dossier après réinstallation du jeu (il faudra lancer le jeu une première fois avant de remplacer le dossier).


# Logiciels

## MSI Afterburner
Pour Afterburner, il faudra sauvegarder un dossier, et un fichier. D'abord, le dossier "**Profiles**", et le fichier "**MSIAfterburner.cfg**", les deux situés dans le dossier
-  %programfiles(x86)%\MSI Afterburner\ 

Pour la réinstallation, il faudra réinstaller MSI Afterburner, le lancer une première fois, puis le fermer, remettre le dossier et le fichier dans le même dossier que pour la sauvegarde, puis relancer Afterburner.

## OBS Studio
Pour OBS, il y a 3 dossiers principaux à sauvegarder : 
- le dossier "**obs-studio**" qui contient les profils et scènes, situé dans **%appdata%**
- le dossier "**obs-plugins**", situé dans **%programfiles%\obs-studio**
- le dossier contenant vos assets, images, vidéos, etc, que vous avez mis quelque part sur votre PC

Pour la réinstallation, il faudra réinstaller OBS Studio, le lancer une première fois, puis le fermer, remettre les dossiers dans les même dossiers que pour la sauvegarde, puis relancer OBS.
