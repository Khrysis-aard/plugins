# Khrysis Plugin Manager (KPM)

The central hub for managing, updating, and installing all of my Aardwolf MUSHclient plugins.

## 🌟 Why use KPM?
Instead of manually checking GitHub for updates to the Potion Tracker or Atk_Aoe_Manager, KPM provides a one-click dashboard to keep your entire setup current.

## 📥 Installation
1. Download the `Khrysis_Plugin_Manager.xml` file.
2. Place it in your MUSHclient `worlds/plugins` folder.
3. In MUSHclient, go to **File -> Plugins -> Add** and select the file.
4. Type `kpm list` to see available plugins.

## 🖥 The Dashboard (`kpm list`)
The dashboard gives you a live view of:
- **Name:** The plugin title.
- **Installed:** Your current local version.
- **Remote:** The latest version available on GitHub.
- **Status:** Shows if the plugin is Loaded, Not Installed, or needs an Update.
- **Actions:** Clickable `[Install]`, `[Update]`, or `[Remove]` links for instant management.

## ⌨️ Commands

| Command | Description |
| :--- | :--- |
| `kpm list` | Open the interactive management dashboard. |
| `kpm update` | Self-update the Plugin Manager itself. |
| `kpm check` | Scan all tracked plugins for updates via the terminal. |
| `kpm help` | View the help file and command list. |

---
*Developed by Khrysis for Aardwolf MUD.*
