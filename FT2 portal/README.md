# FT2 Portal

A comprehensive helper for the **Fairy Tales II** goal on Aardwolf MUD. This plugin uses GMCP room tracking to provide real-time instructions and interactive hyperlinks, alongside a dedicated miniwindow for item shopping and task navigation.

## Commands

| Command | Description |
| :--- | :--- |
| **ft2 guide on** | Displays the FT2 Guide miniwindow |
| **ft2 guide off** | Hides the FT2 Guide miniwindow |
| **ft2 update** | Checks GitHub and installs the latest version |
| **ft2 help** | Shows the in-game help file |

## Features

* **Automated Guidance**: Uses GMCP `room.info` to show exactly what to do as you walk through Tasks 9-21.
* **Interactive Links**: Clickable hyperlinks for killing mobs, wearing gear, and giving items to NPCs.
* **Shopping Assistant**: One-click mapping to every shop required for the goal (Dirks, Hats, Chocolate, etc.).
* **Dynamic UI**: Built using themed miniwindows for a clean look that integrates with your MUD UI.

## Installation

1.  Download the `FT2_portal.xml` file.
2.  Place it in your MUSHclient `worlds/plugins` folder.
3.  In MUSHclient, press **Ctrl + Shift + P** and click **Add** to install.
