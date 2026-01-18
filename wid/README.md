# WID (Weapon ID Tracker)

A utility for Aardwolf MUD that captures and stores the unique identification numbers (IDs) of your Primary, Secondary, and Held items. This ensures you always equip the correct specific items, even when carrying multiple pieces of equipment with similar names.

## Commands

| Command | Description |
| :--- | :--- |
| **wid** | Displays the names and IDs currently stored in the tracker. |
| **won** | Equips your stored IDs based on your preferred mode (Dual/Held). |
| **woff** | Removes the weapons/items currently tracked by the plugin. |
| **wid off** | **Manual Sync**: Forces the plugin to re-scan your equipment and update IDs. |
| **wid help** | Displays the in-game help menu. |

## Features

* **Auto-Sync on Login**: Automatically performs an `eqdata` scan on the first tick after loading to grab your current weapon IDs.
* **Keep-Flag Filter**: Intelligent triggers look for the (K) flag to ensure it only tracks your "permanent" gear for the primary and secondary slots.
* **Smart Swapping**: `won` and `woff` check your current equipment state before sending commands to minimize screen spam.
* **Persistence**: Saved IDs remain stored in your plugin variables across sessions.

## Installation

1. Download the `wid.xml` file.
2. Place it in your MUSHclient `worlds/plugins` folder.
3. In MUSHclient, press **Ctrl + Shift + P** and click **Add** to install.
