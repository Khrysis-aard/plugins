# Practice All or List

A flexible training assistant for Aardwolf MUD that allows players to practice all available skills at once, or maintain custom "Tier" and "Spellup" lists for more targeted training.

## Commands

| Command | Description |
| :--- | :--- |
| **dprac all** | Practices all available skills/spells to 95% |
| **dprac list** | Lists all skills currently available to be practiced |
| **cprac custom** | Practices only the items in your custom list |
| **cprac tier** | Practices items in your tier list (useful for new tiers/remorts) |
| **cprac all** | Practices everything in your custom, tier, and spellup lists |
| **cprac spellup** | Toggles auto-practicing of curative/movement/passive spells |
| **pal update install** | Checks GitHub and installs the latest version |

## Features

* **Custom Lists**: Maintain specific lists of spells (like heals, pets, or attacks) to practice selectively.
* **Tier Management**: Dedicated list for skills you prioritize immediately after hitting a new tier or remorting.
* **Auto-Spellup Detection**: Automatically scans your learned spells for curative, passive, and movement abilities to keep them topped off.
* **Rebirth Automation**: Detects when you remort/reincarnate and can automatically trigger a scan of your available skills.
* **Smart Calculation**: Calculates exactly how many practice sessions you need to complete your chosen list.

## Installation

1.  Download the `Practice_all_or_list.xml` file.
2.  Place it in your MUSHclient `worlds/plugins` folder.
3.  In MUSHclient, press **Ctrl + Shift + P** and click **Add** to install.

---
*Developed by Khrysis for Aardwolf MUD.*
