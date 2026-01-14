# Atk Aoe Manager (AAM) for Aardwolf MUD

A dynamic spell and skill management system that automatically updates your active combat commands as you level up and master new abilities.

## 🚀 Key Features
- **Auto-Leveling Logic:** Add a list of spells (e.g., Fireball, Incinerate, Inferno). As you mastery them (95% or Expert), the plugin automatically sets the highest one as your active attack.
- **Unified Combat Aliases:** Use `aam atk`, `aam aoe`, or `aam skill` in your macros. You never have to change your macros again when you tier or change classes.
- **Short Syntax Mapping:** Map long skill names to short, custom commands (e.g., map "Backstab" to "bs").
- **Multi-Category Tracking:** Separate watch lists for Primary Attacks (Patk), Area of Effect (AoE), and Skills.

## 📥 Installation
1. Download the `Atk_Aoe_Manager.xml` file.
2. Place it in your MUSHclient `worlds/plugins` folder.
3. In MUSHclient, go to **File -> Plugins -> Add** and select the file.

## ⌨️ Essential Commands

| Command | Description |
| :--- | :--- |
| `aam add <patk\|aoe\|skill> <name>` | Add a spell/skill to the auto-upgrade watch list. |
| `aam setskill <full> to <short>` | Create a short alias for a long skill name. |
| `aam status` | View your currently active Atk, AoE, and Skill. |
| `aam list all` | Show all items currently in your watch lists. |
| `aam atk [target]` | Casts your currently active Primary Attack. |
| `aam skill [target]` | Uses your currently active Skill. |
| `aam aoe` | Casts your currently active AoE. |

## 🛠 How to use the "Auto-Upgrade"
1. Add all potential spells for your class: `aam add patk Fireball`, `aam add patk Incinerate`.
2. When the MUD says "You are now an expert in Incinerate," the plugin automatically switches your `aam atk` command to use Incinerate instead of Fireball.

---
*Developed by Khrysis for Aardwolf MUD.*
