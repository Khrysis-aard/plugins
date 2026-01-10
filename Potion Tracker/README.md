# Potion Tracker (PTW) for MUSHclient

A comprehensive inventory tracking and automation system for MUDs. Originally designed for potions, v1.600 now supports Scrolls, Food, Pills, Wands, and Staffs with full automation for restocking and smart-usage.

## 🚀 Key Features in v1.600
- **Smart Usage:** One command (`ptw use <category>`) to consume the best item available.
- **Restock Automation:** Automatically travels to shops, buys items, and returns you to your starting point.
- **Shop Linking:** "Appraise" items to automatically save their room ID, buy keyword, and level.
- **Inventory Sync:** Instantly syncs your window counts with your actual inventory and bags.
- **Held Item Logic:** Detects if you drop or give away a Staff/Wand you were currently holding.

## 📥 Installation
1. Download the `Potion_tracker.xml` file.
2. Place it in your MUSHclient `worlds/plugins` folder.
3. In MUSHclient, go to **File -> Plugins -> Add** and select the file.

## ⌨️ Common Commands

| Command | Description |
| :--- | :--- |
| `ptw help` | View the full in-game help file. |
| `ptw appraise <item> <cat>` | Link an item to a shop and category (e.g., `mana`). |
| `ptw restock <cat> <#>` | Go buy a specific amount of items from the linked shop. |
| `ptw use <cat>` | Quaff/Recite/Eat the best item in that category. |
| `ptw sync` | Manually sync window counts with your bags. |
| `ptw list` | Display your database of approved items and shop locations. |

## 🛠 Configuration
- `ptw font <size>`: Change the miniwindow font size.
- `ptw order`: Toggle between `Name:Count` and `Count:Name`.
- `ptw quiet <on/off>`: Toggle silencing of "You quaff..." messages.

---
*Developed for Aardwolf MUD / MUSHclient.*
