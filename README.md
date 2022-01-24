# ModAccessMenu

Designing a quickly accessible menu for controllers and mobile ports to ease the use of complex DOOM mods.

_Full support for **[GZDoom v4+](https://zdoom.org)**_  

### [DOWNLOAD](https://github.com/FelesNoctis/ModAccessMenu/releases "Download Link")  

![Stable Version](https://img.shields.io/github/v/release/FelesNoctis/ModAccessMenu?label=stable "Stable Version")  
![Experimental Version](https://img.shields.io/github/v/release/FelesNoctis/ModAccessMenu?include_prereleases&label=experimental "Experimental Version")

## Usage

* Load late, generally after the mods you want in the menu.
* __ModAccessMenu__ pk3 first, then __MAMmodule__ pk3s.

## Features

* Single bindable button to open a menu for supported mods
* Quickmenu list at the top of main menu for most common commands
* Modular installation: Customize your menu with only the mods you're using!  
&#10240;
* **Mod Support**:
  * *(DRLA)* DoomRL Arsenal ([ZDoom](https://forum.zdoom.org/viewtopic.php?f=43&t=37044))
  * *(HDST)* Hideous Destructor ([ZDoom](https://forum.zdoom.org/viewtopic.php?f=43&t=12973))
    * *(HDFLWR)* HD - Follower (testing) ([GitLab](https://gitlab.com/accensi/hd-addons/follower/))
  * *(RPGL)* RPG Lite (2.x) ([Github](https://github.com/dashodanger/Doom-RPG-lite))

### Mod Support Notes

* **Hideous Destructor**
  * Support created by request, however: this mod was never meant to be played with a limited control set. Hell, the author explicitly states that it wasn't even really intended to allow the player to succeed in the first place. Because I don't play it myself, there may be a few controls missing here and there or extra functionality that would be useful. If so, please let me know. I fully expect this addon to be an ongoing project considering how complicated HDest is.
* **HD - Follower**
  * Suggested by the same person who requested Hideous Destructor. Right now only gives an option to open the provided menu. This HD addon features a fully ZScripted menu that's controlled by the number keys, so I'm not even sure how possible it is to access those functions from MENUDEF in the first place, let alone if the addon was designed with such a thing in mind. This addon may be put on indefinite hold until I can learn more.
